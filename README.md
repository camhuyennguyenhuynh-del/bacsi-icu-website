<!doctype html>
<html lang="vi">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Bác sĩ Hồi sức Cấp cứu | Website giới thiệu</title>
  <style>
    body{font-family:Arial,Helvetica,sans-serif;margin:0;line-height:1.6;color:#0f172a;background:#f8fafc}
    header{background:#0b2a4a;color:#fff;padding:28px 16px}
    .wrap{max-width:980px;margin:0 auto;padding:0 16px}
    .hero{display:flex;gap:18px;align-items:center;flex-wrap:wrap}
    .avatar{width:110px;height:110px;border-radius:18px;background:#ffffff22;display:flex;align-items:center;justify-content:center;font-size:36px}
    .btns a{display:inline-block;margin:10px 10px 0 0;padding:10px 14px;border-radius:12px;text-decoration:none}
    .primary{background:#22c55e;color:#052e16}
    .secondary{background:#fff;color:#0b2a4a}
    section{padding:24px 0}
    .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:12px}
    .card{background:#fff;border-radius:16px;padding:14px;border:1px solid #e2e8f0}
    .small{color:#475569;font-size:14px}
    footer{padding:18px 0;border-top:1px solid #e2e8f0;color:#475569}
    @media (max-width:800px){.grid{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <header>
    <div class="wrap hero">
      <div class="avatar">BS</div>
      <div>
        <h1 style="margin:0 0 6px">BS. [Họ tên] — Hồi sức Cấp cứu (ICU)</h1>
        <div class="small">Tư vấn chuyên môn • Hỗ trợ theo dõi bệnh nhân nặng • Hướng dẫn xử trí tình huống cấp cứu</div>
        <div class="btns">
          <a class="primary" href="tel:+84XXXXXXXXX">Gọi ngay</a>
          <a class="secondary" href="https://zalo.me/XXXXXXXXXX" target="_blank" rel="noopener">Zalo</a>
        </div>
      </div>
    </div>
  </header>

  <main class="wrap">
    <section>
      <h2>Giới thiệu</h2>
      <p>
        Tôi là bác sĩ chuyên khoa Hồi sức Cấp cứu, kinh nghiệm [X] năm trong hồi sức bệnh nhân nặng.
        Thế mạnh: đánh giá nguy cơ, lập kế hoạch theo dõi sau ICU, tư vấn xử trí cấp cứu ban đầu.
      </p>
      <div class="grid">
        <div class="card"><b>Chuyên môn</b><div class="small">ICU • Cấp cứu • Hồi sức</div></div>
        <div class="card"><b>Kinh nghiệm</b><div class="small">[X] năm • [BV/Đơn vị]</div></div>
        <div class="card"><b>Chứng chỉ</b><div class="small">BLS/ACLS • [khác]</div></div>
      </div>
    </section>

    <section>
      <h2>Dịch vụ</h2>
      <div class="grid">
        <div class="card">
          <b>Tư vấn hồi sức từ xa</b>
          <div class="small">Đánh giá tình trạng, hướng dẫn theo dõi, cảnh báo dấu hiệu nặng.</div>
        </div>
        <div class="card">
          <b>Theo dõi sau ICU</b>
          <div class="small">Kế hoạch thuốc, dinh dưỡng, phục hồi, tái khám.</div>
        </div>
        <div class="card">
          <b>Đào tạo sơ cấp cứu</b>
          <div class="small">Hướng dẫn gia đình/nhân sự: CPR, xử trí sốc phản vệ, đột quỵ.</div>
        </div>
      </div>
    </section>

    <section>
      <h2>Bài viết kiến thức</h2>
      <div class="card">
        <ul style="margin:8px 0 0">
          <li>Dấu hiệu nguy hiểm cần đi cấp cứu ngay</li>
          <li>Cách nhận biết sốc phản vệ</li>
          <li>Chăm sóc bệnh nhân sau thở máy</li>
        </ul>
      </div>
    </section>

    <section>
      <h2>Liên hệ</h2>
      <div class="card">
        <div><b>Hotline:</b> <a href="tel:+84XXXXXXXXX">+84 XXXXXXXX</a></div>
        <div><b>Zalo:</b> <a href="https://zalo.me/XXXXXXXXXX" target="_blank" rel="noopener">Chat Zalo</a></div>
        <div><b>Email:</b> <a href="mailto:emailcuaban@gmail.com">emailcuaban@gmail.com</a></div>
        <div class="small" style="margin-top:8px">*Nội dung chỉ mang tính tư vấn, trường hợp khẩn cấp vui lòng gọi cấp cứu địa phương.</div>
      </div>
    </section>

    <footer class="wrap">
      © <span id="y"></span> BS. [Họ tên]. All rights reserved.
    </footer>
  </main>

  <script>
    document.getElementById("y").textContent = new Date().getFullYear();
  </script>
</body>
</html>
