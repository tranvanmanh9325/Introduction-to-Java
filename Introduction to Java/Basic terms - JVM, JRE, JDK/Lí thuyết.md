# Các thuật ngữ cơ bản: JVM, JRE, JDK

## Mục lục

- [Máy ảo Java (JVM)](#máy-ảo-java-jvm)
- [Bộ phát triển Java (JDK)](#bộ-phát-triển-java-jdk)
- [Môi trường chạy Java (JRE)](#môi-trường-chạy-java-jre)
- [Mối quan hệ giữa JVM, JRE và JDK](#mối-quan-hệ-giữa-jvm-jre-và-jdk)
- [Bản tóm tắt](#bản-tóm-tắt)

Các ngôn ngữ JVM, chẳng hạn như Java, Kotlin hoặc Scala, có thể gây nhầm lẫn cho người mới bắt đầu vì có một số thuật ngữ cơ bản có thể khó phân biệt lúc đầu. Chủ đề này sẽ giúp bạn làm quên hơn với việc phát triển cho Java Platform bằng cách giới thiệu những kiến thức cơ bản đó và cung cấp cái nhìn tổng quát về cách mã được xử lý bởi các thành phần khác nhau của nền tảng.

## Máy ảo Java (JVM)

Máy ảo Java , hay JVM , là một mô phỏng ảo của máy tính vật lý. Nó thực thi mã bytecode Java (hoặc tương thích với Java), mã này xuất hiện sau khi biên dịch mã nguồn. Theo một nghĩa nào đó, JVM hoạt động như một trung gian giữa mã nguồn và máy thật. Nó hoạt động với một tập hợp các lệnh bytecode thống nhất được diễn giải và dịch thành các lệnh máy.

JVM có sẵn cho nhiều nền tảng phần cứng và phần mềm, vì vậy bạn có thể chạy mã bytecode ở hầu hết mọi nơi. Một chương trình được biên dịch sang mã bytecode hầu như luôn độc lập với nền tảng. Về cơ bản, khi bạn có mã ngôn ngữ JVM, bạn chỉ cần biên dịch nó một lần, lấy mã bytecode và bạn sẽ có thể chạy nó trên bất kỳ nền tảng nào có JVM.

Ngày nay có nhiều phiên bản JVM khác nhau, trong đó Java HotSpot Virtual Machine là tài liệu tham khảo chính.

### Bộ phát triển Java (JDK)

**Bộ công cụ phát triển Java**, hay **JDK**, là một gói phần mềm để phát triển chương trình cho Nền tảng. Nó bao gồm JRE để chạy các chương trình và công cụ dành cho nhà phát triển: trình biên dịch Java, trình gỡ lỗi, trình lưu trữ, trình tạo tài liệu, v.v.

Ở giai đoạn biên dịch, trình biên dịch sẽ dịch mã nguồn thành **.class** các tệp chứa mã bytecode và có thể được thực thi bởi JVM. Lưu ý rằng nếu bạn sử dụng các ngôn ngữ JVM khác ngoài Java, bạn sẽ cần tải xuống trình biên dịch riêng vì chúng không được đóng gói cùng với JDK.

Trên thực tế, các chương trình thưởng bao gồm nhiều **.class** tệp được đóng gói cùng nhau bằng một công cụ lưu trữ thành một kho lưu trữ Java(tệp JAR). JRE có thể chạy chương trình được đóng gói trực tiếp vào JAR mà không cần giải nén các tệp đã lưu trữ. Tệp kết quả thuận tiện hơn cho việc lưu trữ và chia sẻ qua mạng vì dữ liệu đã được nén.

### Môi trường chạy Java (JRE)

**Java Runtime Environment**, hay **JRE**, là một môi trường thực thi. Nó bao gồm các thành phần cần thiết để chạy các chương trình JVM đã biên dịch: bản thân JVM và Thư viện lớp Java(JCL).

JCL về cơ bản là một tập hợp các thư viện chuẩn cung cấp các chức năng phổ biến nhất: các lớp cơ bản, đầu vào/đầu ra, gói toán học, bộ sưu tập, bảo mật, bộ công cụ giao diện người dùng và dùng nhiều chức năng khác. Bạn có thể sử dụng các thư viện này trong chương trình của mình.

> **😎 Trước Java 11, nếu bạn chỉ muốn chạy chương trình Java, JRE là đủ. Tuy nhiên, kể từ khi Java 11 ra mắt, đối với hầu hết các triển khai JVM, JRE không còn có thể tải xuống dưới dạng một thành phần riêng biệt nữa. Nếu bạn muốn chạy chương trình trong JVM 11 hoặc mới hơn, bạn phải cài đặt JDK.**

Khi bạn chạy một chương trình đã biên dịch, JRE sẽ kết hợp mã byte của chương trình với các thư viện cần thiết và chạy JVM, thực thi mã byte kết quả.

### Mối quan hệ giữa JVM, JRE và JDK

Hình ảnh sau đây minh họa mối quan hệ giữa JVM, JRE và JDK:

![Mối quan hệ giữa JVM, JRE và JDK](/Basic%20terms%20-%20JVM,%20JRE,%20JDK/public/picture1.svg)

### Bản tóm tắt

- Máy ảo Java thực thi mã bytecode đã biên dịch.

- Java Runtime Environment bao gồm JVM và các thư viện chuẩn và chạy các chương trình đã biên dịch.

- Bộ công cụ phát triển Java, bao gồm JRE và các công cụ phát triển, được các nhà phát triển sử dụng để viết chương trình