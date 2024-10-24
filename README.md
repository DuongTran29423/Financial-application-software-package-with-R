Video Demo: https://github.com/DuongTran29423/Financial-application-software-package-with-R/blob/master/D__R%20-%20Shiny%202024-10-24%2021-33-47.mp4
# ISAPS - Intelligent Stock Analysis and Prediction System

## 📊 Giới thiệu

**ISAPS** (Intelligent Stock Analysis and Prediction System) là một ứng dụng web được phát triển bằng R Shiny giúp người dùng thực hiện các phân tích tài chính và dự báo về cổ phiếu. Ứng dụng cung cấp các tính năng như phân tích chỉ số chứng khoán, dự báo giá cổ phiếu dựa trên các mô hình như ARIMA và DNN, và trực quan hóa dữ liệu tài chính.

## 🧑‍💻 Các tính năng chính

- **Phân tích định lượng cổ phiếu**: Bao gồm tính toán các chỉ số và mối tương quan giữa các cổ phiếu trong cùng ngành.
- **Biểu đồ chỉ số**: Vẽ các chỉ số như SMA, MACD, Bollinger Bands, và RSI.
- **Mô hình dự đoán**: Dự báo xu hướng giá cổ phiếu sử dụng mô hình ARIMA và DNN (Mạng nơ-ron sâu).
- **Mô hình CAPM**: Đánh giá và phân tích rủi ro và lợi nhuận của danh mục đầu tư theo mô hình CAPM.
- **Phân tích tài chính**: Hiển thị các chỉ số tài chính như Tổng tài sản hiện hành, Lợi nhuận gộp, Doanh thu, và dòng tiền.

## 📂 Cấu trúc tệp tin

- **app.R**: File chính chứa mã nguồn của ứng dụng Shiny.
- **merged.xlsx**: Dữ liệu tổng hợp các loại cổ phiếu.
- **Financial_Reports_20192023.xlsx**: Dữ liệu báo cáo tài chính của các công ty từ 2019 đến 2023.
- **F-F_Research_Data_Factors.csv**: Dữ liệu yếu tố Fama-French sử dụng cho mô hình CAPM.
- **webnha-4-Final.r**: File mã nguồn bổ sung cho phân tích nâng cao.
- **D__R - Shiny 2024-10-24 21-33-47.mp4**: Video demo giới thiệu các tính năng của ứng dụng.

## 🚀 Hướng dẫn cài đặt

### 1. Cài đặt các gói R cần thiết
Bạn cần cài đặt các gói R sử dụng trong ứng dụng nếu chưa có:
```r
install.packages(c("shiny", "shinydashboard", "shinyWidgets", "readxl", "readr", "quantmod", 
                   "dygraphs", "dplyr", "DT", "TTR", "plotly", "xts", "lubridate", "stringr", 
                   "corrplot", "prophet", "tidyr", "tibble", "reshape2", "jsonlite", "treemap", 
                   "scales", "timetk", "tidyquant", "forecast", "forcats", "tidyverse", "keras"))
