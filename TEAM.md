# TEAM — Day04, K4-L3B

**Làm nhóm.** Mỗi người tự viết và commit phần INDIVIDUAL của mình.

## Thông tin bài nộp

- Tên nhóm: Cá nhân - Hoang Phong
- Người đại diện / MSSV: Hoang Phong / 2A202602943
- Tên repo: `K4-L3-DAY04-HoVaTen-MSSV-PromptEngineeringToolCalling`
- URL repo, nhánh nộp, commit chốt: https://github.com/HoangPhong20/K4-L3-DAY04-HoangPhong-2A202602943-PromptEngineeringToolCalling
- Deadline áp dụng và link thông báo đổi hạn nếu có:

## Thành viên

| Họ và tên | MSSV | GitHub | Vai trò và công việc | File/commit/PR |
|---|---|---|---|---|
| Hoang Phong | 2A202602943 | TODO | Toàn bộ bài cá nhân: prompt, tool declarations, eval, safety review, transcript và report | `artifacts/`, `data/eval_group.json`, `runs/`, `transcripts/`, `artifacts/REPORT.md` |

## Nhận xét chung

- Kết quả và bằng chứng: base v0-v3 tăng từ `21/30` lên `29/30`; extension `10/10`; group `7/10`; adversarial `9/12`.
- Thay đổi hiệu quả nhất: làm rõ boundary trong `system_prompt.md` và schema/mô tả tool trong `tools.yaml`.
- Giới hạn còn lại: A04/A10 cho thấy confirmation giả hoặc cũ vẫn có thể kích hoạt create_ticket; H19 còn map `demo` thành staging.
- Cách phân công và tích hợp: làm cá nhân; tự viết, chạy, kiểm tra và ghi evidence.

## INDIVIDUAL

Sao chép mục này cho từng thành viên.

### Hoang Phong — 2A202602943

- Phần việc và file/commit/PR: thực hiện toàn bộ artifact, eval v0-v3, group/adversarial/extension runs, transcript, report và safety review. Commit: TODO.
- Quyết định, khó khăn và cách xử lý: giữ IT Helpdesk; dùng OpenAI `gpt-4o-mini`; cải thiện system prompt trước, sau đó siết tools.yaml; đọc cả tool result và generated ticket thay vì chỉ xem PASS/FAIL.
- Điều đã học: prompt cải thiện routing nhưng write-action boundary cần được kiểm soát bằng state/logic thực thi, không chỉ bằng model instruction.
- AI/công cụ đã dùng và cách kiểm tra: dùng GitHub Copilot/VS Code; kiểm tra bằng preflight, eval runs, JSON/YAML validation, hash/version log và filesystem review.
- Thời điểm đã tự nộp URL repo chung trên VLearn: TODO - điền thời điểm thật.
