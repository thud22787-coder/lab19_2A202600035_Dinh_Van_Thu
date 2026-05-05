# AI VC Critique Log — ContractAI

---

## PITCH GỐC (trước critique)

### Pitch Memo gốc

**THE PROBLEM:** Fresher và mid-level tech worker tại Việt Nam thường ký hợp đồng từ công ty nước ngoài mà không hiểu các điều khoản IP assignment, non-compete và ESOP. Luật sư quá đắt và chậm. Không có công cụ phù hợp.

**THE INSIGHT:** Người dùng cần AI đọc hợp đồng của họ theo luật lao động Việt Nam.

**THE SOLUTION:** ContractAI là chatbot AI upload file hợp đồng, phân tích điều khoản rủi ro, giải thích bằng tiếng Việt. Không cần đăng ký. Dùng Claude Sonnet + RAG với BLLĐ 2019 + vector database pattern library.

**WHY NOW:** LLM đang phát triển mạnh, chi phí API giảm, nhu cầu tăng.

**TRACTION:** Pilot 15 user, kết quả tốt. Margin cao vì API rẻ.

**THE ASK:** Gọi 300M VND để build sản phẩm và có thêm user.

---

### Twitter Pitch gốc

ContractAI giúp tech worker VN đọc hợp đồng nước ngoài bằng AI. Upload file, nhận phân tích điều khoản rủi ro theo luật VN trong 5 phút. Pilot 15 user thành công. Margin cao. Đang gọi 300M VND seed để mở rộng.

---

## AI VC CRITIQUE — Full Feedback

**Prompt dùng:** AI VC Critique Prompt (Sequoia Partner, tired & skeptical)

---

### Phản hồi của AI VC

**Tôi là Partner tại Sequoia. Tôi vừa nghe 50 pitch về "AI disrupt X" tuần này. Đây là đánh giá thẳng thắn:**

---

**1. THE 8-SECOND TEST — FAIL**

Câu đầu "Fresher và mid-level tech worker tại Việt Nam thường ký hợp đồng từ công ty nước ngoài mà không hiểu các điều khoản" — **tôi đã ngủ gật ở chữ "thường"**.

Tại sao fail: không có số, không có khoảnh khắc cụ thể, không có gì bất ngờ. Mọi legal-tech pitch đều mở bằng "người ta không hiểu pháp lý."

Cần: Một con số gây shock hoặc một khoảnh khắc cụ thể khiến tôi thấy pain thật. Ví dụ: "Mỗi tuần tại ITviec, 3.000 tech worker VN nhận offer — và 90% ký trong 48 tiếng mà không biết điều khoản IP ràng buộc side project của họ." Tôi sẽ ngồi thẳng lên.

---

**2. THE INSIGHT TEST — WEAK**

"Người dùng cần AI đọc hợp đồng theo luật lao động Việt Nam" — **đây không phải insight, đây là mô tả sản phẩm.**

Insight thật phải là điều phản trực giác. Câu hỏi tôi sẽ hỏi: *Tại sao ChatGPT chưa giải quyết được? Tại sao luật sư chưa build app này?* Pitch gốc không trả lời được.

Insight thực sự của bạn — mà bạn chưa viết ra — là: **người dùng không cần "tư vấn pháp lý", họ chỉ cần "câu hỏi đúng để hỏi HR"**. Đây là gap khác hẳn. ChatGPT không biết đây là gap vì nó không embed vào khoảnh khắc ra quyết định. Luật sư không build vì họ bán "kết luận pháp lý", không bán "câu hỏi cho HR."

---

**3. THE OPENAI THREAT — KHÔNG CÓ CÂU TRẢ LỜI**

Pitch gốc hoàn toàn không đề cập moat. Nếu tôi hỏi "OpenAI ra tính năng review HĐ tuần sau, bạn làm gì?" — pitch này chết ngay.

ChatGPT đã review được HĐ ở mức cơ bản. Tại sao tôi invest bạn chứ không chờ OpenAI làm tốt hơn?

