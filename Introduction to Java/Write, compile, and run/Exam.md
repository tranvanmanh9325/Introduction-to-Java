# Viết, biên dịch và chạy

## Mã nguồn được dịch thành gì?

Trình biên dịch của ngôn ngữ JVM, chẳng hạn như Kotlin, sẽ dịch mã nguồn thành gì?

Điền vào chỗ trống với các yếu tố có liên quan

**Câu hỏi:** Trình biên dịch của ngôn ngữ JVM dịch mã nguồn thành ________

<div style = "display: flex; gap: 2em"><span>bytecode</span><span>machine code</span><span>user code</span><span>bitcode</span></div>

**Đáp án:** Trình biên dịch của ngôn ngữ JVM dịch mã nguồn thành <u> **bytecode** </u>

## Nền tảng độc lập

**Câu hỏi:** Chọn một câu đúng về tính độc lập của nền tảng trong thế giới Java.

- Các chương trình cần có cú pháp đặc biệt để đạt được sự độc lập với nền tảng.

- Các chương trình phụ thuộc trực tiếp vào phần cứng máy tính và hệ điều hành.

- Các chương trình được thực thi trên Máy ảo Java để đạt được sự độc lập với nền tảng.

- Các chương trình được thực thi trên Máy ảo Java nếu hệ điều hành không phải là Linux.

**Đáp án:** Các chương trình được thực thi trên Máy ảo Java để đạt được sự độc lập với nền tảng.

## MyHelloWorldApplication.class

Các chương trình được thực thi trên Máy ảo Java để đạt được sự độc lập với nền tảng.

**Câu hỏi:** Chọn một tùy chọn từ danh sách

- Java source code

- Ngôn ngữ trung gian phổ biến

- JavaScript

- Bytecode

- Machine code

**Đáp án:** Bytecode

## Mục đích của bytecode

Bytecode cần thiết để làm gì?

**Câu hỏi:**

Chọn một tùy chọn từ danh sách

- Nó làm cho các chương trình được viết bằng ngôn ngữ JVM trở nên độc lập với nền tảng

- Nó nhỏ gọn hơn mã gốc của chương trình, do đó các lập trình viên sử dụng nó để đọc chương trình nhanh hơn

- Nó cho phép lưu trữ một chương trình dưới dạng một tập hợp các byte trên máy tính

- Nó bảo vệ mã nguồn của chương trình

- Nó giúp con người viết và hiểu các chương trình

**Đáp án:** Nó làm cho các chương trình được viết bằng ngôn ngữ JVM trở nên độc lập với nền tảng

## Một hệ thống thực thi các chương trình Java

Nhập chữ viết tắt cho hệ thống thực thi chương trình Java.

Gợi ý: từ viết tắt này bao gồm ba chữ cái.

**Câu hỏi:** Điền vào chỗ trống với các yếu tố có liên quan

Viết tắt của hệ thống thực thi chương trình Java là: _________

**Đáp án:** JVM

## Ghép các khai niệm và bối cảnh

Ghép các khai niệm sau với mô tả của chúng

**Câu hỏi** Ghép các mục từ cột bên trái và bên phải

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<div style="display: flex; flex-direction: column; gap: 1em; width: 700px;">

  <!-- Row 1 -->
  <div style="display: flex; gap: 1em;">
    <div style="flex: 1; border: 1px solid #ddd; border-radius: 8px; padding: 10px 14px;">
      Source code
    </div>
    <div style="flex: 1; border: 1px solid #ddd; border-radius: 8px; padding: 10px 14px; display: flex; justify-content: space-between; align-items: center;">
      <div style="display: flex; align-items: center; gap: 0.6em;">
        <i class="fa-solid fa-grip-vertical" style="cursor: grab; color: #666;"></i>
        <span>usually, developers write this code</span>
      </div>
      <div style="display: flex; flex-direction: column; gap: 2px;">
        <i class="fa-solid fa-chevron-up" style="cursor: pointer; color: #777;"></i>
        <i class="fa-solid fa-chevron-down" style="cursor: pointer; color: #777;"></i>
      </div>
    </div>
  </div>

  <!-- Row 2 -->
  <div style="display: flex; gap: 1em;">
    <div style="flex: 1; border: 1px solid #ddd; border-radius: 8px; padding: 10px 14px;">
      Bytecode
    </div>
    <div style="flex: 1; border: 1px solid #ddd; border-radius: 8px; padding: 10px 14px; display: flex; justify-content: space-between; align-items: center;">
      <div style="display: flex; align-items: center; gap: 0.6em;">
        <i class="fa-solid fa-grip-vertical" style="cursor: grab; color: #666;"></i>
        <span>the result of compilation</span>
      </div>
      <div style="display: flex; flex-direction: column; gap: 2px;">
        <i class="fa-solid fa-chevron-up" style="cursor: pointer; color: #777;"></i>
        <i class="fa-solid fa-chevron-down" style="cursor: pointer; color: #777;"></i>
      </div>
    </div>
  </div>

  <!-- Row 3 -->
  <div style="display: flex; gap: 1em;">
    <div style="flex: 1; border: 1px solid #ddd; border-radius: 8px; padding: 10px 14px;">
      Native code
    </div>
    <div style="flex: 1; border: 1px solid #ddd; border-radius: 8px; padding: 10px 14px; display: flex; justify-content: space-between; align-items: center;">
      <div style="display: flex; align-items: center; gap: 0.6em;">
        <i class="fa-solid fa-grip-vertical" style="cursor: grab; color: #666;"></i>
        <span>computers understand this code</span>
      </div>
      <div style="display: flex; flex-direction: column; gap: 2px;">
        <i class="fa-solid fa-chevron-up" style="cursor: pointer; color: #777;"></i>
        <i class="fa-solid fa-chevron-down" style="cursor: pointer; color: #777;"></i>
      </div>
    </div>
  </div>

