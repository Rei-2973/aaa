# README

```html
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>れいのプロフィール</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      color: white;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: #000;
      overflow: hidden;
    }

    /* 背景画像 */
    .background {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      object-fit: cover;
      z-index: -1;
      animation: zoom 20s ease-in-out infinite alternate;
    }

    @keyframes zoom {
      0% { transform: scale(1); }
      100% { transform: scale(1.1); }
    }

    /* 文字ボックス */
    .profile-box {
      background-color: rgba(0, 0, 0, 0.6);
      padding: 20px;
      border-radius: 12px;
      max-width: 700px;
      width: 90%;
      animation: fadeIn 1.5s ease-out;
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    h2 {
      margin: 15px 0 8px;
      font-size: 1.4rem;
    }

    p, li, a {
      font-size: 1rem;
      line-height: 1.6;
    }

    a {
      color: #00ccff;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
      color: #66e0ff;
    }

    ol, ul {
      margin-left: 20px;
      margin-bottom: 15px;
    }

    /* スマホ対応 */
    @media (max-width: 600px) {
      h2 {
        font-size: 1.2rem;
      }
      p, li, a {
        font-size: 0.9rem;
      }
    }
  </style>
</head>
<body>
  <!-- 背景画像 -->
  <img class="background" src="https://raw.githubusercontent.com/Rei-2973/aaa/refs/heads/main/image0.jpg" alt="背景画像">

  <!-- プロフィールボックス -->
  <div class="profile-box">
    <h2>👋 自己紹介</h2>
    <p>はろー！れいって呼んでください</p>

    <h2>🧑‍💼 プロフィール</h2>
    <p>好きなもの？はゲーム、音楽、運動 ｜誕生日は6/25で、MBTIはENFPです</p>

    <h2>🎮 お気に入りのゲーム</h2>
    <ol>
      <li>Roblox</li>
      <li>Muse Dash</li>
      <li>UNDERTALE</li>
      <li>Mo4</li>
    </ol>

    <h2>🚀 将来やりたいこと</h2>
    <p>継続するのが苦手な自分だけど、音楽とかイラストを上手に描ければいいなーっておもってます</p>

    <h2>🔗 その他リンク</h2>
    <ul>
      <li><strong>GitHub:</strong> <a href="https://github.com/Rei-2973">https://github.com/Rei-2973</a></li>
      <li><strong>TikTok:</strong> <a href="https://www.tiktok.com/@tds7352">@tds7352</a></li>
      <li><strong>Spotify:</strong> <a href="https://open.spotify.com/user/317bwulsz633xbnjpeyedrbbs73a?si=a9ue8qooSRar0dedjqYxJw">Spotify プロフィール</a></li>
      <li><strong>Roblox:</strong> <a href="https://www.roblox.com/share?code=79d394580f3e6046b9e76a8156b38e4f&type=Profile&source=ProfileShare&stamp=1752754583723">Roblox プロフィール</a></li>
    </ul>
  </div>
</body>
</html>
```