Câu trả lời bạn cần nhưng chưa nói: (1) Distribution moat — nhúng vào ITviec/TopDev đúng khoảnh khắc offer, OpenAI không có kênh này; (2) Data moat — pattern library từ HĐ công ty nước ngoài tại VN mà OpenAI không có. Hai lớp moat này có trong Day 16 submission của bạn nhưng không vào pitch.

---

**4. THE NUMBERS TEST — THIẾU VÀ MƠ HỒ**

"Pilot 15 user thành công" — **"thành công" là gì?** Tôi sẽ push back ngay câu này.

"Margin cao" — **bao nhiêu?**

Bạn CÓ số cụ thể (87%, 53%, 3k VNĐ, 97% margin) — tại sao không đưa vào pitch? Đây là sai lầm nghiêm trọng nhất. Bạn đang giấu vũ khí mạnh nhất của mình.

---

**5. THE WEAKEST LINE**

> *"LLM đang phát triển mạnh, chi phí API giảm, nhu cầu tăng."*

**Đây là câu tệ nhất trong pitch.** Mọi AI startup năm 2024 đều có thể nói câu này. Nó không nói gì về bạn, không nói gì về timing thực sự của cơ hội.

**Rewrite gợi ý:**
> "Sau 2022, số công ty nước ngoài tuyển trực tiếp tại VN tăng mạnh theo dữ liệu ITviec — trong khi chi phí API giờ là 3.000 đồng/hợp đồng. Timing này tồn tại trong 18–24 tháng trước khi Big Tech nhảy vào."

Câu mới: cụ thể, có số, có urgency, có competitive window.

---

## QUYẾT ĐỊNH ACCEPT / REJECT / PARTIAL

### Point 1 — 8-second test fail

**Quyết định: ACCEPT**

AI đúng — câu mở không có số, không tạo được urgency. Đã viết lại mở bài với số cụ thể (15 user, 87%, 48 tiếng deadline) và khoảnh khắc pain cụ thể thay vì mô tả chung chung.

---

### Point 2 — Insight chưa đủ phản trực giác

**Quyết định: ACCEPT**

AI xác định đúng insight thực sự mà pitch gốc chưa diễn đạt rõ: gap là "câu hỏi đúng để hỏi HR" chứ không phải "hiểu luật". Đã viết lại The Insight section với framing này — cũng là differentiator so với cả luật sư lẫn ChatGPT.

---

### Point 3 — Không có câu trả lời cho OpenAI threat

**Quyết định: ACCEPT**

Moat hoàn toàn vắng mặt trong pitch gốc dù đã được phân tích kỹ trong Day 16 submission (distribution moat ITviec + data moat HĐ VN). Đã thêm 2 lớp moat vào The Solution section và chuẩn bị câu trả lời cho "OpenAI threat" trong pitch final.

---

### Point 4 — Numbers thiếu và mơ hồ

**Quyết định: ACCEPT**

Lỗi rõ ràng — các số cụ thể đã có từ Day 17 (87%, 53%, 3k VNĐ, 97% margin) nhưng không đưa vào pitch. Đã thêm toàn bộ vào Traction section và Twitter Pitch.

---

### Point 5 — "LLM đang phát triển mạnh" là câu tệ nhất

**Quyết định: PARTIAL ACCEPT**

AI đúng rằng câu đó quá generic. Tuy nhiên rewrite của AI ("18–24 tháng trước khi Big Tech nhảy vào") tôi không dùng nguyên văn vì số 18–24 tháng là assumption không có basis. Thay vào đó, viết lại Why Now với 2 lý do cụ thể có data: (1) tăng trưởng tuyển dụng nước ngoài tại VN sau 2022 theo ITviec, (2) API cost đã tới mức gross margin 97% — sustainable từ ngày đầu. Không dùng competitive window estimate không có basis.

---

## PITCH FINAL (sau critique)

### Pitch Memo final

