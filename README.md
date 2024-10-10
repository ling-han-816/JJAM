<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body { 
      font-family: Arial, sans-serif; 
      background: linear-gradient(to right, #444444, #888888); /* 加入漸層背景 */
      color: #888;
      margin: 0; /* 移除預設邊距 */
      height: 100vh; /* 設置頁面高度 */
      overflow: hidden; /* 隱藏滾動條 */
      transition: background 0.5s ease; /* 平滑背景轉換 */ 
    }

    /* 主要容器 */
    .main-container {
      display: flex;
      flex-direction: column; /* 垂直排列 */
      align-items: center; /* 水平置中 */
      margin: 20px; /* 外邊距 */
      height: 70%; /* 讓容器也填滿頁面 */
      justify-content: center;
    }

    /* 音樂播放器容器 */
    .audio-container {
      margin: 10px 0; /* 縮小上下邊距 */
    }

    /* 照片容器 */
    .photo-container {
      display: flex;
      justify-content: center;
      margin: 10px 0; /* 縮小上下邊距 */
    }

    /* 歌名和團名 */
    .song-info {
      font-size: 20px; /* 字體大小 */
      color: #222; /* 字體顏色 */
      margin: 4px 0; /* 調整間距 */
      text-align: center; /* 文字置中 */
      font-weight: bold; /* 設置為粗體 */
    }

    /* 歌詞容器 */
    .lyrics-container {
      margin: 20px auto;
      height: 165px;
      width: 80%;
      overflow-y: scroll;
      text-align: center;
    }

    .lyrics-container::-webkit-scrollbar {
      display: none; /* 隱藏滾動條 */
    }

    .lyrics-container {
      scrollbar-width: none; /* 隱藏 Firefox 的滾動條 */
    }

    .lyrics p {
      margin: 5px 0;
      font-size: 18px;
      line-height: 1.5;
      color: #888;
    }

    .lyrics p.active {
      color: #fff;
      font-weight: bold;
    }

    /* 照片樣式 */
    .photo {
      width: 100%; /* 照片寬度，根據需要調整 */
      border-radius: 10px; /* 圓角邊框，根據需要調整 */
    }

    /* 背景上傳按鈕樣式 */
    .upload-container {
      margin-top: 20px;
      text-align: center;
    }
  </style>
  <title>Stray Kids_JJAM</title>
</head>
<body>
  <div class="main-container">
    <!-- 添加圖片 -->
    <div class="photo-container">
      <img src="https://upload.wikimedia.org/wikipedia/zh/5/56/Stray_Kids_-_Ate.JPG" alt="Song Image" class="photo"> <!-- 在這裡替換成你的圖片路徑 -->
    </div>

    <!-- 歌名和團名 -->
    <div class="song-info">JJAM - Stray Kids</div>
    
    <!-- 第一首歌 -->
    <div class="audio-container">
      <audio id="audio2" controls>
        <source src="jjam.mp3" type="audio/mp3"> <!-- 第一首歌音檔 -->
      </audio>
    </div>
    
    <!-- 歌詞顯示區域 -->
    <div class="lyrics-container" id="lyrics-container2">
      <div class="lyrics" id="lyrics2">
        <p data-time="5.9">재미 좀 볼 때 발라 버려 honey jam ayy</p>
        <p data-time="8.7">Finger lickin' yeah 실컷 찍어라 직캠</p>
        <p data-time="11">다채로움을 모아 새로 조화롭게</p>
        <p data-time="13.8">자 찬란한 목소리 현란한 춤사위 모여 같이 jam jam</p>
        <p data-time="17">오늘의 topic 걍 잼있게 놀기</p>
        <p data-time="19.9">이 음악도 솔깃해 you can't stop it</p>
        <p data-time="22.8">굵직한 bass line에 맞춰 body shake</p>
        <p data-time="25.2">그래 okay 컷 바라던 대로 take</p>
        <p data-time="27.9">Come and join the crew get closer now</p>
        <p data-time="30.2">It's time to make a move get lit so loud</p>
        <p data-time="33.2">We know we'll never lose get trophies now</p>
        <p data-time="36">숨겨둔 흥을 터트려 시선들은 멈춰 yeah</p>
        <p data-time="39.7">Peanut butter jelly time</p>
        <p data-time="42">We stick together day and night, yeah</p>
        <p data-time="45.2">Fill up our jars every time</p>
        <p data-time="47.5">Just spread it out ~ ~</p>
        <p data-time="52.7">찍어 발라 버려 jam</p>
        <p data-time="55.3">Sticky sticky sticky jam</p>
        <p data-time="58.1">yeah our jam got them</p>
        <p data-time="59.8">I got no 잼</p>
        <p data-time="60.4">You got no 잼</p>
        <p data-time="61.1">We gotta jam (촵촵)</p>
        <p data-time="62.5">Look at our jam come on and 도리도리 잼잼</p>
        <p data-time="65">Stick it up now put your put your hands up (ooh)</p>
        <p data-time="68.2">It's our playground 북적북적해져 (ah)</p>
        <p data-time="70.9">재미재미져 재미재미 catch up</p>
        <p data-time="73.9">Look at our jam come on and 도리도리 잼잼 (sing)</p>
        <p data-time="76.5">Come on 억눌러 봤자 불필요</p>
        <p data-time="79.6">버려 고민들 털고 움직여</p>
        <p data-time="82.4">꽉 막힌 road just take it slow</p>
        <p data-time="85.1">여긴 언제나 open our home</p>
        <p data-time="87.7">붉은 headlights 속에서</p>
        <p data-time="90.4">불러 힘껏 sing this song</p>
        <p data-time="93.5">No one can escape this feeling</p>
        <p data-time="96">빠질 수 없어 (dance)</p>
        <p data-time="101.4">I gotta move look at my groove</p>
        <p data-time="107">Jam jam jam jam</p>
        <p data-time="109.8">Say whoa ~ (ha)</p>
        <p data-time="115.4">say ooh</p>
        <p data-time="119.1">I know you know Lee Know (rap)</p>
        <p data-time="121.7">Kick snare hi-hat drum and bass</p>
        <p data-time="123">환상적 케미 peanut butter jelly</p>
        <p data-time="124.7">개나 소나 쟤나 걔나 얘나 다</p>
        <p data-time="125.8">불러와 재미 보고 흥미를 take it</p>
        <p data-time="127.3">움츠러들 필요 따윈 없지</p>
        <p data-time="128.7">필요한 건 오로지 패기와 객기</p>
        <p data-time="130.2">재빠른 재치 catch</p>
        <p data-time="130.8">노잼 allergy 기침 재채기 에취</p>
        <p data-time="132.9">Sticking together day and night yeah</p>
        <p data-time="135.7">Filling up jars oh every time</p>
        <p data-time="138">So just spread it out ~ (right now)</p>
        <p data-time="143">찍어 발라 버려 jam</p>
        <p data-time="145.9">Sticky sticky sticky jam</p>
        <p data-time="148.7">yeah our jam got them</p>
        <p data-time="149.9">I got no 잼</p>
        <p data-time="150.8">You got no 잼</p>
        <p data-time="151.5">We gotta jam (촵촵)</p>
        <p data-time="152.9">Look at our jam come on and 도리도리 잼잼</p>
        <p data-time="155.8">Everybody every everybody-body jam(Jam)</p>
        <p data-time="169.3">Stick it up now put your put your hands up (Yeah)</p>
        <p data-time="172.8">It's our playground 북적북적해져</p>
        <p data-time="175.5">재미재미져 재미재미 catch up</p>
        <p data-time="178.1">Look at our jam come on and 도리도리 잼잼 (Jam Jam)</p>
      </div>
    </div>

    <!-- 背景圖片上傳 -->
    <div class="upload-container">
      <label for="bgUpload">可以自訂背景呦</label>
      <input type="file" id="bgUpload" accept="image/*">
    </div>
  </div>

<script>
    // 背景上傳處理邏輯
    const bgUpload = document.getElementById('bgUpload');
    bgUpload.addEventListener('change', function (event) {
      const file = event.target.files[0];
      if (file) {
        const reader = new FileReader();
        reader.onload = function (e) {
          document.body.style.backgroundImage = `url(${e.target.result})`;
          document.body.style.backgroundSize = 'cover';  // 背景圖片覆蓋整個頁面
          document.body.style.backgroundPosition = 'center';  // 圖片置中
          document.body.style.backgroundRepeat = 'no-repeat';  // 圖片不重複
        };
        reader.readAsDataURL(file); // 讀取上傳的圖片
      }
    });

    // 歌詞同步功能
    function syncLyrics(audio, lyricsElement, containerElement) {
      const lyrics = lyricsElement.getElementsByTagName('p');
      
      audio.addEventListener('timeupdate', () => {
        for (let i = 0; i < lyrics.length; i++) {
          const time = parseFloat(lyrics[i].getAttribute('data-time'));
          const nextTime = lyrics[i + 1] ? parseFloat(lyrics[i + 1].getAttribute('data-time')) : Infinity;

          if (audio.currentTime >= time && audio.currentTime < nextTime) {
            lyrics[i].classList.add('active'); // 當前歌詞變為活躍
            lyrics[i].scrollIntoView({ behavior: 'smooth', block: 'center' }); // 自動滾動並將當前歌詞居中
          } else {
            lyrics[i].classList.remove('active');
          }
        }
      });
    }

    // 對每首歌進行歌詞同步
    const audio2 = document.getElementById('audio2');
    const lyrics2 = document.getElementById('lyrics2');
    const container2 = document.getElementById('lyrics-container2');
    syncLyrics(audio2, lyrics2, container2);
  </script>

</body>
</html>
