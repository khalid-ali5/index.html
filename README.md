<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Safe Vision Dashboard</title>
  <style>
    body { font-family: Arial, sans-serif; margin:0; background:#f5f7fa; }
    .alert { background:red; color:white; padding:15px; font-size:18px; text-align:center; font-weight:bold; }
    .map { text-align:center; margin:20px; }
    .map img { width:90%; border-radius:12px; }
    .buttons { display:flex; justify-content:center; gap:20px; margin:20px; }
    .buttons button { padding:15px 25px; border:none; border-radius:8px; font-size:16px; cursor:pointer; color:white; }
    .green { background:green; }
    .blue { background:blue; }
    .navbar { position:fixed; bottom:0; width:100%; background:#fff; display:flex; justify-content:space-around; border-top:1px solid #ccc; padding:10px 0; }
    .navbar div { text-align:center; font-size:14px; color:#333; }
  </style>
</head>
<body>
  <div class="alert">🚨 حالة إغماء — الساحة الشمالية — 2:15 م</div>

  <div class="map">
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/f8/Mecca_from_Satellite.jpg" alt="خريطة مكة">
  </div>

  <div class="buttons">
    <button class="green">✅ أنا بالطريق</button>
    <button class="blue">🆘 طلب دعم</button>
  </div>

  <div class="navbar">
    <div>🏠 الرئيسية</div>
    <div>🔔 التنبيهات</div>
    <div>📝 المهام</div>
    <div>👤 الملف</div>
  </div>
</body>
</html>
