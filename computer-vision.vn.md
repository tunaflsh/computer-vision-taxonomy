# Tổng quan
Computer Vision (tầm nhìn máy tính) là một lĩnh vực của trí tuệ nhân tạo (AI) và khoa học máy tính, nghiên cứu về việc làm cho máy tính có khả năng nhìn và hiểu thông qua hình ảnh và video. Mục tiêu chính của Computer Vision là phát triển các thuật toán và công cụ để máy tính có thể hiểu, phân tích và rút trích thông tin từ dữ liệu hình ảnh và video.

Computer Vision giải quyết nhiều vấn đề liên quan đến nhận dạng, nhận diện, phân loại và hiểu nội dung của hình ảnh và video. Các vấn đề chính mà Computer Vision giải quyết bao gồm:

1. Nhận dạng đối tượng (Object recognition): Từ một hình ảnh hoặc video, Computer Vision có khả năng nhận diện và xác định các đối tượng có mặt trong đó, bao gồm con người, động vật, vật thể, phương tiện giao thông, và nhiều hơn nữa.

2. Phân tích hình ảnh và video (Image analysis): Computer Vision có thể phân tích các thuộc tính, đặc trưng và thông tin trong hình ảnh và video, như màu sắc, hình dạng, đường viền, diễn biến thời gian, và sự tương tác giữa các yếu tố.

3. Đo lường và định vị (Measurement and localization): Computer Vision có thể đo lường và định vị vị trí, kích thước, tỉ lệ, và khoảng cách giữa các đối tượng trong hình ảnh và video. Điều này có thể áp dụng trong nhiều ứng dụng, từ nhận dạng khuôn mặt, xử lý ảnh y khoa, định vị GPS cho robot, đến công nghệ tự lái ô tô.

4. Phân loại và nhận diện (Classification and identification): Computer Vision có khả năng phân loại và nhận dạng các đối tượng, biểu đồ, ký hiệu và hình vẽ. Các ứng dụng có thể bao gồm nhận dạng ký tự trong hình ảnh, phân loại sản phẩm trong cửa hàng, hay nhận dạng dấu hiệu giao thông trên đường phố.

5. Phát hiện và theo dõi (Detection and tracking): Computer Vision có thể phát hiện và theo dõi các đối tượng hoặc sự di chuyển trong không gian và thời gian. Điều này có thể được áp dụng trong việc theo dõi vật thể, nhận dạng hành vi, hoặc xác định sự xuất hiện và biến mất của các đối tượng trong video giám sát.

Computer Vision đã tạo ra nhiều ứng dụng thực tế như xe tự lái, nhận dạng khuôn mặt, hệ thống giám sát an ninh, trợ lý ảo và nhiều hơn nữa. Đây là một lĩnh vực rộng lớn và đang phát triển nhanh chóng, đóng góp quan trọng vào sự phát triển của công nghệ và cuộc sống hàng ngày.

## Nhận dạng đối tượng (Object recognition)
là quá trình xác định và phân biệt các đối tượng trong một hình ảnh hoặc video dựa trên đặc trưng và thông tin hình ảnh của chúng. Mục tiêu của object recognition là nhận dạng một đối tượng cụ thể và xác định liệu đối tượng đó có tồn tại trong hình ảnh hay không.

Thuật toán object recognition sử dụng các phương pháp học máy và học sâu để phân tích và so khớp đặc trưng của đối tượng trong hình ảnh. Các đặc trưng này có thể là màu sắc, hình dạng, cạnh, texture, hoặc các đặc trưng phức tạp hơn như mối liên hệ giữa các điểm ảnh trong hình ảnh.

Các bước chính trong quá trình nhận dạng đối tượng bao gồm:

1. Thu thập dữ liệu: Thu thập và xây dựng một tập dữ liệu đủ lớn và đa dạng các hình ảnh chứa đối tượng muốn nhận dạng.

