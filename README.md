# stackoverflow-data-analysis
# Stack Overflow Developer Salary & Experience Analysis

## 📊 Mô tả dự án
Dự án này sử dụng dữ liệu từ khảo sát hàng năm của Stack Overflow để phân tích các yếu tố ảnh hưởng đến mức lương và trải nghiệm làm việc của lập trình viên. Mục tiêu là rút ra những hiểu biết hữu ích cho cả người tìm việc và nhà tuyển dụng trong ngành công nghệ.

## 📁 Dữ liệu
Nguồn dữ liệu: [Stack Overflow Developer Survey 2024](https://survey.stackoverflow.co/)

Tệp sử dụng:
- `survey_results_public.csv`: Dữ liệu gốc từ Stack Overflow
- `filtered_survey_subset.csv`: Dữ liệu đã làm sạch, lọc những cột và dòng cần thiết cho phân tích

## ❓ Câu hỏi nghiên cứu
1. Những công ty hoặc quy mô tổ chức nào trả lương cao nhất cho lập trình viên?
2. Làm việc từ xa ảnh hưởng như thế nào đến mức độ hài lòng trong công việc?
3. Số năm kinh nghiệm lập trình ảnh hưởng ra sao đến mức lương?
4. Cách học lập trình phổ biến nhất là gì?
5. Liệu bằng cấp (ví dụ: thạc sĩ) có giúp dễ kiếm việc làm hơn không?

## 🛠️ Công cụ sử dụng
- Python (pandas, matplotlib, seaborn)
- Jupyter Notebook
- Excel (cho bước xử lý hoặc kiểm tra nhanh dữ liệu)

## 📈 Một số phân tích chính
- **Quy mô tổ chức và lương:** Công ty càng lớn, mức lương trung bình càng cao.
- **Làm việc từ xa:** Người làm việc từ xa có mức độ hài lòng cao hơn.
- **Kinh nghiệm và lương:** Lương tăng mạnh trong 10 năm đầu đi làm.
- **Bằng cấp:** Có thể phân tích so sánh tỷ lệ có việc làm theo trình độ học vấn.

## 🧼 Xử lý dữ liệu
- Loại bỏ giá trị thiếu (`NaN`)
- Chuẩn hóa cột `YearsCodePro` và `EdLevel`
- Lọc các trường cần thiết để giảm kích thước dữ liệu