**THE PROBLEM:** Mỗi năm, hàng trăm nghìn fresher và mid-level tech worker tại Việt Nam nhận offer từ công ty nước ngoài và phải ký hợp đồng tiếng Anh chứa điều khoản IP assignment, non-compete, và ESOP phức tạp — trong 2–5 ngày ra quyết định. Luật sư tư giá 200k–500k/giờ và mất 2–3 ngày để có cuộc hẹn. Bạn bè trong ngành có kinh nghiệm nhưng không có nền tảng pháp lý để đọc hợp đồng cụ thể của bạn.

**THE INSIGHT:** Tech worker Việt Nam không cần "tư vấn pháp lý" — họ chỉ cần đủ thông tin để biết câu nào cần hỏi lại HR trước khi ký. Đây là gap mà cả luật sư (quá chậm, đắt) lẫn ChatGPT (không có knowledge base BLLĐ 2019 theo context VN, không embed vào đúng khoảnh khắc ra quyết định) đều không lấp được.

**THE SOLUTION:** ContractAI là chatbot AI đọc file hợp đồng lao động do người dùng upload (PDF/Word, tiếng Anh hoặc song ngữ), phân tích theo khung pháp lý lao động Việt Nam được cấu trúc hóa, và trả về danh sách điều khoản rủi ro được giải thích bằng tiếng Việt thường ngày — trong 5 phút, không cần đăng ký, không lưu file sau session. Differentiator: được nhúng trực tiếp vào ITviec/TopDev ngay trang offer (distribution moat — OpenAI không có kênh này) + domain data flywheel từ 5.000+ HĐ công ty nước ngoài tại VN (data moat — pattern mà OpenAI không có trong training data). AI cụ thể: Claude Sonnet xử lý file song ngữ 10–30 trang, retrieval từ vector database BLLĐ 2019 + 100+ pattern điều khoản phổ biến.

**WHY NOW:** Sau 2022–2023, số công ty nước ngoài tuyển trực tiếp tại Việt Nam tăng mạnh theo dữ liệu tuyển dụng ITviec. Đồng thời, API cost đã xuống mức 3.000 đồng/hợp đồng — đủ để gross margin 97% ngay từ user đầu tiên, không cần scale mới sustainable.

**TRACTION / PROOF:**
- Wizard of Oz MVP (15 user): 87% (13/15) hiểu rõ điều khoản cần hỏi lại HR sau khi nhận kết quả
- Copy-to-action rate: 53% (ngưỡng success đặt ra: 40%) — vượt target ngay tuần đầu
- 3 user đã negotiate được carve-out IP cho side project cá nhân dựa vào kết quả phân tích
- Unit economics: API cost ~3k VNĐ/HĐ | Giá: 99k–149k/lần | Gross margin: 97%

**THE ASK:** Gọi 300M VND seed để: (1) Build AI version thay Wizard of Oz trong 8 tuần, (2) Reach 200 paying user trong 3 tháng, (3) Confirm partnership distribution với ITviec — unlock distribution moat. Target: ThinkZone Ventures, Antler Vietnam.

---

### Twitter Pitch final

Bọn em là ContractAI. Giúp fresher và mid-level tech worker VN hiểu điều khoản IP/non-compete trong HĐ nước ngoài trước khi ký — trong 5 phút, không cần đăng ký. Pilot 15 user: 87% biết đúng câu cần hỏi HR. Copy-to-action 53%. API cost 3k/HĐ, bán 99k → margin 97%. Gọi 300M VND seed để build AI version và reach 200 paying user trong 3 tháng.

---

*Thay đổi lớn nhất giữa gốc và final: (1) Thêm số cụ thể vào mở bài và mọi claim; (2) Viết rõ insight thực sự ("câu hỏi đúng để hỏi HR" chứ không phải "hiểu luật"); (3) Thêm 2 lớp moat vào Solution để defend OpenAI threat; (4) Viết lại Why Now với data thay vì generic statement về AI.*
