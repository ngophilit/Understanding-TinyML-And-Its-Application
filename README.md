<h1 align="center">TIỂU LUẬN CHUYÊN NGÀNH</h1>

<h2 align="center">Đề tài: Tìm hiểu về Tiny Machine Learning và ứng dụng</h2>
<h3>I. Giới thiệu</h3>
<h4>1. Bối cảnh và động lực.</h4>
  a. Bối cảnh.<br>
    - Hiện nay, công nghệ thông tin đang phát triển rất nhanh chóng và mang tính đột phá. Các công nghệ mới như trí tuệ nhân tạo, blockchain, Internet vạn vật, giám sát từ xa, đám mây, và nhiều công nghệ khác đang được áp dụng rộng rãi trong các lĩnh vực khác nhau, từ kinh doanh đến giáo dục, y tế và nhiều lĩnh vực khác. Các ứng dụng di động và các ứng dụng web cũng đang phát triển mạnh mẽ và đã trở thành một phần không thể thiếu của cuộc sống hàng ngày của chúng ta. Trong tương lai gần, chúng ta sẽ chứng kiến sự phát triển của thế giới thông minh, khoa học dữ liệu, và nhiều ứng dụng công nghệ thông tin tối ưu hơn cho các ngành công nghiệp và đời sống cá nhân.<br>
  b. Động lực.<br>
    - Với sự phát triển và ứng dụng mạnh mẽ của trí tuệ nhân tạo (AI) thì các ứng dụng AI là thứ không thể thiếu trong đời sống hằng ngày của chúng ta. Nhưng các giải pháp AI đòi hỏi sức mạnh tính toán lớn và kết nối internet. Từ đó sinh ra bài toán làm thế nào để triển khai các ứng dụng trí tuệ nhân tạo (AI) trực tiếp trên các thiết bị nhỏ như các thiết bị IoT, cảm biến, thiết bị y tế, hệ thống bảo mật và nhiều ứng dụng khác mà không cần kết nối internet. Và để giải quyết bài toán này thì một thuật ngữ được gọi là Tiny Machine Clearning được ra đời.
    - Với TinyML, các thiết bị có thể tự động học hỏi và đưa ra quyết định trên chính nó một cách hiệu quả và tiết kiệm năng lượng. Điều này mở ra nhiều cơ hội mới cho các ứng dụng IoT và trí tuệ nhân tạo.
    
<h4>2. Mục tiêu và phạm vi.</h4>


Tiny machine learning là một phương pháp nhúng các mô hình machine learning vào các thiết bị nhỏ và thiết bị cầm tay, như các cảm biến và thiết bị IoT, mà không cần kết nối mạng hoặc phần cứng mạnh mẽ. Tiny machine learning đang được phát triển để giúp các thiết bị này trở nên thông minh hơn và có thể tự động hóa các quyết định và tương tác với người dùng một cách tự động. Các công nghệ tiny machine learning hiện đang được nghiên cứu và phát triển bởi nhiều hãng công nghệ hàng đầu như Google và Arm.

Quy trình:
1/ Bài toán: phân biệt chó mèo.

2/ Data: bộ dữ liệu có gán nhãn về chó và mèo

3/ Xây dựng mô hình: sử dụng thư viện keras
  - Thư viện Keras.
  - Các lớp(Conv2D, MaxPooling2D, Flatten, Dense,..) và thuật toán( activation = "relu" ? sigmoid ? ,thuật toán tối ưu "adam"..)
  
4/Sử dụng trên Tiny ML
