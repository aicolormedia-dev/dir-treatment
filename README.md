# ColorMedia Skills — Claude Code Marketplace

Bộ skill nội bộ ColorMedia / MMCorp cho [Claude Code](https://claude.com/claude-code).
Cài qua cơ chế plugin marketplace của Claude Code.

## Cài đặt (dành cho người dùng)

Trong Claude Code, chạy:

```
/plugin marketplace add hoangdung-colormedia/colormedia-skills
/plugin install colormedia@colormedia-skills
```

> Thay `hoangdung-colormedia/colormedia-skills` bằng `owner/repo` GitHub thật của bạn
> (định dạng ngắn `owner/repo`, hoặc URL đầy đủ `https://github.com/owner/repo.git`).

Sau khi cài, khởi động lại phiên Claude Code. Skill sẽ xuất hiện dưới namespace
`colormedia:` — ví dụ gọi treatment bằng:

```
/colormedia:treatment
```

hoặc chỉ cần nói tự nhiên (vd "tạo treatment cho dự án này") — Claude sẽ tự gọi.

## Skill trong bộ này

| Skill | Mô tả |
|---|---|
| `treatment` | Kiến trúc & dựng hồ sơ Treatment đạo diễn (v1.3 — generate-first): 3 Điểm Chạm, storyboard, tự tạo ảnh (ChatGPT Image 2), reference, nhạc (Suno), ráp Canva + PPTX. |

## Cấu trúc repo

```
colormedia-skills/
├── .claude-plugin/
│   └── marketplace.json          # khai báo marketplace + danh sách plugin
├── plugins/
│   └── colormedia/
│       ├── .claude-plugin/
│       │   └── plugin.json        # manifest plugin
│       └── skills/
│           └── treatment/
│               ├── SKILL.md       # entry point (frontmatter name + description)
│               └── references/
│                   └── treatment_architecture_v1_3.md   # spec đầy đủ
└── README.md
```

## Cập nhật skill

1. Sửa `plugins/colormedia/skills/treatment/SKILL.md` hoặc file trong `references/`.
2. Tăng `version` trong `plugin.json` + `marketplace.json`.
3. `git commit` & `git push`.
4. Người dùng chạy `/plugin marketplace update colormedia-skills` rồi cài lại.

---
© ColorMedia / MMCorp. License: MIT.
