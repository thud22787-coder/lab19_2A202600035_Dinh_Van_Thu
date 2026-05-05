# PITCH MEMO — ContractAI

**Audience:** Seed VC — ThinkZone Ventures / Antler Vietnam

---

## 1. THE PROBLEM

Mỗi năm, hàng trăm nghìn fresher và mid-level tech worker tại Việt Nam nhận offer từ công ty nước ngoài và phải ký hợp đồng tiếng Anh chứa điều khoản IP assignment, non-compete, và ESOP phức tạp — trong 2–5 ngày ra quyết định. Luật sư tư giá 200k–500k/giờ và mất 2–3 ngày để có cuộc hẹn — quá chậm và đắt cho một deadline như vậy. Bạn bè trong ngành có kinh nghiệm nhưng không có nền tảng pháp lý để đọc hợp đồng cụ thể của bạn.

---

## 2. THE INSIGHT

Tech worker Việt Nam không cần "tư vấn pháp lý" — họ chỉ cần **đủ thông tin để biết câu nào cần hỏi lại HR trước khi ký**. Đây là gap mà cả luật sư (quá chậm, đắt) lẫn ChatGPT (không có knowledge base BLLĐ 2019 theo context VN, không embed vào đúng khoảnh khắc ra quyết định) đều không lấp được.

---

## 3. THE SOLUTION

ContractAI là chatbot AI đọc file hợp đồng lao động do người dùng upload (PDF/Word, tiếng Anh hoặc song ngữ), phân tích theo khung pháp lý lao động Việt Nam được cấu trúc hóa, và trả về danh sách điều khoản rủi ro được giải thích bằng tiếng Việt thường ngày — trong 5 phút, không cần đăng ký tài khoản, không lưu file sau session.

**Differentiator so với ChatGPT:** Không phải "một AI khác" — ContractAI được nhúng trực tiếp vào ITviec/TopDev ngay trang offer (distribution moat: tiếp cận user đúng khoảnh khắc ra quyết định, không phải sau khi đã ký), kết hợp domain data flywheel từ 5.000+ HĐ công ty nước ngoài tại VN mà OpenAI không có trong training data.

**AI giúp cụ thể:** Claude Sonnet xử lý file HĐ 10–30 trang song ngữ, retrieval từ vector database BLLĐ 2019 + pattern library 100+ điều khoản phổ biến, stream kết quả từng điều khoản — chi phí API ~3k VNĐ/HĐ.

---

## 4. WHY NOW

Sau 2022–2023, số công ty nước ngoài tuyển trực tiếp tại Việt Nam tăng mạnh (dữ liệu tuyển dụng ITviec). Đồng thời, LLM đã đủ khả năng xử lý văn bản pháp lý song ngữ với chi phí đủ thấp để sustainable: API cost ~3k VNĐ/HĐ, giá bán 99k–149k/lần → gross margin 97% ngay từ user đầu tiên.

---

## 5. TRACTION / PROOF

- **Wizard of Oz MVP (15 user):** 87% (13/15) hiểu rõ điều khoản cần hỏi lại HR sau khi nhận kết quả — đạt Aha Moment
- **Copy-to-action rate: 53%** (ngưỡng success đặt ra: 40%) — vượt target ngay tuần đầu
- **3 user** đã negotiate được carve-out IP cho side project cá nhân dựa vào kết quả phân tích
- **Unit economics:** API cost ~3k VNĐ/HĐ | Giá: 99k–149k/lần | Gross margin: 97%
- **Return rate D30:** đang đo — dự kiến có data sau 6 tuần với 200 user
- **Rủi ro đã xác định & có plan:** legal positioning ("công cụ giáo dục pháp luật" vs "tư vấn pháp lý") cần tham vấn luật sư trước launch công khai; partnership ITviec/TopDev chưa confirm — là ưu tiên dùng vốn seed

---

## 6. THE ASK

Gọi **300M VND seed** để:
1. Build AI version thay Wizard of Oz trong 8 tuần
2. Reach 200 paying user trong 3 tháng (validate willingness to pay thực sự)
3. Confirm partnership distribution với ITviec — unlock distribution moat

**Target investors:** ThinkZone Ventures, Antler Vietnam, Do Ventures
