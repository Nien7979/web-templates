# Nguồn & giấy phép

Tổng hợp ngày 23/11/2026 từ catalog
[aitmpl.com](https://aitmpl.com) (Claude Code Templates —
kho tổng davila7/claude-code-templates).

## Nguồn chính

| Nguồn | Vai trò | Giấy phép |
|---|---|---|
| [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates) | Kho tổng chứa toàn bộ file skill/agent trong repo này (2.019 component tại thời điểm tổng hợp) | MIT — Copyright (c) 2025 Daniel (San) Ávila (file `LICENSE` ở gốc repo này) |
| [aitmpl.com](https://aitmpl.com) | Catalog duyệt + API công khai của kho tổng (`/api/v1/catalog.json`, `/api/v1/version.json`) | MIT |
| [navedux/illos-skills](https://github.com/navedux/illos-skills) | Nguồn của skill `illos-library` | MIT — Copyright (c) 2026 Naved Alam |

## Giấy phép theo skill

- **MIT (kho tổng davila7):** áp dụng cho mọi skill/agent không có file
  `LICENSE.txt` riêng trong thư mục của nó.
- **Apache 2.0 (skill gốc Anthropic):** `frontend-design`,
  `theme-factory`, `figma`, `figma-implement-design`,
  `develop-web-game`, `render-deploy`, `web-artifacts-builder`,
  `webapp-testing` — mỗi thư mục đều giữ nguyên file `LICENSE.txt`
  gốc. Chi tiết xem [ANTHROPIC_ATTRIBUTION.md](ANTHROPIC_ATTRIBUTION.md).
- **MIT (navedux):** `illos-library` — file `LICENSE` trong thư mục skill.

## File đã lược bỏ khi tổng hợp

Công cụ đẩy GitHub chỉ nhận file text UTF-8 nên các file nhị phân sau
không có trong repo (lấy bản gốc tại link nguồn của từng skill):

| File | Lý do |
|---|---|
| `figma/assets/figma.png`, `figma-implement-design/assets/figma.png`, `develop-web-game/assets/game.png`, `render-deploy/assets/render.png` | Icon PNG 100×100 (chỉ để trang trí) |
| `theme-factory/theme-showcase.pdf` (124 KB) | File PDF mẫu theme |
| `web-artifacts-builder/scripts/shadcn-components.tar.gz` | Gói nén nhị phân |

## Ghi chú thu thập

- Toàn bộ file trong repo được **đọc và copy nguyên trạng**, không chỉnh
  sửa nội dung, không chạy thử bất kỳ script nào trong quá trình tổng hợp.
- Số liệu lượt tải trong README lấy từ catalog aitmpl.com ngày 23/11/2026.
- Catalog gốc có 2.019 component; repo này chọn 39 mục trực tiếp phục
  vụ build & thiết kế website. Các mục khác xem [THAM-KHAO.md](THAM-KHAO.md).
