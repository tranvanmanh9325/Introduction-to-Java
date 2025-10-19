# Các thuật ngữ cơ bản: JVM, JRE, JDK

## Mục lục

- [Máy ảo Java (JVM)](#máy-ảo-java-jvm)
- [Bộ phận phát triển Java (JDK)](#bộ-phận-phát-triển-java-jdk)
- [Môi trường chạy Java (JRE)](#môi-trường-chạy-java-(jre))
- [Mối quan hệ giữa JVM, JRE và JDK](#mối-quan-hệ-giữa-jvm,-jre-và-jdk)
- [Bản tóm tắt](#bản-tóm-tắt)

Các ngôn ngữ JVM, chẳng hạn như Java, Kotlin hoặc Scala, có thể gây nhầm lẫn cho người mới bắt đầu vì có một số thuật ngữ cơ bản có thể khó phân biệt lúc đầu. Chủ đề này sẽ giúp bạn làm quên hơn với việc phát triển cho Java Platform bằng cách giới thiệu những kiến thức cơ bản đó và cung cấp cái nhìn tổng quát về cách mã được xử lý bởi các thành phần khác nhau của nền tảng.

## Máy ảo Java (JVM)

Máy ảo Java , hay JVM , là một mô phỏng ảo của máy tính vật lý. Nó thực thi mã bytecode Java (hoặc tương thích với Java), mã này xuất hiện sau khi biên dịch mã nguồn. Theo một nghĩa nào đó, JVM hoạt động như một trung gian giữa mã nguồn và máy thật. Nó hoạt động với một tập hợp các lệnh bytecode thống nhất được diễn giải và dịch thành các lệnh máy.

JVM có sẵn cho nhiều nền tảng phần cứng và phần mềm, vì vậy bạn có thể chạy mã bytecode ở hầu hết mọi nơi. Một chương trình được biên dịch sang mã bytecode hầu như luôn độc lập với nền tảng. Về cơ bản, khi bạn có mã ngôn ngữ JVM, bạn chỉ cần biên dịch nó một lần, lấy mã bytecode và bạn sẽ có thể chạy nó trên bất kỳ nền tảng nào có JVM.

Ngày nay có nhiều phiên bản JVM khác nhau, trong đó Java HotSpot Virtual Machine là tài liệu tham khảo chính.
