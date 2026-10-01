<!DOCTYPE html>
<html lang="th">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>01 • หน้าปก | Portfolio By Siriwan</title>

  <link href="https://fonts.googleapis.com/css2?family=Kanit:wght@300;400;500;600;700&display=swap" rel="stylesheet">

  <style>
    /* ✨ เอฟเฟกต์แบบแอป */
    a {
      transition: transform 0.18s ease, box-shadow 0.18s ease;
    }

    a:hover {
      transform: translateY(-3px);
    }

    a:active {
      transform: scale(0.93);
    }

    img {
      transition: transform 0.2s ease;
    }

    img:active {
      transform: scale(0.97);
    }

    /* 📱 มือถือ */
    @media (hover: none) {
      a:hover {
        transform: none;
      }

      a:active {
        transform: scale(0.93);
      }
    }
  </style>

</head>

<body style="
  margin:0;
  padding:0;
  font-family:'Kanit',sans-serif;
  background:#FFFDE7;
  color:#301050;
">

<div style="
  padding:40px 20px;
  text-align:center;
">

  <div style="
    max-width:900px;
    margin:0 auto;
    width:100%;
  ">

    <!-- เมนู -->
    <div style="
      background:#ffffff;
      padding:14px 20px;
      border-radius:50px;
      display:inline-flex;
      align-items:center;
      justify-content:center;
      flex-wrap:wrap;
      gap:8px;
      box-shadow:0 10px 30px rgba(48,16,80,0.1);
      margin-bottom:30px;
      border:2px solid #FFF59D;
      max-width:95%;
    ">

      <a href="./index.html"
         style="
           color:#4C1D95;
           text-decoration:none;
           font-weight:700;
           font-size:0.85rem;
         ">
        🏠 หน้าหลัก
      </a>

      <span style="color:#ddd;">|</span>

      <a href="./ปก.html"
         style="
           color:#FDE047;
           background:#301050;
           padding:4px 10px;
           border-radius:20px;
           text-decoration:none;
           font-weight:600;
           font-size:0.85rem;
         ">
        01 ปก
      </a>

      <span style="color:#ddd;">|</span>

      <a href="./sop.html"
         style="
           color:#301050;
           text-decoration:none;
           font-weight:600;
           font-size:0.85rem;
         ">
        02 SOP
      </a>

      <span style="color:#ddd;">|</span>

      <a href="./ประวัติส่วนตัว.html"
         style="
           color:#301050;
           text-decoration:none;
           font-weight:600;
           font-size:0.85rem;
         ">
        03 ประวัติส่วนตัว
      </a>

      <span style="color:#ddd;">|</span>

      <a href="./ประวัติการศึกษา.html"
         style="
           color:#301050;
           text-decoration:none;
           font-weight:600;
           font-size:0.85rem;
         ">
        04 ประวัติการศึกษา
      </a>

      <span style="color:#ddd;">|</span>

      <a href="./กิจกรรมที่ภาคภูมิใจ.html"
         style="
           color:#301050;
           text-decoration:none;
           font-weight:600;
           font-size:0.85rem;
         ">
        05 ผลงาน
      </a>

      <span style="color:#ddd;">|</span>

      <a href="./กิจกรรมเข้าร่วม.html"
         style="
           color:#301050;
           text-decoration:none;
           font-weight:600;
           font-size:0.85rem;
         ">
        06 กิจกรรม
      </a>

      <span style="color:#ddd;">|</span>

      <a href="./ปกหลัง.html"
         style="
           color:#301050;
           text-decoration:none;
           font-weight:600;
           font-size:0.85rem;
         ">
        07 ปกหลัง
      </a>

    </div>


    <!-- หน้าปก -->
    <div style="
      background:#ffffff;
      border-radius:28px;
      padding:40px;
      box-shadow:0 10px 30px rgba(48,16,80,0.06);
      border:2px solid #FFE082;
      text-align:center;
    ">

      <h1 style="
        color:#301050;
        font-size:2rem;
        margin:0 0 20px;
      ">
        01 • หน้าปก (Cover)
      </h1>


      <!-- รูปหน้าปก -->
      <img
        src="./1.png"
        width="100%"
        style="
          border-radius:16px;
          box-shadow:0 8px 25px rgba(0,0,0,0.15);
          display:block;
        "
        alt="Portfolio Cover"
      >


      <br><br>


      <!-- กลับหน้าหลัก -->
      <a
        href="./index.html"
        style="
          background:#301050;
          color:#FFFFFF;
          padding:10px 24px;
          border-radius:25px;
          text-decoration:none;
          font-size:14px;
          font-weight:600;
          display:inline-block;
        ">
        ⬅ กลับสู่หน้าหลัก
      </a>

    </div>

  </div>

</div>

</body>
</html>
