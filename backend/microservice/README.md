# Câu hỏi phỏng vấn Microservice

![](./assets/microservices.png)

## Microservice là gì?

Microservice là một kỹ thuật phát triển phần mềm, một biến thể của kiến trúc hướng dịch vụ cấu trúc một ứng dụng như một tập hợp các dịch vụ được ghép lỏng lẻo. Trong kiến trúc microservice, các dịch vụ được xử lý tốt và các giao thức rất nhẹ. Các ứng dụng được mô hình hoá dưới dạng các dịch vụ, nó giúp:
- Dễ bảo trì và kiếm tra
- Kết nối mềm
- Có thể triển khai độc lập
- Được thiết kế hoặc tổ chức dựa trên khả năng doanh nghiệp
- Được quản lý bởi một team nhỏ

![](./assets/Microservices_Interview.jpg)

## Câu hỏi phỏng vấn cho Fresher

### 1. Các tính năng chính của Microservices?

![](./assets/features_of_Microservices.jpg)

- **Phân Tách:** Trong một hệ thống, các dịch vụ chủ yếu được phân tách. Do đó, toàn bộ ứng dụng có thể dễ dàng được xây dựng, thay đổi và có thể mở rộng.
- **Thành phần hóa:** Microservice được xem như các thành phần độc lập có thể dễ dàng được trao đổi hoặc nâng cấp.
- **Kích cỡ nghiệp vụ:** Microservice tương đối đơn giản và chỉ tập trung vào một dịch vụ.
- **Quyền tự chủ của nhóm:** Các nhà phát triển làm việc độc lập với nhau, cho phép tiến trình dự án nhanh hơn.
- **Phân phối liên tục:** Cho phép phát hành phần mềm thường xuyên thông qua hệ thống tự động hóa phát triển, kiểm tra và phê duyệt phần mềm.
- **Trách nhiệm:** Microservices không tập trung vào các ứng dụng như các dự án. Thay vào đó, họ coi các ứng dụng là sản phẩm mà họ chịu trách nhiệm.
**Quản trị phi tập trung:** Lựa chọn công cụ phù hợp theo công việc là mục tiêu. Các nhà phát triển có thể chọn các công cụ tốt nhất để giải quyết vấn đề của họ
- **Kết hợp Agile:** Microservices tạo điều kiện cho kết hợp với phương pháp Agile. Có thể tạo các tính năng mới một cách nhanh chóng và loại bỏ chúng bất cứ lúc nào

### 2. Các thành phần chính trong Microservices?

* Containers, Clustering, và Orchestration.
* IaC [Infrastructure as Code Conception] 
* Cloud Infrastructure 
* API Gateway 
* Enterprise Service Bus 
* Service Delivery 

### 3. Ưu nhược điểm của Microservices?

**Ưu điểm**

- Module triển khai khép kín và độc lập.
- Các dịch vụ được quản lý độc lập.
- Để cải thiện hiệu suất, dịch vụ yêu cầu có thể được triển khai trên nhiều server.
- Nó dễ kiểm tra hơn và có ít phụ thuộc hơn.
- Khả năng mở rộng lớn hơn.
- Đơn giản trong việc debug và bảo trì.
- Giao tiếp tốt hơn giữa nhà phát triển và người dùng doanh nghiệp.
- Các nhóm phát triển có quy mô nhỏ hơn.

**Nhược điểm**

- Do sự phức tạp của kiến trúc, việc kiểm tra và giám sát khó khăn hơn.
- Thiếu văn hóa doanh nghiệp phù hợp để nó hoạt động.
- Lập kế hoạch trước là điều cần thiết.
- Phát triển phức tạp.
- Yêu cầu một sự chuyển dịch văn hóa.
- Đắt so với monoliths.
- Nguy cơ về bảo mật.
- Việc duy trì mạng khó khăn hơn.

### 4. Các công cụ thường dùng cho Microservices?

- Wiremock
- Docker
- Hstrix

### 5. Giải thích kiến trúc Microservice?

![](./assets/Microservice_Architecture.jpg)

- **Clients**: Người dùng khác nhau gửi yêu cầu đến thiết bị khác nhau.
- **Identity Provider**: Xác thực định danh người dùng hoặc client và cấp token bảo mật.
- **API Gateway**: xử lý yêu cầu từ client.
- **Static Content**: Bao gồm tất cả nội dung của hệ thống.
- **Management**: Dịch vụ được cản bằng trên các node và lỗi được xác định.
- **Service Discovery**: Hướng dẫn khám phá các định tuyến để giao tiếp trong microservices.
- **CDN**: bao gồm mạng phân phối của proxy server và trung tâm dữ liệu của họ.
- **Remote Service**: Cung cấp khả năng truy cập từ xa vào dữ liệu hoặc thông tin trên các máy tính và thiết bị được nối mạng.

