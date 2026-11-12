# vinh-skills

Bộ skill cá nhân của Vinh cho Claude Code.

| Plugin | Nguồn | Dùng để |
|---|---|---|
| `frontend-design` | Bản sao trong repo này (từ `anthropics/claude-plugins-official`, Apache-2.0) | Thiết kế giao diện có chủ đích |
| `ui-ux-pro-max` | `nextlevelbuilder/ui-ux-pro-max-skill` | Kho style, màu, font, quy tắc UX |
| `ponytail` | `DietrichGebert/ponytail` | Giảm code, giảm token |
| `watch` | `bradautomates/claude-video` | Xem video, đọc transcript |

Ba plugin sau trỏ thẳng tới repo gốc, nên luôn lấy bản mới nhất khi cập nhật.

## Cài đặt (trong Claude Code)

```
/plugin marketplace add phantaivinhw264-ctrl/vinh-skills
/plugin install frontend-design@vinh-skills
/plugin install ui-ux-pro-max@vinh-skills
/plugin install ponytail@vinh-skills
/plugin install watch@vinh-skills
```

Bật tự động cập nhật: `/plugin` → Marketplaces → `vinh-skills` → Enable auto-update.

`watch` cần thêm: Python 3.10+, ffmpeg, yt-dlp (macOS: `brew install python ffmpeg yt-dlp`).