2. Trích xuất đặc trưng: Sử dụng các phương pháp phân tích hình ảnh, thuật toán object recognition trích xuất các đặc trưng hình ảnh từ tập dữ liệu đã thu thập.

3. Xây dựng mô hình: Dữ liệu và đặc trưng được sử dụng để xây dựng mô hình học máy hoặc học sâu. Mô hình này được huấn luyện sử dụng các thuật toán như Support Vector Machines (SVM), Logistic Regression, Convolutional Neural Networks (CNN), hoặc Recurrent Neural Networks (RNN).

4. Kiểm tra và xác định: Mô hình đã được huấn luyện sẽ được áp dụng cho các hình ảnh mới để xác định và nhận dạng đối tượng trong đó. Mô hình so sánh các đặc trưng của hình ảnh mới với các đặc trưng đã học trước đó để xác định đối tượng tương ứng.

Object recognition được áp dụng trong nhiều lĩnh vực, bao gồm nhận dạng khuôn mặt, nhận dạng biển số xe, nhận dạng sản phẩm trong cửa hàng, nhận dạng dấu hiệu giao thông, và nhiều hơn nữa. Đây là một lĩnh vực quan trọng và phát triển trong trí tuệ nhân tạo và ứng dụng thực tế.

## Phát hiện đối tượng (Object detection) 
là quá trình nhận dạng và xác định vị trí và giới hạn của các đối tượng trong một hình ảnh hoặc video. Mục tiêu chính của phát hiện đối tượng là nhận dạng và định vị vị trí của các đối tượng cụ thể trong một hình ảnh và xác định các bounding box (hộp giới hạn) xung quanh chúng.

Quá trình phát hiện đối tượng bao gồm các bước sau:

1. Nhận dạng đối tượng: Thuật toán phát hiện đối tượng xác định xem có bao nhiêu đối tượng trong hình ảnh và loại đối tượng nào đang có mặt, sử dụng các phương pháp như deep learning (học sâu) và machine learning (học máy).

2. Định vị vị trí: Sau khi xác định được đối tượng, thuật toán object detection xác định vị trí của từng đối tượng bằng cách tạo ra một bounding box (hộp giới hạn) xung quanh đối tượng. Bounding box này xác định vùng chứa đối tượng và cho biết vị trí và kích thước của nó.

3. Phân loại đối tượng: Một khi đối tượng được xác định và vị trí được định vị, thuật toán object detection phân loại đối tượng đó vào một trong các nhãn đã biết trước (ví dụ: con người, ô tô, chó, …).

Phát hiện đối tượng được sử dụng trong nhiều ứng dụng thực tế, bao gồm:

- Tự động lái ô tô: Nhận dạng và theo dõi xe và các đối tượng khác trên đường để đảm bảo an toàn khi lái xe tự động.
- Giám sát an ninh: Phát hiện và nhận dạng những hành vi đáng ngờ trong video giám sát để bảo vệ an ninh công cộng và quản lý sự kiện.
- Tìm kiếm và định vị vật thể: Xác định vị trí của các đối tượng như một cuốn sách, điện thoại di động, hay chìa khóa trong một hình ảnh để hỗ trợ cho việc tìm kiếm và định vị.
- Trò chơi và thực tế ảo: Theo dõi và nhận dạng các đối tượng trong khung cảnh ảo để tạo ra một trải nghiệm trò chơi và thực tế ảo tương tác và chân thực.
Nói chung, phát hiện đối tượng đóng vai trò quan trọng trong việc hiểu và xử lý hình ảnh, đóng góp vào nhiều ứng dụng từ cuộc sống hàng ngày cho đến công nghiệp và khoa học.
# Các thuật toán và công cụ
## Classical machine learning

1. **Scale-Invariant Feature Transform (SIFT)**
2. **Speeded Up Robust Features (SURF)**
3. **Histogram of Oriented Gradients (HOG)**
4. **Support Vector Machine (SVM)**
5. **Random Forest (RF)**
6. **Adaboost**
7. **K-Nearest Neighbors (KNN)**
8. **K-Means Clustering**

