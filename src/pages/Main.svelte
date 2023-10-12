<script>
  let hour = new Date().getHours();
  let min = new Date().getMinutes();

  setInterval(() => (min = min + 1), 1000);
</script>

<header>
  <div class="info-bar">
    <div class="info-bar__time">{hour}:{min}</div>
    <div class="info-bar__icons">
      <img src="assets/chart-bar.svg" alt="chart-bar" />
      <img src="assets/wifi.svg" alt="wifi-bar" />
      <img src="assets/battery.svg" alt="battery-bar" />
    </div>
  </div>
  <div class="menu-bar">
    <div class="menu-bar__location">
      <div>중1동</div>
      <div class="menu-bar__location-icon">
        <img src="assets/arrow.svg" alt="arrow" />
      </div>
    </div>
    <div class="menu-bar__icons">
      <img src="assets/search.svg" alt="searcj" />
      <img src="assets/hamburger.svg" alt="hamburger" />
      <img src="assets/bell.svg" alt="bell" />
    </div>
  </div>
</header>

<main>
  <a class="write-button" href="#/write">+글쓰기</a>
</main>

<footer>
  <div class="footer-block">
    <div class="footer-icons">
      <div class="footer-icons__img">
        <img src="assets/home.svg" alt="" />
      </div>
      <div class="footer-icons__font">홈</div>
    </div>
    <div class="footer-icons">
      <div class="footer-icons__img">
        <img src="assets/paper.svg" alt="" />
      </div>
      <div class="footer-icons__font">동네생활</div>
    </div>
    <div class="footer-icons">
      <div class="footer-icons__img">
        <img src="assets/location.svg" alt="" />
      </div>
      <div class="footer-icons__font">내근처</div>
    </div>
    <div class="footer-icons">
      <div class="footer-icons__img">
        <img src="assets/chat.svg" alt="" />
      </div>
      <div class="footer-icons__font">채팅</div>
    </div>
    <div class="footer-icons">
      <div class="footer-icons__img">
        <img src="assets/user.svg" alt="" />
      </div>
      <div class="footer-icons__font">나의 당근</div>
    </div>
  </div>
</footer>
<div class="media-info-msg">화면 사이즈를 줄여주세요.</div>