### 6. Sự khác biệt giữa Monolithic, SOA và Microservices?

![](./assets/difference_between_Monolithic__SOA_and_Microservices_Architecture.jpg)

**Monolithic**: Giống như một container lớn, trong đó là tất cả thành phần của ứng dụng được gói cùng với nhau. Nó được xây dựng như một hệ thống lớn với một code-base.

**SOA (Serivce-Oriented Architecture)**: Nó là một nhóm các dịch vụ tương tác hoặc giao tiếp với nhau. Tùy thuộc vào bản chất của giao tiếp, nó có thể là trao đổi dữ liệu đơn giản hoặc nó có thể liên quan đến một số dịch vụ phối hợp một số hoạt động. 

**Microservice**: Nó liên quan đến việc cấu trúc một ứng dụng dưới dạng một cluster (cụm) các dịch vụ nhỏ, tự trị được mô hình hóa xung quanh một miền doanh nghiệp. Các module chức năng có thể được triển khai độc lập, có thể mở rộng, nhằm đạt được các mục tiêu kinh doanh cụ thể và giao tiếp với nhau qua các giao thức tiêu chuẩn.

### 7. Cohesion và Coupling là gì?

**Khớp nối (Cohesion):** Nó được định nghĩa là mối quan hệ giữa các modile phần mềm A và B, và mức độ một module phụ thuộc hoặc tương tác với một module khác. Các khớp nối được chia thành ba loại chính. Các module có thể được ghép nối nhiều (phụ thuộc nhiều), liên kết lỏng lẻo và tách rời khỏi nhau. Loại khớp nối tốt nhất là khớp nối lỏng, được thực hiện thông qua các interface.

**Liên kết (Coupling):** Nó được định nghĩa là mối quan hệ giữa hai hoặc nhiều phần tử của một module phục vụ cùng một mục đích. Nói chung, một module có tính liên kết cao có thể thực hiện một chức năng cụ thể một cách hiệu quả mà không cần giao tiếp với bất kỳ module nào khác. Tính liên kết cao nâng cao chức năng của module.

![](./assets/Cohesion_and_Coupling.jpg)

### 8. Bounded Context là gì?

Một bounded context là một mẫu trung tâm trong DDD (Domain-Driven Design), đề cập đến sự cộng tác giữa các mô hình và nhóm lớn. DDD chia nhỏ các mô hình lớn thành nhiều ngữ cảnh để giúp chúng dễ quản lý hơn. Ngoài ra, nó giải thích mối quan hệ của họ một cách rõ ràng. Khái niệm này thúc đẩy phương pháp tiếp cận hướng đối tượng để phát triển các dịch vụ gắn với mô hình dữ liệu và cũng chịu trách nhiệm đảm bảo tính toàn vẹn và khả năng thay đổi của mô hình dữ liệu nói trên.

![](./assets/Bounded_Context.jpg)

### 9. Viết các đặc điểm cơ bản của Thiết kế Microservice?

- Dựa trên khả năng kinh doanh: Các dịch vụ được phân chia và tổ chức xoay quanh khả năng kinh doanh.
- Sản phẩm không phải dự án: Một sản phẩm nên thuộc về team có trách nhiệm xử lý nó.
- Dựa vào các framework message: Loại bỏ các bus dịch vụ tập trung bằng cách nắm lấy khái niệm phân quyền.

### 10. Các thách thức khi sử dụng Microservices?

Những thách thức mà ta phải đối mặt khi sử dụng microservices có thể là cả chức năng và kỹ thuật như dưới đây:

#### Thách thức chức năng:

- Yêu cầu thiết lập cơ sở hạ tầng nặng.
- Cần đầu tư nặng.
- Yêu cầu lập kế hoạch quá mức để xử lý hoặc quản lý chi phí hoạt động

#### Thách thức kỹ thuật:

