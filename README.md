# README

```html
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>自己紹介ページ</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #121212;
      color: #fff;
    }

    /* コンテナ */
    .container {
      position: relative;
      width: 100%;
      max-width: 800px;
      margin: 0 auto;
      border-radius: 10px;
      overflow: hidden;
    }

    /* 背景画像（ズームアニメーション） */
    .container img {
      width: 100%;
      display: block;
      transform: scale(1);
      animation: zoomIn 15s ease-in-out infinite alternate;
    }

    /* ズームするアニメーション */
    @keyframes zoomIn {
      0% { transform: scale(1); }
      100% { transform: scale(1.1); }
    }

    /* 文字ボックス（ふわっと表示アニメーション） */
    .overlay {
      position: absolute;
      top: 20%;
      left: 10%;
      right: 10%;
      background-color: rgba(0, 0, 0, 0.6);
      color: white;
      padding: 25px;
      border-radius: 10px;
      box-sizing: border-box;
      line-height: 1.6;
      opacity: 0;
      transform: translateY(20px);
      animation: fadeInUp 1.5s ease-out forwards;
      animation-delay: 0.5s;
    }

    /* フェードイン＆スライドアップ */
    @keyframes fadeInUp {
      0% {
        opacity: 0;
        transform: translateY(20px);
      }
      100% {
        opacity: 1;
        transform: translateY(0);
      }
    }

    h2, h3 {
      margin-top: 0;
    }

    a {
      color: #00ccff;
      text-decoration: none;
      transition: color 0.3s ease;
    }

    a:hover {
      color: #66e0ff;
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- 背景画像 -->
    <img src="https://raw.githubusercontent.com/Re1-2973/aaa/refs/heads/main/image0.jpg" alt="背景画像">

    <!-- 文字を重ねるボックス -->
    <div class="overlay">
      <h2>🌙 自己紹介</h2>
      <p>ぱろー！れいって呼んでください。<br>誕生日は6/25で、MBTIはENFPです。</p>

      <h3>📜 プロフィール</h3>
      <p>好きなものはゲーム、音楽、運動、料理！</p>

      <h3>🎮 お気に入りのゲーム</h3>
      <ol>
        <li>Roblox</li>
        <li>Muse Dash</li>
        <li>UNDERTALE</li>
        <li>Mo4</li>
      </ol>

      <h3>🎨 将来やりたいこと</h3>
      <p>継続が苦手な自分だけど、音楽やイラストを上手に描けるようになりたいです。</p>

      <h3>🔗 その他リンク</h3>
      <ul>
        <li><strong>GitHub:</strong> <a href="https://github.com/Re1-2973">こちら</a></li>
        <li><strong>TikTok:</strong> <a href="https://www.tiktok.com/@tds7352">こちら</a></li>
        <li><strong>Spotify:</strong> <a href="https://open.spotify.com/user/31bvmul6z53xh5fg7vflkhwz3tpy">こちら</a></li>
        <li><strong>Roblox:</strong> <a href="https://www.roblox.com/share?code=79d3945060">こちら</a></li>
      </ul>
    </div>
  </div>
</body>
</html>
```
