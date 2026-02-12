# 🎓 Hướng Dẫn Sử Dụng Website Học Tiếng Trung

## 📋 Mục Lục
1. [Bắt Đầu Nhanh](#bắt-đầu-nhanh)
2. [Cấu Trúc Website](#cấu-trúc-website)
3. [Lộ Trình Học Đề Xuất](#lộ-trình-học-đề-xuất)
4. [Tính Năng](#tính-năng)
5. [Tips Học Hiệu Quả](#tips-học-hiệu-quả)

## 🚀 Bắt Đầu Nhanh

### Cách 1: Mở trực tiếp (Offline)
1. Download toàn bộ thư mục `public/`
2. Mở file `public/index.html` bằng trình duyệt (Chrome, Firefox, Edge, Safari...)
3. Bắt đầu học!

### Cách 2: Chạy local server
```bash
cd public
python3 -m http.server 8000
# Mở trình duyệt tại: http://localhost:8000
```

## 📚 Cấu Trúc Website

### Trang Chính
- **index.html** - Trang chủ với tổng quan về các cấp độ HSK và công cụ học tập
- **curriculum.html** - Lộ trình học chi tiết từ HSK 1 đến HSK 4

### Các Cấp Độ HSK
- **hsk1.html** - 150 từ vựng cơ bản (2-3 tuần học)
- **hsk2.html** - 300 từ vựng sơ cấp (3-4 tháng)
- **hsk3.html** - 600 từ vựng trung cấp (4-6 tháng)
- **hsk4.html** - 600 từ vựng nâng cao (6-8 tháng)

### Công Cụ Học Tập
- **Pinyin.html** - Học phát âm tiếng Trung (21 thanh mẫu + 38 vận mẫu)
- **BoThuChuHan.html** - Học 214 bộ thủ và thứ tự nét viết
- **Flashcards.html** - Thẻ ghi nhớ từ vựng với hệ thống SRS
- **grammar.html** - Bài học ngữ pháp từ cơ bản đến nâng cao
- **Practice.html** - Dashboard theo dõi tiến độ học tập

### Dữ Liệu
- **data/hsk1_vocab.json** - 30 từ vựng HSK 1 mẫu
- **data/hsk2_vocab.json** - 10 từ vựng HSK 2 mẫu
- **data/hsk3_vocab.json** - 10 từ vựng HSK 3 mẫu
- **data/hsk4_vocab.json** - 10 từ vựng HSK 4 mẫu
- **data/grammar_lessons.json** - 10 bài học ngữ pháp

## 🎯 Lộ Trình Học Đề Xuất

### Tuần 1-2: Nền Tảng Phát Âm
1. Mở **Pinyin.html**
2. Học 21 thanh mẫu (5-10 âm/ngày)
3. Học 38 vận mẫu (5-10 âm/ngày)
4. Luyện 4 dấu thanh
5. **Mục tiêu:** Phát âm chính xác mọi từ tiếng Trung

### Tuần 2-4: Bộ Thủ Cơ Bản
1. Mở **BoThuChuHan.html**
2. Học 5-10 bộ thủ/ngày
3. Luyện viết thứ tự nét
4. **Mục tiêu:** Biết 50-100 bộ thủ thông dụng

### Tuần 3-8: HSK 1 (150 từ)
1. Mở **hsk1.html**
2. Học 10-15 từ/ngày
3. Sử dụng **Flashcards.html** để ôn tập
4. Học ngữ pháp HSK 1 ở **grammar.html**
5. **Mục tiêu:** Giao tiếp cơ bản, đếm số, giới thiệu bản thân

### Tháng 3-6: HSK 2 (300 từ)
1. Mở **hsk2.html**
2. Học 8-10 từ/ngày
3. Ôn HSK 1 mỗi ngày với flashcards
4. Luyện nghe podcast tiếng Trung 15-20 phút/ngày
5. **Mục tiêu:** Giao tiếp hàng ngày - đi chợ, nhà hàng, đường phố

### Tháng 7-12: HSK 3 (600 từ)
1. Mở **hsk3.html**
2. Học 10-12 từ/ngày
3. Đọc văn bản ngắn (100-200 từ)
4. Xem phim tiếng Trung có phụ đề
5. **Mục tiêu:** Diễn đạt phức tạp, thảo luận chủ đề đa dạng

### Tháng 13-18: HSK 4 (600 từ)
1. Mở **hsk4.html**
2. Học 10-12 từ/ngày
3. Đọc báo, bài viết tiếng Trung
4. Viết email, đoạn văn ngắn
5. **Mục tiêu:** Giao tiếp thành thạo, làm việc bằng tiếng Trung

## ✨ Tính Năng

### 1. Học Từ Vựng với Flashcards
- Mỗi từ có: Hán tự, Pinyin, nghĩa tiếng Việt, ví dụ
- Đánh dấu từ đã học
- Tìm kiếm từ vựng
- Lưu tiến độ tự động (LocalStorage)

### 2. Học Ngữ Pháp
- 10 bài ngữ pháp từ HSK 1-3
- Giải thích chi tiết bằng tiếng Việt
- Nhiều ví dụ minh họa
- Lọc theo cấp độ HSK

### 3. Theo Dõi Tiến Độ
- Số từ đã học / tổng số
- Tiến độ từng cấp độ HSK
- Lưu tự động trong trình duyệt

### 4. Responsive Design
- Hoạt động tốt trên điện thoại, tablet, máy tính
- Dark mode tự động theo hệ thống
- Giao diện đẹp, dễ sử dụng

## 💡 Tips Học Hiệu Quả

### 1. Kiên Trì Hàng Ngày
- ✅ Học 30 phút/ngày tốt hơn 3 giờ/tuần
- ✅ Đặt mục tiêu cụ thể: 10 từ mới + ôn 20 từ cũ
- ✅ Học cùng giờ mỗi ngày để tạo thói quen

### 2. Sử Dụng Phương Pháp SRS
- ✅ Ôn từ cũ theo khoảng cách thời gian tăng dần
- ✅ Từ khó ôn thường xuyên hơn
- ✅ Sử dụng Flashcards để ghi nhớ lâu dài

### 3. Luyện Viết Chữ Hán
- ✅ Viết tay mỗi chữ 10-20 lần
- ✅ Nắm vững thứ tự nét (stroke order)
- ✅ Hiểu ý nghĩa của bộ thủ

### 4. Luyện Nghe Nhiều
- ✅ Nghe podcast tiếng Trung 15-20 phút/ngày
- ✅ Xem phim/video có phụ đề
- ✅ Lặp lại những gì nghe được

### 5. Đừng Sợ Sai
- ✅ Sai là phần của quá trình học
- ✅ Thử nói/viết ngay cả khi chưa hoàn hảo
- ✅ Học từ những lỗi sai

## 📖 Tài Nguyên Bổ Sung

### Website Miễn Phí
- [Chinese Grammar Wiki](https://resources.allsetlearning.com/chinese/grammar) - Ngữ pháp chi tiết
- [Arch Chinese](https://www.archchinese.com) - Viết chữ Hán, công cụ Pinyin
- [HSK Online](http://www.hskonline.com) - Danh sách từ vựng HSK đầy đủ

### Ứng Dụng Mobile
- **Pleco** - Từ điển tốt nhất (iOS/Android)
- **HelloChinese** - App học tốt cho người mới (iOS/Android)
- **Anki** - Flashcard SRS (iOS/Android/Desktop)

### YouTube Channels
- ChinesePod
- Learn Chinese with Emma
- Mandarin Corner
- Chinese Zero to Hero

### Podcast
- ChinesePod
- Slow Chinese
- TeaTime Chinese

## 🔧 Mở Rộng & Tùy Chỉnh

### Thêm Từ Vựng Của Bạn
Chỉnh sửa file `data/hsk*_vocab.json`:
```json
{
  "id": 31,
  "hanzi": "学习",
  "pinyin": "xuéxí",
  "vietnamese": "Học tập",
  "type": "động từ",
  "example": "我喜欢学习",
  "examplePinyin": "Wǒ xǐhuan xuéxí",
  "exampleVietnamese": "Tôi thích học tập"
}
```

### Thêm Bài Ngữ Pháp
Chỉnh sửa file `data/grammar_lessons.json` theo format có sẵn.

### Tùy Chỉnh Giao Diện
- Các màu sắc được định nghĩa trong Tailwind config
- Có thể thêm CSS tùy chỉnh trong thẻ `<style>`

## ❓ FAQ

**Q: Website có hoạt động offline không?**
A: Có! Sau lần tải đầu tiên, website hoạt động hoàn toàn offline.

**Q: Tiến độ học có được lưu không?**
A: Có, tiến độ được lưu trong LocalStorage của trình duyệt.

**Q: Có thể học trên điện thoại không?**
A: Có! Website responsive, hoạt động tốt trên mọi thiết bị.

**Q: Tài liệu có đầy đủ không?**
A: Hiện tại là bản demo với dữ liệu mẫu. Bạn có thể mở rộng bằng cách thêm vào file JSON.

**Q: Có thể chia sẻ website này không?**
A: Có! Website hoàn toàn miễn phí và mã nguồn mở.

## 🤝 Đóng Góp

Muốn đóng góp thêm từ vựng, ngữ pháp hoặc tính năng?
1. Fork repository
2. Thêm/chỉnh sửa nội dung
3. Tạo Pull Request

## 📝 Ghi Chú

- Website này được xây dựng hoàn toàn bằng HTML/CSS/JavaScript
- Không cần server, database hay backend
- Dữ liệu được lưu trữ trong file JSON
- Miễn phí 100% cho mục đích học tập

---

**Chúc bạn học tiếng Trung thành công!**

**加油！(Jiāyóu - Cố lên!)**

千里之行，始于足下
*Đường đi ngàn dặm bắt đầu từ bước chân đầu tiên*
