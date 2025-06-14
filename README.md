<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>One UI 7 WebOS</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div id="wallpaper"></div>  <!-- Dock -->  <div class="dock">
    <button onclick="openApp('settings')">⚙️</button>
    <button onclick="openApp('goodlock')">🧩</button>
  </div>  <!-- Settings App -->  <div class="app-window" id="settings">
    <div class="app-header">
      <span>Settings</span>
      <button onclick="closeApp('settings')">✖️</button>
    </div>
    <div class="app-body">
      <h3>Wallpaper</h3>
      <button onclick="setWallpaper('bg1.jpg')">Wallpaper 1</button>
      <button onclick="setWallpaper('bg2.jpg')">Wallpaper 2</button><h3>TikTok</h3>
  <a href="https://www.tiktok.com/@x.qto" target="_blank">@x.qto</a>
</div>

  </div>  <!-- Good Lock App -->  <div class="app-window" id="goodlock">
    <div class="app-header">
      <span>Good Lock</span>
      <button onclick="closeApp('goodlock')">✖️</button>
    </div>
    <div class="app-body">
      <p>Fake Good Lock modules coming soon!</p>
    </div>
  </div>  <script src="script.js"></script></body>
</html>
