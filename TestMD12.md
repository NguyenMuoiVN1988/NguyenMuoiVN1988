<!-- Bắt đầu phần CSS để tạo layout 2 cột -->
<style>
  /* Định nghĩa một container chính sử dụng Flexbox */
  .container-2-column {
    display: flex; /* Kích hoạt layout Flexbox để các mục con nằm ngang */
    flex-wrap: wrap; /* Cho phép các cột xuống dòng nếu màn hình quá hẹp */
    gap: 30px; /* Tạo khoảng trống 30px giữa hai cột */
  }

  /* Định nghĩa cho mỗi cột */
  .column {
    flex: 1; /* Giúp mỗi cột linh hoạt co giãn và chiếm không gian bằng nhau */
    min-width: 300px; /* Chiều rộng tối thiểu cho mỗi cột trước khi xuống dòng */
  }

  /* Tùy chỉnh riêng cho cột form để iframe vừa vặn */
  .column-form iframe {
    width: 100%; /* Chiều rộng của form bằng 100% cột chứa nó */
    height: 80vh; /* Chiều cao bằng 80% chiều cao màn hình, bạn có thể điều chỉnh */
    border: 1px solid #ccc; /* Thêm một đường viền mảnh cho đẹp */
    border-radius: 5px; /* Bo góc cho mềm mại */
  }

  /* CSS cho tiêu đề */
  h2 {
    border-bottom: 2px solid #eee;
    padding-bottom: 10px;
  }
</style>

# BÀI KIỂM TRA NHANH MÔN TOÁN

Đây là bài kiểm tra nhanh gồm 5 câu hỏi trắc nghiệm để ôn tập kiến thức toán học cơ bản. Hãy đọc kỹ đề bài ở cột bên trái và điền câu trả lời vào biểu mẫu ở cột bên phải.

---

<!-- Bắt đầu phần HTML chứa layout 2 cột -->
<div class="container-2-column">

  <!-- CỘT 1: CHỨA CÂU HỎI -->
  <div class="column column-questions">
    <h2>Phần Đề Bài</h2>
    
    <p><strong>Câu 1: Kết quả của phép tính $15 + 5 \times 2$ là bao nhiêu?</strong></p>
    <ul>
      <li>A. 40</li>
      <li>B. 25</li>
      <li>C. 22</li>
      <li>D. 35</li>
    </ul>

    <p>Câu 2: Tìm giá trị của <code>x</code> trong phương trình: $3x - 7 = 11$</p>
    <ul>
      <li>A. x = 4</li>
      <li>B. x = 5</li>
      <li>C. x = 6</li>
      <li>D. x = 7</li>
    </ul>

    <p><strong>Câu 3: Một hình chữ nhật có chiều dài 12cm và chiều rộng 5cm. Chu vi của hình chữ nhật đó là bao nhiêu?</strong></p>
    <ul>
      <li>A. 17 cm</li>
      <li>B. 34 cm</li>
      <li>C. 60 cm</li>
      <li>D. 29 cm</li>
    </ul>
    
    <p><strong>Câu 4: Số nào sau đây là số nguyên tố?</strong></p>
    <ul>
      <li>A. 9</li>
      <li>B. 15</li>
      <li>C. 21</li>
      <li>D. 13</li>
    </ul>

    <p><strong>Câu 5: Chuyển phân số <code>3/4</code> thành số thập phân.</strong></p>
    <ul>
      <li>A. 0.25</li>
      <li>B. 0.5</li>
      <li>C. 0.75</li>
      <li>D. 1.33</li>
    </ul>
  </div>

  <!-- CỘT 2: CHỨA GOOGLE FORM -->
  <div class="column column-form">
    <h2>Phiếu Trả Lời</h2>

    <!-- DÁN MÃ NHÚNG IFRAME CỦA GOOGLE FORM CỦA BẠN VÀO ĐÂY -->
    <!-- Hãy chắc chắn bạn lấy mã từ tab "< > Nhúng HTML" của Google Form -->
   <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSe_hk1f6EBksdztDrfzBN-R2MYEcpcn5CmtY1O9OyrkcMcwTQ/viewform?embedded=true" width="640" height="1729" frameborder="0" marginheight="0" marginwidth="0">Đang tải…</iframe>

  </div>

</div>
