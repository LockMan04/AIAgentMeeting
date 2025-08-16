# AI Meeting Assistant - Hệ thống AI Agent chuẩn bị cuộc họp thông minh

## Mô tả dự án

AI Meeting Assistant là một hệ thống multi-agent AI tiên tiến được xây dựng bằng CrewAI, giúp tự động hóa toàn bộ quá trình chuẩn bị và phân tích cuộc họp một cách chuyên nghiệp và hiệu quả.

## Tính năng chính

### **1. Chuẩn bị cuộc họp tự động**
- **Multi-Agent System**: 3 AI agents chuyên biệt làm việc cùng nhau
- **Phân tích bối cảnh**: Tự động nghiên cứu thông tin công ty và ngành
- **Industry Insights**: Cung cấp phân tích xu hướng và cạnh tranh
- **Chiến lược cuộc họp**: Tạo agenda chi tiết và talking points
- **Executive Brief**: Báo cáo tổng hợp cho ban lãnh đạo

### **2. Chat Assistant thông minh**
- **Giao diện chat tự nhiên**: Tương tác bằng ngôn ngữ tự nhiên
- **Parsing thông minh**: Tự động phân tích input phức tạp
- **Validation dữ liệu**: Kiểm tra và yêu cầu bổ sung thông tin thiếu
- **Lịch sử trò chuyện**: Lưu và quản lý các cuộc trò chuyện

### **3. Phân tích transcript cuộc họp**
- **Whisper Integration**: Trích xuất văn bản từ video cuộc họp
- **Action Items Extraction**: Tự động phát hiện nhiệm vụ và cam kết
- **Progress Tracking**: So sánh với kế hoạch đã lưu
- **Meeting Summary**: Tóm tắt toàn diện cuộc họp

### **4. Quản lý liên hệ và email**
- **Google Contacts Integration**: Tích hợp với danh bạ Google
- **Smart Contact Matching**: Tìm người tham gia thông minh
- **Automated Email**: Gửi email mời và báo cáo tự động
- **Department Support**: Hỗ trợ gửi theo phòng ban

### **5. Quản lý dữ liệu**
- **Auto Save**: Tự động lưu báo cáo và lịch sử
- **Export Reports**: Xuất báo cáo dạng Markdown
- **Session Management**: Quản lý phiên làm việc
- **History Browser**: Duyệt lịch sử cuộc họp và trò chuyện

## Kiến trúc hệ thống

### **3 AI Agents chuyên biệt:**

1. **Meeting Preparation Expert**
   - Phân tích bối cảnh cuộc họp
   - Nghiên cứu xu hướng ngành
   - Thiết kế chiến lược và agenda
   - Tạo báo cáo tổng hợp

2. **Smart Assistant**
   - Tương tác với người dùng
   - Phân tích và parse input
   - Tư vấn về kỹ năng họp
   - Quản lý conversation flow

3. **Meeting Analysis Expert**
   - Phân tích transcript cuộc họp
   - Trích xuất action items
   - So sánh tiến độ thực hiện
   - Đánh giá hiệu quả cuộc họp

### **Quy trình xử lý:**
```
User Input → Smart Assistant → [Meeting Prep Expert | Analysis Expert] → Report Generation → Email Distribution
```

## Tính năng nâng cao

### **Dashboard & Analytics**
- Metrics cuộc họp (độ phức tạp, số người tham gia)
- Thống kê lịch sử và báo cáo
- Fun facts về hiệu quả cuộc họp

### **UI/UX Features**
- Giao diện chat hiện đại
- Progress tracking real-time
- Responsive design
- Dark/Light theme support

### **Smart Features**
- Auto-completion cho tên công ty
- Department-based contact matching
- Multi-language transcript support
- Intelligent meeting duration estimation

## Công nghệ sử dụng

| Thành phần | Công nghệ |
|------------|-----------|
| **Frontend** | Streamlit |
| **AI Framework** | CrewAI |
| **LLM** | OpenAI GPT-4o-mini |
| **Search** | SerperDev API |
| **Speech-to-Text** | OpenAI Whisper |
| **Email** | SMTP (Gmail) |
| **Contacts** | Google People API |
| **Data** | JSON, Markdown |

## Roadmap & Future Features

### **Đang phát triển:**
- [ ] Multi-language support
- [ ] Advanced analytics dashboard
- [ ] Calendar integration
- [ ] Mobile app version
- [ ] Voice commands
- [ ] Meeting recording integration

### **Tính năng mong muốn:**
- [ ] Slack/Teams integration
- [ ] AI-powered follow-up suggestions
- [ ] Meeting effectiveness scoring
- [ ] Custom agent training
- [ ] Enterprise SSO support

## Acknowledgments

- [CrewAI](https://github.com/joaomdmoura/crewai) - Multi-agent framework
- [Streamlit](https://streamlit.io/) - Web app framework
- [OpenAI](https://openai.com/) - GPT models
- [Google](https://developers.google.com/) - Contacts API

---
