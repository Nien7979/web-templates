# Kho Template & Skill Build Website — web-templates

Kho skill và agent **miễn phí / mã nguồn mở** để build và thiết kế website bằng AI
(Claude Code, Codex, Free Claude Code…), tổng hợp từ thư viện
[AI Templates của Phan Đông Giang](https://phandonggiang.com/ai-templates)
— thực chất là catalog [Claude Code Templates](https://aitmpl.com) /
[github.com/davila7/claude-code-templates](https://github.com/davila7/claude-code-templates)
(2.019 component, giấy phép MIT).

> Tổng hợp ngày 23/11/2026. Chỉ đưa vào repo những tài nguyên miễn phí / mã nguồn
> mở / giấy phép cho phép dùng lại. Mục trả phí hoặc bản quyền kín nằm ở
> [THAM-KHAO.md](THAM-KHAO.md) — chỉ có link, không copy file.

## Có gì trong kho

| Nhóm | Số lượng | Thư mục |
|---|---|---|
| Skill thiết kế giao diện | 20 | `skills/creative-design/` |
| Skill lập trình web | 8 | `skills/development/` |
| Agent (subagent) | 11 | `agents/` |
| **Tổng cộng** | **39** | |

Lượt tải trong bảng là số liệu từ catalog aitmpl.com ngày 23/11/2026.
Cột giấy phép: `MIT` = theo giấy phép MIT của kho tổng davila7
(trừ khi thư mục skill có file `LICENSE.txt` riêng);
`Apache 2.0` = skill gốc của Anthropic, xem `ANTHROPIC_ATTRIBUTION.md`.

## 1. Skill thiết kế giao diện — `skills/creative-design/`

| Skill | Mô tả | Giấy phép | Lượt tải |
|---|---|---|---|
| [frontend-design](skills/creative-design/frontend-design/) | Hướng dẫn thiết kế giao diện đặc sắc, có chủ đích: định hướng thẩm mỹ, typography, tránh kiểu "mẫu mặc định" | Apache 2.0 | 54.576 |
| [ui-ux-pro-max](skills/creative-design/ui-ux-pro-max/) | Trí tuệ thiết kế UI/UX: 50 style, 21 bảng màu, 50 cặp font, 20 biểu đồ, 9 stack (React, Next.js, Vue, Svelte, Tailwind, shadcn/ui…) | MIT | 31.613 |
| [ui-design-system](skills/creative-design/ui-design-system/) | Bộ công cụ design system: sinh design token, tài liệu component, tính responsive, bàn giao cho dev | MIT | 18.168 |
| [mobile-design](skills/creative-design/mobile-design/) | Tư duy thiết kế mobile-first cho iOS/Android, React Native, Flutter | MIT | 10.742 |
| [theme-factory](skills/creative-design/theme-factory/) | 10 theme có sẵn để tạo phong cách cho artifact, slide, tài liệu, landing page HTML | Apache 2.0 | 3.924 |
| [ux-researcher-designer](skills/creative-design/ux-researcher-designer/) | Nghiên cứu UX: persona theo dữ liệu, journey map, usability testing | MIT | 4.098 |
| [tailwind-patterns](skills/creative-design/tailwind-patterns/) | Nguyên tắc Tailwind CSS v4: cấu hình CSS-first, container query, design token | MIT | 2.887 |
| [scroll-experience](skills/creative-design/scroll-experience/) | Trải nghiệm cuộn trang: parallax, kể chuyện bằng cuộn, trang điện ảnh kiểu Apple/NYT | MIT | 2.375 |
| [web-design-guidelines](skills/creative-design/web-design-guidelines/) | Rà soát code UI theo Web Interface Guidelines: accessibility, UX | MIT | 2.306 |
| [premium-web-design](skills/creative-design/premium-web-design/) | Thiết kế web cao cấp chuẩn Awwwards, dạng component React (.jsx) | MIT | 1.384 |
| [mermaid-diagrams](skills/creative-design/mermaid-diagrams/) | Vẽ sơ đồ bằng Mermaid: flowchart, sequence, ERD, C4, state, gantt… | MIT | 1.241 |
| [figma](skills/creative-design/figma/) | Lấy context thiết kế từ Figma qua MCP server, chuyển node thành code | Apache 2.0 | 925 |
| [figma-implement-design](skills/creative-design/figma-implement-design/) | Dịch node Figma thành code production đúng 1:1 qua Figma MCP | Apache 2.0 | 737 |
| [interactive-portfolio](skills/creative-design/interactive-portfolio/) | Làm portfolio gây ấn tượng, biến visitor thành cơ hội việc làm/khách hàng | MIT | 683 |
| [develop-web-game](skills/creative-design/develop-web-game/) | Vòng lặp dev + test game web (HTML/JS) bằng Playwright | Apache 2.0 | 393 |
| [diagrammer](skills/creative-design/diagrammer/) | Vẽ sơ đồ SVG phong cách blueprint từ spec JSON | MIT | 137 |
| [claude-d3js-skill](skills/creative-design/claude-d3js-skill/) | Trực quan hoá dữ liệu tương tác bằng d3.js | MIT | — |
| [3d-web-experience](skills/creative-design/3d-web-experience/) | Trải nghiệm 3D cho web: Three.js, React Three Fiber, Spline, WebGL | MIT | — |
| [accessibility-auditor](skills/creative-design/accessibility-auditor/) | Kiểm tra accessibility: WCAG, ARIA, thiết kế bao hàm | MIT | — |
| [illos-library](skills/creative-design/illos-library/) | Minh hoạ SVG động miễn phí từ Illos.dev cho hero, feature, empty state | MIT | 14 |

## 2. Skill lập trình web — `skills/development/`

| Skill | Mô tả | Giấy phép | Lượt tải |
|---|---|---|---|
| [senior-frontend](skills/development/senior-frontend/) | Dùng khi build/sửa/review code giao diện: page, component, form… kèm checklist UI và script kiểm tra | MIT | — |
| [senior-backend](skills/development/senior-backend/) | Backend NodeJS/Express/Go/Python/Postgres/GraphQL/REST: scaffold API, bảo mật, tối ưu DB | MIT | — |
| [senior-architect](skills/development/senior-architect/) | Kiến trúc phần mềm: React/Next/Node, hệ thống mở rộng, bảo trì được | MIT | — |
| [senior-devops](skills/development/senior-devops/) | CI/CD, chiến lược deploy, hạ tầng dưới dạng code | MIT | — |
| [render-deploy](skills/development/render-deploy/) | Deploy app lên Render: sinh render.yaml, có mẫu static-site, Next.js, Express… | Apache 2.0 | 35 |
| [react-ui-patterns](skills/development/react-ui-patterns/) | Pattern UI React hiện đại: loading state, xử lý lỗi, fetch dữ liệu | MIT | — |
| [web-artifacts-builder](skills/development/web-artifacts-builder/) | Làm HTML artifact nhiều component (React, Tailwind, shadcn/ui) kiểu Claude artifact | Apache 2.0 | 354 |
| [webapp-testing](skills/development/webapp-testing/) | Kiểm thử web app local bằng Playwright: verify UI, debug, chụp màn hình | Apache 2.0 | — |

## 3. Agent (subagent) — `agents/`

Agent là file `.md` mô tả một subagent chuyên trách, dùng trong Claude Code
(thư mục `~/.claude/agents/`).

| Agent | Mô tả | Giấy phép | Lượt tải |
|---|---|---|---|
| [development-team/frontend-developer](agents/development-team/frontend-developer.md) | Build frontend hoàn chỉnh React/Vue/Angular, đa framework | MIT | 42.257 |
| [development-team/fullstack-developer](agents/development-team/fullstack-developer.md) | Feature xuyên suốt DB – API – frontend | MIT | 18.757 |
| [development-team/devops-engineer](agents/development-team/devops-engineer.md) | CI/CD, deploy, vận hành cloud | MIT | 7.669 |
| [development-team/backend-developer](agents/development-team/backend-developer.md) | API server, microservice, backend production-ready | MIT | — |
| [development-team/backend-architect](agents/development-team/backend-architect.md) | Kiến trúc backend, chọn mô hình API, tách monolith | MIT | — |
| [development-team/ui-designer](agents/development-team/ui-designer.md) | Thiết kế giao diện, design system, component library | MIT | — |
| [development-team/ui-ux-designer](agents/development-team/ui-ux-designer.md) | Review/audit UI/UX, usability, accessibility | MIT | — |
| [development-team/code-architect](agents/development-team/code-architect.md) | Thiết kế kiến trúc tính năng theo pattern của codebase | MIT | 1.549 |
| [development-team/cli-ui-designer](agents/development-team/cli-ui-designer.md) | Giao diện phong cách terminal bằng công nghệ web hiện đại | MIT | — |
| [accessibility/accessibility-tester](agents/accessibility/accessibility-tester.md) | Audit accessibility WCAG 2.2, ADA / Section 508 / EAA | MIT | 397 |
| [development-tools/code-reviewer](agents/development-tools/code-reviewer.md) | Review code: chất lượng, lỗ hổng bảo mật, best practice | MIT | — |

## Cách dùng

Xem [CACH-DUNG.md](CACH-DUNG.md) — tóm tắt: copy thư mục skill vào
`~/.claude/skills/`, copy file agent vào `~/.claude/agents/`,
hoặc cài bản gốc bằng `npx claude-code-templates@latest --skill <nhóm>/<tên>`.

## Lưu ý quan trọng

- **Script chưa từng được chạy.** Một số skill kèm script `.py` / `.js` / `.mjs` / `.sh`
  (ví dụ `ui-ux-pro-max/scripts/`, `senior-*/scripts/`). Toàn bộ file trong repo
  này chỉ được **đọc và copy**, không chạy thử. Trước khi chạy script nào,
  đọc kỹ nội dung của nó.
- **File nhị phân đã lược bỏ** (công cụ đẩy GitHub chỉ nhận file text UTF-8):
  4 icon PNG 100×100 (figma, render-deploy, develop-web-game),
  `theme-factory/theme-showcase.pdf` (124 KB) và
  `web-artifacts-builder/scripts/shadcn-components.tar.gz`.
  Lấy bản gốc tại link nguồn của từng skill trong [NGUON.md](NGUON.md).
- **Catalog gốc có 2.019 component** (23/11/2026); repo này chỉ chọn **39 mục
  trực tiếp phục vụ build & thiết kế website**. Phần còn lại của catalog
  (AI research, marketing, data…) không nằm trong phạm vi kho này.
- Nhóm **Templates (14 mục)** trên trang phandonggiang.com/ai-templates chạy
  bằng JavaScript nên không liệt kê được bằng cách đọc text — xem ghi chú
  trong [THAM-KHAO.md](THAM-KHAO.md).

## Nguồn & giấy phép

Xem [NGUON.md](NGUON.md) và file [LICENSE](LICENSE).