While these techniques might be relevant for learning purposes, they are not used in the current state-of-the-art methods for image understanding. The following techniques are more relevant for the current state-of-the-art methods.

## Deep learning

1. **Convolutional Neural Networks (CNN)**
    - **ResNet**
    - **EfficientNet**
2. **Region-based CNN (R-CNN)**
    - **Fast R-CNN**
    - **Faster R-CNN**
    - **Mask R-CNN**
3. **You Only Look Once (YOLO)**
    - **YOLOv1, ..., YOLOv8**
4. **Transformer-based**
    - **Vision Transformer (ViT)**
    - **Data-efficient Vision Transformer (DeiT)**
    - **End-to-End Object Detection with Transformers (DETR)**
    - **Swin Transformer: Hierarchical Vision Transformer**
    - **Fully Transformer-based Object Detector (ViDT)**
    - **Point Cloud Transformer (PCT)**
5. **Vision Permutator: MLP-Like Architecture**
6. **GAN**
7. **Diffusion**
## Scale-Invariant Feature Transform (SIFT) 
là một thuật toán mạnh mẽ trong lĩnh vực nhận dạng và trích xuất đặc trưng hình ảnh. Thuật toán SIFT được phát triển bởi David Lowe vào năm 1999 và nhanh chóng trở thành một trong những công cụ phổ biến trong xử lý hình ảnh.

Nguyên tắc làm việc của thuật toán SIFT là như sau:

1. Đặc trưng tăng chức năng (Scale Space Extrema Detection): Đầu tiên, ảnh đầu vào được tạo ra một hình ảnh multi-scale (nhiều tỉ lệ) bằng cách áp dụng một hàm Gaussian với các tỉ lệ khác nhau. Tại mỗi tỉ lệ, điểm đặc trưng gọi là "keypoint" được tìm thấy bằng cách tìm kiếm các đỉnh cực trị trong không gian tỉ lệ.

2. Chọn vị trí đặc trưng chính xác (Keypoint Localization): SIFT tiếp tục xử lý những điểm đặc trưng tìm thấy từ bước trước và kiểm tra xem chúng có đáng tin cậy không. Điều này đảm bảo rằng các keypoint không bị ảnh hưởng bởi biến đổi tỉ lệ hay nhiễu.

3. Xây dựng hướng và tỉ lệ đặc trưng (Orientation Assignment): Mỗi keypoint được gán một hướng để tạo ra độ quan tâm không gian. Việc này được thực hiện bằng cách tính toán histogram độ biến thiên hướng xung quanh keypoint và lấy giá trị lớn nhất.

4. Trích xuất đặc trưng (Feature Descriptor): Cuối cùng, thuật toán SIFT tạo ra một vector đặc trưng có thể đại diện cho mỗi keypoint bằng cách tính toán biểu diễn của hình dạng và hướng. Vector đặc trưng này dựa trên gradient và khoảng cách từ keypoint đến các điểm hàng xóm.

Tổng hợp lại, thuật toán SIFT cho phép trích xuất các đặc trưng không thay đổi tỉ lệ và không bị ảnh hưởng bởi biến đổi hình học. Điều này giúp cho việc nhận dạng và đối sánh hình ảnh trở nên ổn định và tin cậy trong nhiều ứng dụng như nhận dạng đối tượng, ghép ảnh và phục hồi 3D.
## ResNet (Residual Neural Network) 
là một kiến trúc mạng nơ-ron sâu (deep neural network) đột phá trong lĩnh vực xử lý ảnh và được sử dụng rộng rãi trong computer vision.

