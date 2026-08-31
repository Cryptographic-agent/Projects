# Projects — Software Engineering Portfolio

Hai dự án sản phẩm thực tế, trình độ nâng cao, kết hợp **Web + AI/ML + DevOps**.

| # | Thư mục | Dự án | Trọng tâm kỹ thuật |
|---|---------|-------|--------------------|
| 1 | `01-rag-knowledge-assistant` | Trợ lý tri thức hỏi–đáp tài liệu (RAG) | LLM/RAG, vector DB, FastAPI, Next.js, Docker |
| 3 | `03-ecommerce-recommender` | Sàn TMĐT có gợi ý cá nhân hóa | Microservices, recommendation ML, thanh toán, CI/CD |

## Thứ tự thực hiện
Theo yêu cầu: **hoàn thiện Dự án 1 trước**, xong mới sang Dự án 3. Mỗi dự án làm theo từng milestone,
xong milestone này mới sang milestone kế tiếp (xem `docs/ROADMAP.md` trong mỗi dự án).

## Quy ước chung
- Mã nguồn tách `backend/` và `frontend/`.
- Mỗi dự án tự chứa: có `README.md`, `docs/`, `.env.example`, `docker-compose.yml`.
- Commit theo Conventional Commits: `feat:`, `fix:`, `docs:`, `chore:`, `refactor:`, `test:`.
- Không commit secrets; luôn dùng `.env` (đã gitignore) sao chép từ `.env.example`.

## Trạng thái
- [x] Dự án 1 — HOÀN TẤT (backend test tích hợp pass, frontend build pass)
- [x] Dự án 3 — HOÀN TẤT (backend test tích hợp pass, storefront build pass)
