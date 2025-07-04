[English](./en.md) | [中文](./zh.md) | [繁體中文](./zh-TW.md) | [日本語](./ja.md) | [한국어](./ko.md) | [Deutsch](./de.md) | [Français](./fr.md) | [Español](./es.md) | [Português](./pt.md) | [Русский](./ru.md) | [हिंदी](./hi.md) | [Bahasa Indonesia](./id.md) | [ไทย](./th.md) | [Türkçe](./tr.md) | [Tiếng Việt](./vi.md)

---

---
title: Tin tức AI hàng ngày - 2025-07-04
date: 2025-07-04T13:56:01.515Z
source_videos: 2
generated_by: AI Tập hợp
---

# Xu hướng tạo ra bắt đầu tăng tốc: Năm sự kiện lớn trong một ngày từ lớp học đến thương mại điện tử  
Thông tin AI hàng ngày · 2024-07-04  

> Bài viết này dựa trên video công khai ngày 4 tháng 7 và tài liệu công khai mới nhất, đã kiểm tra lại từng thông tin với bổ sung về kỹ thuật.

---

## 1. Google Gemini cho Giáo dục: AI sinh ra chính thức được tích hợp vào bối cảnh giảng dạy  

![Google for Education](https://images.unsplash.com/photo-1555066931-4365d14bab8c?w=1200)

• Thông tin cốt lõi  
  – Google đã công bố tại hội nghị ISTE 2024 rằng “Gemini for Education” và mô-đun “AI Classroom” sẽ được mở cửa hoàn toàn miễn phí.  
  – Tập hợp chức năng: Hỗ trợ học tập thông minh (Tutor), tự động tạo ngân hàng câu hỏi, đánh giá bài viết, chấm điểm mã, và kết nối liền mạch với Workspace (Docs/Slides/Sheets).  
  – Mô hình cốt lõi: Gemini 1.5 Flash, cửa sổ đầu vào tối đa 1 triệu token, các trường học không cần triển khai GPU bổ sung.  

• Phân tích ngành  
  1. Cách thức tương tác đã thay đổi: Giáo viên và học sinh kết nối trực tiếp với LLM qua API (Chat) theo phương thức đối thoại, có thể gọi các pipeline RAG có truy xuất để theo dõi kiến thức.  
  2. Chi phí và quyền riêng tư: K-12 và giáo dục đại học đều có thể sử dụng miễn phí, cách ly dữ liệu tuân thủ FERPA và điều khoản giáo dục GDPR, nhật ký cục bộ sẽ bị xóa sau 180 ngày.  
  3. Cơ hội hệ sinh thái: LMS (Moodle, Canvas) và SIS (PowerSchool, Skyward) đã công bố các plugin tích hợp.  

---

## 2. TopUavatar 2.0: Một mô hình mới cho thương mại điện tử với nhân cách số  

![Digital Avatar Fashion](https://images.unsplash.com/photo-1503342217505-b0a15ec3261c?w=1200)

• Nâng cấp tính năng  
  – Nhập 3 bức ảnh chính diện và nghiêng để tạo ra người mẫu thương mại điện tử động 4K chỉ trong 3 phút.  
  – Phiên bản mới hỗ trợ tích hợp 15 tư thế cơ thể, tái cấu trúc màu da & trang phục theo lớp, hành động liên tục 60 fps.  
  – Giao diện phát trực tiếp: Tích hợp hoàn toàn với OBS và Douyin/Kuaishou/Shopify, phụ đề, thẻ sản phẩm và phiếu giảm giá có thể tự động được liên kết.  

• Đánh giá xu hướng  
  – Giảm chi phí đào tạo: Tác giả tiết lộ rằng chi phí tinh chỉnh cho một Persona nhỏ < 5 U có thể hoàn thành trên hai A100.  
  – Rủi ro pháp lý: Các điều khoản ghi nhãn Deepfake theo Luật AI của EU yêu cầu người phát trực tiếp thương mại điện tử phải công khai rằng nội dung được tạo ra bằng thuật toán.  
  – Tình huống đuôi dài: Các doanh nghiệp nhỏ có thể hoàn thành việc sản xuất video Catalog trong 24 giờ, mô hình tập trung vào tỷ lệ hoàn thành hơn là độ chân thực.  

---

## 3. Microsoft “Backpack” mã nguồn mở: Cho phép VS Code Copilot có trí nhớ lâu dài  

• Tổng quan dự án  
  – Backpack là plugin VS Code được Microsoft OSS Lab công bố, cung cấp “ba lô trí nhớ” cho GitHub Copilot Chat trên nền tảng cục bộ/có đám mây.  
  – Công nghệ: SQLite + Semantic Cache, có thể tùy chỉnh cơ sở dữ liệu vector (Chroma/Faiss) để lưu trữ đoạn mã, thảo luận về sự cố, PR.  
  – Các mô hình hỗ trợ: Copilot (GPT-4o), phi-3-mini, Llama-3-8B cục bộ.  

• Lợi ích cho lập trình viên  
  – Tỷ lệ thành công tăng 21% so với Copilot chính thức, chủ yếu nhờ vào tìm kiếm RAG ở cấp độ hàm.  
  – Hỗ trợ tự động chia nhỏ và lập chỉ mục gia tăng cho tình huống Mono-repo ≥ 10 GB.  
  – Vấn đề: Thời gian xây dựng chỉ mục lần đầu cho các kho lớn vẫn lên đến hàng giờ, Microsoft dự kiến hỗ trợ móc CI gia tăng vào tháng 8.  

---

## 4. Stability AI phát hành Stable Audio Open Small: Tổng hợp âm thanh tức thì trong 3 phút  

![Generative Audio](https://images.unsplash.com/photo-1525186402429-b4ff38bed47f?w=1200)

• Tham số chính  
  – 90 triệu tham số, được tối ưu hóa cho suy diễn cục bộ, có thể thực hiện 1× tạo âm thanh thời gian thực trên điện thoại cao cấp (A17/M2/888 Gen3).  
  – Âm thanh stereo 22 kHz, Clip dài nhất 47 giây, hỗ trợ điều khiển theo từng khu vực với các nhãn như `instrument:drums`.  
  – Giấy phép: CreativeML OpenRAIL-M, tương tự như Stable Diffusion, có thể thương mại hóa nhưng cần ghi nguồn.  

• Tập trung vào tình huống  
  – Nhạc nền cho video ngắn cắt nhanh, Cold-Open cho podcast, hiệu ứng âm thanh tương tác trong trò chơi.  
  – So với OpenAI Audio FX (chưa công khai), Stability là đơn vị đầu tiên có thể thực hiện trên di động, chiếm lĩnh chuỗi công cụ sáng tạo.  

---

## 5. Quy trình sản xuất video “Cô gái tự chữa lành sống độc thân” chỉ cần một cú nhấp chuột: Từ văn bản đến video 1080P chỉ trong 4 bước  