Ý tưởng cơ bản của ResNet là xây dựng các "residual blocks" (khối dư thừa) để giải quyết vấn đề đóng góp của các tầng mạng trong việc học các biểu diễn phức tạp. Trong các mạng nơ-ron truyền thống, khi mạng trở nên sâu hơn, việc huấn luyện có thể gặp vấn đề đối với những tầng đóng góp ít vào kết quả cuối cùng, gọi là "vanishing gradient" (điểm gradient biến mất). Điều này khiến chúng khó có thể học được thông tin cần thiết cho việc phân loại.

ResNet giải quyết vấn đề này bằng cách sử dụng các "skip connections" (kết nối bỏ qua) để cho phép dữ liệu truyền thẳng từ tầng này sang tầng kế tiếp mà không qua bất kỳ phép biến đổi nào. Nhờ vậy, các tầng mới có thể học được các biểu diễn tinh vi hơn mà không bị ảnh hưởng bởi vấn đề "vanishing gradient". Những kết nối bỏ qua này còn được gọi là "identity shortcuts" (đoạn ngắn định danh) vì chúng giúp mô hình học cùng một định danh nhưng với mức độ chi tiết khác nhau.

Mạng ResNet có nhiều biến thể như ResNet-18, ResNet-34, ResNet-50, ResNet-101 và ResNet-152, với số lượng tầng và độ sâu khác nhau. Các biến thể này phù hợp cho các tác vụ xử lý ảnh khác nhau, từ nhận diện đơn giản đến phân loại ảnh phức tạp. ResNet đã chứng minh tính hiệu quả của mình trong nhiều cuộc thi và ứng dụng thực tế, trở thành một trong những kiến trúc quan trọng và phổ biến trong lĩnh vực computer vision.
# Các công cụ đã thử nghiệm
Thử nghiệm sử dụng các thuật toán nhận dạng đối tượng cho bài toán nhận dạng vân tay. 
## Bài toán nhận dạng vân tay 
là một trong các lĩnh vực ứng dụng của công nghệ nhận dạng đối tượng. Nội dung của bài toán này như sau:
- Cho CSDL các vân tay có mã số định trước (bằng tên file)
- Cho mẫu dấu tay cần tìm (thực tế chưa nhận được các mẫu này, vì vậy phải tạo ra mẫu nhân tạo từ các vân tay đã có sẵn, xem phần tạo mẫu giả để thử nghiệm)
- Cần xác định mã số của vân tay giống với mẫu dấu tay đã cho
- Yêu cầu
  1. Độ chính xác cao.
  2. Tốc độ học máy và nhận dạng cao.
  3. Việc thêm mẫu vân tay mới vào CSDL cần phải được thực hiện nhanh, không bị hạn chế, và không ảnh hưởng tới việc nhận dạng các mẫu vân tay đã có.
  4. Chương trình có thể đưa ra một số phương án kết quả khác nhau và xếp thứ tự về mức độ tương đồng của dấu tay với mẫu vân tay tìm thấy được

**Phần cứng đã sử dụng:**

Máy tính ảo không phí của colab.research.google.com. Tài nguyên của máy này gồm:

CPU RAM 25GB

Video RAM 16GB

GPU  Tương đương với T100, A100

## Tạo giả dấu tay cần tìm
Do bên đặt hàng không cung cấp các mẫu dấu tay thực cần tìm kiếm, mà chỉ cung cấp CSDL gồm 10001 thẻ vân tay, nên đội nghiên cứu đã tạo giả các mẫu dấu tay cần tìm từ các hình vân tay có sẵn, bằng cách cắt lấy một mẩu nhỏ từ các hình đó. Để mẫu giả giống thực hơn, mỗi mẫu được quay đi một góc bất kỳ và làm nhòe đi một lượng bất kỳ so với bản gốc.

## 1. Autoencoder
là một mô hình mạng nơ-ron tự động mã hóa (unsupervised learning) được sử dụng rộng rãi trong lĩnh vực xử lý ảnh và nhận dạng đối tượng (object recognition).

