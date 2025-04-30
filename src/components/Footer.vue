<template>
  <footer class="footer">
    <div class="footer-left">
      <img src="../footerImg/logo (4).png" alt="figma1" />
      <div class="left2">
        <p>© YouMeal, 2022</p>
        <p>Design: Anastasia Ilina</p>
      </div>
    </div>
    <div class="footer-righ">
      <div class="footer-1">
        <p>Номер для заказа</p>
        <p>+7(930)833-38-11</p>
      </div>
      <div class="footer-2">
        <p>Мы в соцсетях</p>
        <a
          href="https://vk.com/https://www.figma.com/design/1YJoWwU9ISwgtGy2pLNJYx/Bolalarni-birinchi-marta-shu-yerda-qilishgan-team-projecti-vuexda?node-id=1-222&t=n55Owfz8rvh7XII6-0"
          target="_blank"
        >
          <img src="../footerImg/wka.png" alt="VK Icon" />
        </a>
        <a href="https://t.me/@mukhtaroww" target="_blank">
          <img src="../footerImg/telagram.png" alt="Telegram Icon" />
        </a>
      </div>
    </div>
  </footer>
</template>
<script>
export default {};
</script>
<style scoped>
.footer-2 a {
  margin-right: 15px;
}
.footer-2 {
  padding-top: 30px;
  padding-left: 20px;
}

.footer-2 p {
  font-family: Nunito;
  font-weight: 400;
  font-size: 24px;
  line-height: 100%;
  padding-bottom: 22px;

  letter-spacing: 0%;
}
.left2 {
  padding-top: 55px;
}
.left2 p:nth-child(1) {
  font-family: Nunito;
  font-weight: 400;
  font-size: 15px;
  line-height: 100%;
  letter-spacing: 0%;
  color: #000000;
  padding-bottom: 4px;
}
.left2 p:nth-child(2) {
  font-family: Nunito;
  font-weight: 400;
  font-size: 15px;
  line-height: 100%;
  letter-spacing: 0%;
  color: #000000;
}
.footer-left img {
  width: 300px;
  height: 62px;
}
.footer-1 {
  padding-top: 20px;
}
.footer-1 p:nth-child(1) {
  font-family: Nunito;
  font-weight: 400;
  font-size: 30px;
  line-height: 100%;
  letter-spacing: 0%;
  padding-bottom: 24px;
  color: #000000;
}
.footer-1 p:nth-child(2) {
  font-family: Nunito;
  font-weight: 400;
  font-size: 18px;
  line-height: 130%;
  letter-spacing: 0%;
  color: #000000;
}
.footer-righ {
  display: flex;
  gap: 126px;
  padding-top: 50px;
}
.footer-left {
  padding-left: 85px;
  padding-top: 50px;
}
.footer {
  width: 100%;
  height: 245px;
  background: #ffffff;

  display: flex;
  gap: 385px;
  margin-top: 100px;
}

@media (max-width: 1300px) {
  .footer {
    gap: 200px;
  }
}

@media (max-width: 1024px) {
  .footer-left {
    padding-left: 32px;
  }
  .footer-righ {
    padding-left: 0;
    text-align: left;
  }

  .footer-righ {
    gap: 50px;
  }
}

@media (min-width: 950px) {
  .footer {
    justify-content: center;
    align-content: center;
    gap: 150px;
  }
}
@media (max-width: 868px) {
  .footer {
    margin: auto;
    display: grid;
    grid-template-columns: 1fr;
    justify-items: center;
    text-align: center;
    justify-content: center;
    gap: 0px;
  }
}

@media (max-width: 320px) {
}
</style>
