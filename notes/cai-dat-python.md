## Giới thiệu
Trước hết, ta cần phải cài đặt môi trường để làm việc với Python. Python là một ngôn ngữ lập trình mã nguồn mở, hướng đối tượng và đa nền tảng và rất súc tích (so với các đối thủ cạnh tranh trực tiếp như C++ và Java). Nó cho phép xây dựng một sản phẩm rất nhanh 

## Python 2 hay 3?

Hiện tại, Python đang được chia thành hai nhánh: Python 2 và Python 3. Mặc dù phiên bản 3 mới hơn nhưng phiên bản 2 vẫn được sử dụng phổ biến trong khoa học do một số thư viện chưa hỗ trợ trên phiên bản 3 và không có sự tương thích ngược giữa phiên bản 3 và phiên bản 2.

## Cài đặt

Sau đây là các bước cài đặt Python lên máy tính:

- Đầu tiên, tải bộ cài Python tại [https://www.python.org/downloads/](https://www.python.org/downloads/)


## Một số gói thư viện phổ biến trong Python

### NumPy

Được tạo bởi Travis Oliphant, **NumPy** là một "ngựa kéo" phân tích thực sự của Python. Nó cung cấp cho người dùng cách làm việc với các mảng nhiều chiều, cùng một số lượng lớn các hàm để xử lý trên các toán tử toán học nhiều chiều trên các mảng đó. Mảng là các khối dữ liệu được sắp xếp theo nhiều chiều dựa trên các véc tơ và ma trận trong toán học. Mảng thường hữu ích không chỉ trong việc lưu dữ liệu mà cả việc tính toán nhanh các ma trận, điều không thể thiếu khi giải quyết các vấn đề liên quan đến khoa học dữ liệu.

- Cài đặt: ```pip install numpy```
- Trang chủ: [http://www.numpy.org](http://www.numpy.org)

### SciPy

Là một dự án gốc bởi Travis Oliphant, Pearu Peterson, and Eric Jones, SciPy hoàn thiện các tính năng của NumPy, nhằm cung cấp các thuật toán cho đại số tuyến tính, không gian ma trận, xử lý tín hiệu và xử lý ảnh, tối ưu, biến đổi Fourier,...

- Cài đặt: ```pip install scipy```
- Trang chủ: [http://www.scipy.org](http://www.scipy.org)

### pandas

**pandas** là thư viện thực hiện mọi thứ mà **NymPy** và **SciPy** không thể làm. Nó làm việc với các đối tượng cấu trúc dữ liệu, DataFrames và Chuỗi (Series). pandas cho phép bạn có thể xử lý các bảng dữ liệu phức tạp của nhiều loại khác nhau (điều mà các mảng của NumPy thông thể làm được) và chuỗi thời gian. Bạn sẽ dễ dàng tải dữ liệu từ nhiều nguồn khác nhau, sau đó slide, dice, xử lý các thành phần còn thiếu, thêm, đổi tên, tổng hợp (aggregate), reshape và cuối cùng là trực quan dữ liệu theo ý của bạn.

- Cài đặt: ```pip install pandas```
- Trang chủ: [http://pandas.pydata.org](http://pandas.pydata.org)

### Scikit-learn

Bắt đầu như một phần của SciKits, Scikit-learn là lõi hoạt động của khoa học dữ liệu trên Python. Nó cung cấp tất cả những gì bạn cần để tiền xử lý dữ liệu, học giám sát và không giám sát, lựa chọn mô hình, validate và error metrics. 


- Cài đặt: ```pip install scikit-learn```
- Trang chủ: [http://scikit-learn.org/stable](http://scikit-learn.org/stable)

### IPython

Một cách tiếp cận khoa học yêu cầu thử nghiệm nhanh các giả thuyết khác nhau trong một khoảng thời gian. IPython được tạo bởi Fernando Perez để giải quyết việc cần thiết một lệnh Shell Python (dựa trên shell, trình duyệt web, và giao diện ứng dụng) với đồ họa tích hợp, các lệnh có thể tùy chỉnh, lịch sử phong phú (dưới định dạng JSON) và khả năng tính toán song song để cải thiện hiểu năng tính toán.

- Cài đặt: ```pip install "ipython[notebook]"```
- Trang chủ: [http://ipython.org](http://ipython.org)

### Matplotlib

Được phát triển bởi John Hunte, matplotlib là một thư viện xây dựng các khối cần thiết để tạo các biểu đồ chất lượng từ mảng và trực quan và tương tác với chúng.

- Cài đặt: ```pip install matplotlib```
- Trang chủ: [http://matplotlib.org](http://matplotlib.org)

### Statsmodels

Trước đây là một phần của SciKits, Statsmodels bổ sung các tính năng thống kê cho SciPy. Nó bao gồm các mô hình tuyến tính tổng quát (generalized linear models), mô hình lựa chọn rời rạc (discrete choice models), phân tích chuỗi thời gian (time series analysis) và một chuỗi các thống kê mô tả như kiểm định tham số và kiểm định phi tham số (parametric and
nonparametric tests).

- Cài đặt: ```pip install statsmodels```
- Trang chủ: [http://statsmodels.sourceforge.net](http://statsmodels.sourceforge.net)

### Beautiful Soup

Beautiful Soup, a creation of Leonard Richardson, is a great tool to scrap out data
from HTML and XML files retrieved from the Internet. It works incredibly well,
even in the case of tag soups (hence the name), which are collections of malformed,
contradictory, and incorrect tags. After choosing your parser (basically, the HTML
parser included in Python's standard library works fine), thanks to Beautiful Soup,
you can navigate through the objects in the page and extract text, tables, and any
other information that you may find useful.

### NetworkX

NetworkX, được phát triển bởi Los Alamos National Laborator, là một gói thư viện chuyên về tạo, thao tác, phân tích và trình diễn đồ họa dữ liệu mạng thực tế. Nó có thể hoạt động một cách dễ dàng với đồ thị được tạo bởi hàng triệu nút (nodes) và cạnh (edges). Bên cạnh các cấu trúc chuyên biệt cho đồ thị và các phương thức trực quan hóa tiêu chuẩn như 2D hay 3D, nó còn cung cấp nhiều giải pháp đồ thị chẩn và các thuật toán như shortest path, centrality, components, communities, clustering, và PageRank.

- Cài đặt: ```pip install networkx```
- Trang chủ: [https://networkx.github.io](https://networkx.github.io)

### NLTK