Cơ bản, autoencoder có hai phần chính: phần mã hóa (encoder) và phần giải mã (decoder). Mục tiêu của autoencoder là học cách biểu diễn dữ liệu đầu vào thành một biểu diễn tương tự, gọi là mã hóa (latent representation), và sau đó giải mã nó trở lại dạng ban đầu. Autoencoder được đào tạo bằng cách tối thiểu hóa sai số giữa dữ liệu gốc và dữ liệu tái tạo, thông qua quá trình lan truyền ngược (backpropagation) để điều chỉnh trọng số của mô hình.

Trong bài toán nhận dạng đối tượng, autoencoder có thể được sử dụng như một công cụ để rút trích các đặc trưng quan trọng từ ảnh. Cụ thể, autoencoder học cách biểu diễn dữ liệu hình ảnh thành một biểu diễn nguyên thủy, có thể là một vectơ dữ liệu thưa (sparse) hoặc một tập hợp các giá trị trọng số (weights). Quá trình này giúp giảm chiều dữ liệu và tách riêng các đặc trưng quan trọng từ dữ liệu không gian lớn.

Sau khi autoencoder đã học được các biểu diễn đặc trưng, chúng có thể được sử dụng để giảm chiều dữ liệu hoặc phục vụ cho các nhiệm vụ nhận dạng đối tượng khác. Các biểu diễn đặc trưng này thường là những biểu diễn nguyên thủy của dữ liệu, giúp giảm thiểu thông tin không cần thiết và tập trung vào những đặc điểm quan trọng, dễ dàng cho mô hình nhận dạng đối tượng để sử dụng.

Tuy autoencoder không phải là phương pháp trực tiếp để nhận dạng đối tượng, nhưng nó là một công cụ hữu ích để tạo ra các biểu diễn đặc trưng cần thiết để đạt được kết quả nhận dạng đối tượng chính xác hơn, đặc biệt khi dữ liệu có nhiều chiều hoặc khi lượng dữ liệu lớn.

Các bước sử dụng autoencoder để nhận dạng vân tay như sau:
- Khi dạy autoencoder, cho các vân tay qua autoencoder để vẽ lại chính nó. Nếu vẽ thành công thì ở đầu ra của encoder ta sẽ nhận được vector đặc trưng của vân tay. Sau khi dạy xong lưu lại encoder.
- Sau đó cho từng vân tay qua encoder để lưu lại vector của nó vào CSDL.
- Khi có mẫu vân tay cần tìm, lấy vector của mẫu so với CSDL các vector có sẵn để tìm.
- Các vector có thể so với nhau bằng cách đo khoảng cách Euclide (sai số toàn phương trung bình)

**Biện pháp đã thực hiện:**

