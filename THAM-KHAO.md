# Tham khảo — những mục KHÔNG đưa vào repo

Các mục dưới đây **không được copy file vào repo** vì trả phí, bản quyền
kín, cần API key trả phí, nằm ngoài phạm vi "build & thiết kế website",
hoặc không đọc được bằng cách đọc text. Chỉ ghi link để tham khảo.

## 1. Nhóm Templates trong catalog

- Catalog có nhóm **Templates (14 mục)**
  nhưng nội dung tải bằng JavaScript nên không liệt kê được bằng cách đọc
  text trang. Muốn xem đủ 14 mẫu này cần mở catalog bằng trình duyệt.
- Catalog gốc aitmpl.com cũng không có loại `templates` trong API
  (`/api/v1/` chỉ có agents, commands, mcps, settings, hooks, skills,
  loops, mods) — 14 mục Templates là cách nhóm riêng trong giao diện
  web của catalog.

## 2. Minh hoạ Illos Pro (trả phí)

- Skill `illos-library` trong repo chỉ dùng minh hoạ **miễn phí** của
  Illos.dev. Minh hoạ Pro và skill Pro theo theme xem tại
  https://illos.dev/pro — trả phí, không copy preview.

## 3. Skill cần API key trả phí (không đưa vào)

| Skill | Cần key | Link gốc |
|---|---|---|
| imagegen | `OPENAI_API_KEY` | https://www.aitmpl.com/component/skills/creative-design/imagegen |
| luma-imagegen | `LUMA_API_KEY` | https://www.aitmpl.com/component/skills/creative-design/luma-imagegen |
| patentfig | `PATENTFIG_API_KEY` | https://www.aitmpl.com/component/skills/creative-design/patentfig |

## 4. Skill ngoài phạm vi website (không đưa vào, có link gốc để tự lấy)

| Skill | Vì sao không đưa vào | Link gốc |
|---|---|---|
| canvas-design | Làm poster/art PNG/PDF, kèm ~40 font TTF (nặng) | https://www.aitmpl.com/component/skills/creative-design/canvas-design |
| game-development | Làm game (Godot/Unity/Unreal…) | https://www.aitmpl.com/component/skills/creative-design/game-development |
| remotion-best-practices | Làm video bằng Remotion/React | https://www.aitmpl.com/component/skills/creative-design/remotion-best-practices |
| marp-slide | Làm slide Marp | https://www.aitmpl.com/component/skills/creative-design/marp-slide |
| meme-factory | Tạo meme | https://www.aitmpl.com/component/skills/creative-design/meme-factory |
| slack-gif-creator | Tạo GIF cho Slack | https://www.aitmpl.com/component/skills/creative-design/slack-gif-creator |
| executing-marketing-campaigns | Chạy chiến dịch marketing | https://www.aitmpl.com/component/skills/creative-design/executing-marketing-campaigns |
| draw-io / excalidraw / c4-architecture | Vẽ sơ đồ (đã có diagrammer + mermaid-diagrams trong repo) | https://aitmpl.com (tìm theo tên) |
| algorithmic-art | Nghệ thuật sinh bằng p5.js | https://www.aitmpl.com/component/skills/creative-design/algorithmic-art |

## 5. Kho skill tổng hợp khác (để mở rộng sau)

| Kho | Mô tả | Giấy phép | Link |
|---|---|---|---|
| anthropics/skills | Kho skill gốc của Anthropic (frontend-design, theme-factory, web-artifacts-builder…) | Apache 2.0 | https://github.com/anthropics/skills |
| mattpocock/skills | 38 skill kinh nghiệm senior software engineering | — | https://github.com/mattpocock/skills |
| obra/superpowers | Framework skill + phương pháp phát triển phần mềm cho agent | — | https://github.com/obra/superpowers |
| affaan-m/ECC | 261+ skill, 64+ agent, 84+ lệnh tối ưu agent | — | https://github.com/affaan-m/ECC |
| davila7/claude-code-templates | Kho tổng 2.019 component (nguồn của repo này) | MIT | https://github.com/davila7/claude-code-templates |

(Giấy phép của 3 kho giữa chưa kiểm chứng trong đợt này — kiểm tra file
LICENSE của từng kho trước khi copy file từ đó.)
