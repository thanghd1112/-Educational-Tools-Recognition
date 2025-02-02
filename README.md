# Educational-Tools-Recognition

## Project Overview

This project focuses on the recognition and classification of educational tools using image processing techniques. We experimented with various machine learning models such as MLP, CNN, VGG16, and ResNet50, including transfer learning approaches. Additionally, an image segmentation model was built using the UNet architecture, and all models were deployed using Streamlit.

## Main Responsibilities

Collecting and labeling image data.
Experimenting with image classification models (MLP, CNN, VGG16, ResNet50) and transfer learning (VGG16, ResNet50).
Building an image segmentation model using the UNet architecture.
Deploying models with Streamlit.

## Recognition and Gains

Acquired skills in image data collection, processing, and labeling.
Gained a deeper understanding of MLP, CNN, VGG16, ResNet50, and UNet models.
Applied techniques to improve model performance.
Developed problem-solving and teamwork skills throughout the project.


### HƯỚNG DẪN CÀI ĐẶT VÀ CÁC CHÚ Ý LIÊN QUAN ####

1. Vì số lượng hình ảnh khá nhiều nên các file mô hình khi training trên google colab để vừa đủ tài nguyên và đã gộp lại thành 1 file code nên khi chạy chú ý chạy từng mô hình một.

    -1.1. Các mô hình transfer learning có thể bị trùng tên với mô hình tự xây dựng cho nên vui lòng sau khi chạy xong các mô hình tự xây
    dựng thì hãy reset kernel chạy lại từ đầu với data và mô hình transfer learning.
    -1.2. File tổng hợp được chạy trên Jupyter Notebook trên nền tảng Anaconda. Vui lòng điều chỉnh cho phù hợp khi chuyển đổi môi trường
    chạy.
    
2. Đối với streamlit để hỗ trợ xây dựng web thì cần đảm bảo như sau:

    -2.1. Đảm bảo file xây dựng code web được lưu dưới dạng .py của python. (Như mình là Segmentation.py và Webapp.py trong đó: Segmentation.py là chứa
    giao diện web của Segmenttation còn Webapp.py là classifi của các model huấn luyện khác.)
    -2.2. Đảm bảo môi trường chạy phải cung cấp đầy đủ các thư viện liên quan đến mô hình và web.
    -2.3. Mở terminal -> chuyển đến nơi lưu file code web bằng lệnh sau [cd "đường dẫn thư mục chứa file code"] ->sau đó nhập lệnh
    [streamlit run 'tên file code.py'].
    *Lưu ý: Phải đảm bảo môi trường đầy đủ các thư viện. Ví dụ ở đây mình sử dụng Anaconda với môi trường chạy là my_env nơi cài đặt đủ thư
    viện cho nên ở bước terminal mình sẽ chạy thêm lệnh [conda activate my_env] để kích hoạt môi trường.

3. Đối với file code U-net Segmentation.ypnb thì dữ liệu train là file Data-2 với các file liên quan nằm trong đó.