- Máy google colab không phí có quá ít bộ nhớ, nên không tạo được mạng CNN xử lý được toàn bộ hình ảnh vân tay. Vì vậy, phải chia hình ảnh vân tay ra các mẩu nhỏ kích thước 32x32. Cho autoencoder học vẽ lại các mẩu con đó.
- Để tăng chất lượng học cho autoencoder, các mẩu 32x32 được lấy từ giữa ra theo hình xoáy trôn ốc, phần rìa có thể không cần lấy, vì thông thường phần ngoài rìa không có vân tay và hay có các nhiễu bẩn. Các hình được lấy ra của mỗi vòng trùng nhau một phần tư so với hình của vòng trước.
-	Sau khi dạy xong, lưu lại encoder.
-	Quy tất cả các hình ảnh vân tay thành cùng 1 độ phân giải. Mỗi một hình ảnh chia nhỏ thành các mẩu 32x32, cho qua encoder để nhận được các vector. Tập hợp tất cả các vector của cùng một vân tay thành vector của vân tay. Có thể để nguyên vị trí các vector như trong hình (2D). Lưu tất cả các hình thành CSDL.
-	Chia dấu tay thành các mẩu hình kích thước 32x32 và cho qua encoder để lấy vector của các mẩu đó. Nối lại thành vector của hình dấu tay.
-	So sánh vector của dấu tay với vector của từng mẫu vân tay trong CSDL để tìm khoảng cách giữa chúng với nhau. 
-	Đếm số lượng các vector có khoảng cách nhỏ hơn ngưỡng đặt ra. Tìm hình có số lượng trùng lớn nhất
-	Nếu lập bản đồ 2D vị trí các vector trùng, có thể nhìn thấy được vị trí các ô trùng nhau (theo tính toán).
- Chất lượng kết quả không được tốt. Kết quả tìm kiếm phụ thuộc nhiều vào vị trí, góc quay và độ nhòe của dấu tay được tạo. Nguyên nhân chủ yếu do việc chia nhỏ hình gốc - các đặc trưng của mẩu đó (vector nhận được) phụ thuộc vào vị trí của mẩu trên hình, các điểm đặc trưng về bản chất phải nằm trong một bản đồ hai chiều, trong khi các vector lại được nối với nhau thành chuỗi tuyến tính. Ngoài ra, ranh giới cắt mỗi mẩu 32x32 của vân tay và của dấu tay sẽ ảnh hưởng đến các điểm đặc trưng rơi vào từng vector được tạo ra và khoảng cách giữa các vector sẽ không thể hiện chân thực mức độ phù hợp của toàn bộ dấu tay. Tỉ lệ, độ phân giải, góc nghiêng của dấu tay cũng có thể ảnh hưởng đến kết quả đo khoảng cách.

## 2. Scale-Invariant Feature Transform (SIFT)
- Dùng thuật toán SIFT để tìm các điểm đặc trưng của vân tay. Lưu lại các đặc trưng của từng vân tay vào CSDL.
- Tìm các điểm đặc trưng của mẫu dấu tay
- Dùng giải thuật FLANN (Fast Library for Approximate Nearest Neighbors) để tìm các cặp tương đồng giữa các điểm đặc trưng của dấu tay và từng vân tay trong CSDL
- Dùng phương pháp thử nghiệm tỉ lệ của Lowe (Lowe's ratio test) để loại bỏ các cặp không hợp lệ
- Tìm mẫu vân tay có số lượng cặp tương đồng lớn nhất.
- Kết quả của phương pháp này cho phép tìm kiếm từ một mẫu bị quay 1 góc bất kỳ, cắt thành miếng nhỏ, làm nhòe đến sigma=3 với độ chính xác trên 95%, tỉ lệ sai 0%.
- Dùng thư viện OpenCV (cv2) có thể chỉ ra vị trí của dấu tay cần tìm trên mẫu vân tay, các cặp điểm tương đồng và vẽ đường nối các điểm đó với nhau.
- Nếu số điểm tương đồng dưới 5 có thể kết luận là không tìm thấy (đã thử nghiệm trên bộ CSDL 1000 file). Thông thường phương án tìm được phải có ít nhất vài chục điểm tương đồng.
- Giải pháp này có thể dùng cho nhiều ứng dụng trong việc giải quyết bài toán tìm vân tay:
	+ do tốc độ cao trong việc tìm kiếm và đòi hỏi tài nguyên thấp, có thể sử dụng cho các máy kiểm tra di động. VD đối với bài toán tìm dấu tay trong một danh sách hạn chế (chẳng hạn như danh sách nhân viên công ty, danh sách truy nã, v.v...) có thể ghi sẵn toàn bộ danh sách trong máy di động mà không cần nối với máy chủ
	+ dùng cho việc chứng minh mức tương đồng của dấu tay và mẫu vân tay: vẽ vị trí dấu tay và chỉ ra các cặp điểm tương đồng trên hình vẽ
	+ dùng để kiểm tra kết quả tìm kiếm bằng các giải pháp khác, hoặc nếu có giải pháp đã đưa ra được danh sách hạn chế các ứng cử viên – tìm trong danh sách hạn chế đó.