- Các microservices luôn phụ thuộc lẫn nhau. Vì vậy, chúng phải giao tiếp với nhau.
- Nó là một mô hình có nhiều liên quan vì là một hệ thống phân tán.
- Bạn cần chuẩn bị cho các hoạt động nhiều chi phí nếu bạn đang sử dụng kiến trúc Microservice.
- Để hỗ trợ các dịch vụ vi mô được phân phối không đồng nhất, bạn cần các chuyên gia có tay nghề cao.
- Rất khó để tự động hóa vì số lượng các thành phần ít hơn. Vì lý do đó, mỗi thành phần phải được xây dựng, triển khai và giám sát riêng biệt.
- Rất khó để quản lý cấu hình trên các môi trường khác nhau cho tất cả các thành phần.
- Những thách thức liên quan đến triển khai, gỡ lỗi và thử nghiệm.

### 11. Giải thích PACT trong Microservices?

PACT được định nghĩa là một công cụ mã nguồn mở cho phép các nhà cung cấp dịch vụ và người tiêu dùng kiểm tra các tương tác một cách tách biệt với các hợp đồng đã được thực hiện để tăng độ tin cậy của tích hợp microservice. Nó cũng cung cấp hỗ trợ cho nhiều ngôn ngữ, chẳng hạn như Ruby, Java, Scala, .NET, JavaScript, Swift/Objective-C.

### 12. Giải thích cách microservice giao tiếp với các phần khác?

Giao tiếp giữa các microservice có thể thực hiện:
- HTTP/REST với JSON hoặc giao thức nhị phân cho request/response.
- Websocket cho streaming
- Một broker hoặc server dùng cho các thuật toán routing.

RabbitMQ, Kafka,... có thể dùng như một message broker, mỗi cái được xây dựng để xử lý message cụ thể. 

### 13. Client certificates là gì?

Client certificates là một loại chứng chỉ kỹ thuật số thường cho phép các hệ thống client xác thực các yêu cầu của họ tới các server từ xa. Trong nhiều thiết kế xác thực lẫn nhau, nó đóng một vai trò quan trọng trong việc cung cấp sự đảm bảo mạnh mẽ về danh tính của người yêu cầu.

### 14. Giải thích về CDC?

Như tên của nó, CDC (Consumer-Driven Contract) về cơ bản đảm bảo khả năng tương thích giao tiếp dịch vụ bằng cách thiết lập một thỏa thuận giữa người tiêu dùng và nhà cung cấp dịch vụ về định dạng dữ liệu được trao đổi giữa họ. Một thỏa thuận như thế này được gọi là hợp đồng. Về cơ bản, nó là một mẫu được sử dụng để phát triển các Microservices để chúng có thể được các hệ thống bên ngoài sử dụng một cách hiệu quả.

### 15. Các công ty nổi tiếng sử dụng kiến trúc Microservices?

- Twitter
- Netflix
- Amazon

## Câu hỏi phỏng vấn cho Experienced

### 16. Semantic Monitoring là gì?

Semantic monitoring, còn được gọi là giám sát tổng hợp, sử dụng các bài kiểm tra tự động và giám sát ứng dụng để xác định lỗi trong quy trình kinh doanh. Công nghệ này cung cấp cái nhìn sâu hơn về hiệu suất giao dịch, tính khả dụng của dịch vụ và hiệu suất ứng dụng tổng thể để xác định các vấn đề về hiệu suất của microservices, phát hiện lỗi trong giao dịch và cung cấp mức hiệu suất tổng thể cao hơn.

### 17. Continuos monitoring là gì?

Giám sát liên tục (continuos monitoring) liên quan đến việc xác định các vấn đề tuân thủ và rủi ro trong môi trường tài chính và hoạt động của công ty. Nó bao gồm con người, quy trình và hệ thống làm việc hỗ trợ hoạt động hiệu quả và hiệu quả.

### 18. Domain Driven Design là gì?

DDD (Domain Driven Design) là một phương pháp tiếp cận trong việc phân tích và phát triển phần mềm khi giải quyết những vấn đề nghiệp vụ phức tạp. Ý tưởng cơ bản của phương pháp này là việc xây dựng sự kết nối chặt chẽ giữa thiết kế phần mềm và mô hình nghiệp vụ trong suốt vòng đời phát triển sản phẩm. Để tạo nên sự kết nối này, DDD đưa ra 3 yêu cầu cơ bản:

- Trọng tâm của dự án là những nguyên tắc và logic nghiệp vụ
- Thiết kế phần mềm cần phải phản ánh chính xác mô hình nghiệp vụ
- Sự cộng tác liên tục giữa kĩ sư và chuyên gia nghiệp vụ

