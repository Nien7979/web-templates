# Cách dùng kho web-templates

## 1. Lấy repo về

```bash
git clone https://github.com/Nien7979/web-templates.git
cd web-templates
```

## 2. Dùng skill với Claude Code / Free Claude Code (FCC)

Skill là thư mục chứa `SKILL.md` — Claude tự đọc khi công việc khớp với
mô tả trong file đó.

```bash
# Cài 1 skill (ví dụ frontend-design) vào Claude Code
cp -r skills/creative-design/frontend-design ~/.claude/skills/

# Cài hết skill thiết kế
cp -r skills/creative-design/* ~/.claude/skills/

# Cài hết skill lập trình web
cp -r skills/development/* ~/.claude/skills/
```

Hoặc cài bản gốc từ kho tổng (không cần repo này):

```bash
npx claude-code-templates@latest --skill creative-design/frontend-design
npx claude-code-templates@latest --skill creative-design/ui-ux-pro-max
npx claude-code-templates@latest --skill development/senior-frontend
```

## 3. Dùng agent (subagent)

Agent là file `.md` đơn, copy vào thư mục agents của Claude Code:

```bash
cp agents/development-team/frontend-developer.md ~/.claude/agents/
cp agents/development-team/fullstack-developer.md ~/.claude/agents/
cp agents/development-tools/code-reviewer.md ~/.claude/agents/
```

Sau đó gọi bằng tên agent trong phiên Claude Code.

## 4. Dùng với Codex / ChatGPT Codex

Skill là file Markdown nên Codex đọc được trực tiếp: mở `SKILL.md` của
skill cần dùng và làm theo, hoặc copy thư mục skill vào nơi Codex
cấu hình skill. Một số skill kèm file `agents/openai.yaml` để Codex
nhận diện.

## 5. Dùng thủ công (không cài gì)

Mở `SKILL.md` của skill cần dùng, đọc phần mô tả + quy tắc, rồi
áp dụng khi viết prompt hoặc làm việc với AI. Cách này dùng được với
bất kỳ AI nào (Muse, ChatGPT, Gemini, Claude…).

## 6. Quy trình gợi ý khi làm một website mới

1. **Lên ý tưởng + phong cách:** `frontend-design` + `ui-ux-pro-max`
   (+ `theme-factory` để chọn theme, `illos-library` để lấy minh hoạ).
2. **Làm khung + component:** `tailwind-patterns` + `react-ui-patterns`
   (hoặc `web-artifacts-builder` nếu làm artifact HTML).
3. **Code:** agent `frontend-developer` / `fullstack-developer`,
   skill `senior-frontend` + `senior-backend` + `senior-architect`.
4. **Kiểm tra:** `web-design-guidelines` + `accessibility-auditor` +
   agent `code-reviewer`, test bằng `webapp-testing` (Playwright).
5. **Deploy:** `render-deploy` (mẫu Render) hoặc `senior-devops`
   (áp dụng ý tưởng pipeline cho Railway/Vercel…).

## 7. An toàn khi dùng script kèm theo skill

- Script `.py` / `.js` / `.mjs` / `.sh` trong các thư mục skill
  **chưa từng được chạy** trong quá trình tổng hợp kho này.
- Trước khi chạy bất kỳ script nào: mở file ra đọc, hiểu nó làm gì,
  chỉ chạy khi tin tưởng.
- Skill cần API key (ví dụ `figma` cần Figma MCP, `webapp-testing`
  cần Playwright đã cài) sẽ tự báo khi thiếu — không nhập key lạ
  vào script không rõ nguồn.