</div>

**Đáp án:** 

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<div style="display: flex; flex-direction: column; gap: 1em; width: 700px;">

  <!-- Row 1 -->
  <div style="display: flex; gap: 1em;">
    <div style="flex: 1; border: 1px solid #ddd; border-radius: 8px; padding: 10px 14px;">
      Source code
    </div>
    <div style="flex: 1; border: 1px solid #ddd; border-radius: 8px; padding: 10px 14px; display: flex; justify-content: space-between; align-items: center;">
      <div style="display: flex; align-items: center; gap: 0.6em;">
        <i class="fa-solid fa-grip-vertical" style="cursor: grab; color: #666;"></i>
        <span>usually, developers write this code</span>
      </div>
      <div style="display: flex; flex-direction: column; gap: 2px;">
        <i class="fa-solid fa-chevron-up" style="cursor: pointer; color: #777;"></i>
        <i class="fa-solid fa-chevron-down" style="cursor: pointer; color: #777;"></i>
      </div>
    </div>
  </div>

  <!-- Row 2 -->
  <div style="display: flex; gap: 1em;">
    <div style="flex: 1; border: 1px solid #ddd; border-radius: 8px; padding: 10px 14px;">
      Bytecode
    </div>
    <div style="flex: 1; border: 1px solid #ddd; border-radius: 8px; padding: 10px 14px; display: flex; justify-content: space-between; align-items: center;">
      <div style="display: flex; align-items: center; gap: 0.6em;">
        <i class="fa-solid fa-grip-vertical" style="cursor: grab; color: #666;"></i>
        <span>the result of compilation</span>
      </div>
      <div style="display: flex; flex-direction: column; gap: 2px;">
        <i class="fa-solid fa-chevron-up" style="cursor: pointer; color: #777;"></i>
        <i class="fa-solid fa-chevron-down" style="cursor: pointer; color: #777;"></i>
      </div>
    </div>
  </div>

  <!-- Row 3 -->
  <div style="display: flex; gap: 1em;">
    <div style="flex: 1; border: 1px solid #ddd; border-radius: 8px; padding: 10px 14px;">
      Native code
    </div>
    <div style="flex: 1; border: 1px solid #ddd; border-radius: 8px; padding: 10px 14px; display: flex; justify-content: space-between; align-items: center;">
      <div style="display: flex; align-items: center; gap: 0.6em;">
        <i class="fa-solid fa-grip-vertical" style="cursor: grab; color: #666;"></i>
        <span>computers understand this code</span>
      </div>
      <div style="display: flex; flex-direction: column; gap: 2px;">
        <i class="fa-solid fa-chevron-up" style="cursor: pointer; color: #777;"></i>
        <i class="fa-solid fa-chevron-down" style="cursor: pointer; color: #777;"></i>
      </div>
    </div>
  </div>

</div>

## Ngôn ngữ JVM

Ngôn ngữ lập trình nào sau đây có thể chạy trên JVM?

**Câu hỏi:** Chọn một hoặc nhiều tùy chọn từ danh sách

- Groovy

- Scala

- Kotlin

- Java

**Đáp án:**

- Groovy

- Scala

- Kotlin

- Java