Kết quả của việc phân tích hệ thống dựa trên phương pháp DDD, kết hợp cùng mô hình kiến trúc Microservices giúp chúng ta tổ chức và phát triển những microservices giải quyết các vấn đề nghiệp vụ một cách tương ứng. Hoạt động kết hợp này được phản ánh qua một qui trình bao gồm các bước:

- Phân tích nghiệp vụ - domain model
- Định nghĩa ngữ cảnh - bounded context
- Định nghĩa đối tượng (entities), tập hợp (aggregate) và dịch vụ (service)
- Xác định microservices cần xây dựng

![](./assets/ddd.png)

### 19. Giải thích về OAuth và OAuth2?

**OAuth** là một phương thức xác thực giúp một ứng dụng bên thứ 3 có thể được ủy quyền bởi người dùng để truy cập đến tài nguyên người dùng nằm trên một dịch vụ khác. OAuth là từ ghép của O(Open) và Auth tượng trưng cho:

- *Authentication*: xác thực người dùng.
- *Authorization*: cấp quyền truy cập đến tài nguyên mà người dùng hiện đang nắm giữ.

OAuth2 là bản nâng cấp của OAuth1.0, là một giao thức chứng thực cho phép các ứng dụng chia sẻ một phần tài nguyên với nhau mà không cần xác thực qua username và password như cách truyền thống từ đó giúp hạn chế được những phiền toái khi phải nhập username, password ở quá nhiều nơi hoặc đăng ký quá nhiều tài khoản mật khẩu mà chúng ta chẳng thể nào nhớ hết.

Trong OAuth2 định nghĩa 4 vai trò:

- **Resource owner:** là những người dùng có khả năng cấp quyền truy cập, chủ sở hữu của tài nguyên mà ứng dụng muốn lấy.
- **Resource server:** nơi lưu trữ các tài nguyên, có khả năng xử lý yêu cầu truy cập đến các tài nguyên được bảo vệ.
- **Client**: là những ứng dụng bên thứ 3 muốn truy cập vào phần tài nguyên được chia sẻ với tư cách của người sở hữu (resource owner) và tất nhiên trước khi truy cập ứng dụng cần được sự ủy quyền của user.
- **Authorization server:** làm nhiệm vụ xác thực, kiểm tra thông tin mà user gửi đến từ đó cấp quyền truy cập cho ứng dụng bằng việc sinh ra các đoạn mã access token. Đôi khi authorization server cũng chính là resource server.

![](./assets/oauth.jpg)

### 20. Distributed Transactions là gì?

Giao dịch phân tán (distributed transactions) là một cách tiếp cận lỗi thời trong kiến trúc microservice ngày nay khiến nhà phát triển gặp phải các vấn đề nghiêm trọng về khả năng mở rộng. Các giao dịch được phân phối cho một số dịch vụ được gọi để hoàn thành giao dịch theo trình tự. Với rất nhiều bộ phận chuyển động, nó rất phức tạp và dễ bị hỏng hóc.

### 21. Idempotence là gì?

Thuật ngữ "Idempotence" đề cập đến việc thực hiện lặp đi lặp lại một nhiệm vụ mặc dù cùng một kết quả. Nói cách khác, nó là một tình huống trong đó một nhiệm vụ được thực hiện lặp đi lặp lại với kết quả cuối cùng được giữ nguyên.
 
Cách sử dụng: Khi dịch vụ từ xa hoặc nguồn dữ liệu nhận được hướng dẫn nhiều lần, Idempotence đảm bảo rằng nó sẽ xử lý từng yêu cầu một lần.

### 22. Ent-to-end microservices testing là gì?

Thông thường, end-to-end (E2E) microservice testing là một kỹ thuật không phối hợp, chi phí cao được sử dụng để đảm bảo rằng tất cả các thành phần hoạt động cùng nhau cho một hành trình hoàn chỉnh của người dùng. Thông thường, nó được thực hiện thông qua giao diện người dùng, bắt chước cách nó xuất hiện với người dùng. Nó cũng đảm bảo tất cả các quy trình trong quy trình làm việc hoạt động bình thường.

### 23. Thuật ngữ Euruka trong Microservices?

Eureka Server, còn được gọi là Netflix Service Discovery Server, là một ứng dụng theo dõi tất cả các ứng dụng dịch vụ client. Vì mọi Microservice đăng ký với Server Eureka, Eureka biết tất cả các ứng dụng client đang chạy trên các cổng và địa chỉ IP khác nhau. Nó thường sử dụng Spring Cloud và không nặng về quá trình phát triển ứng dụng.