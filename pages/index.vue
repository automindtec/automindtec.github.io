<template>
  <div>
    <header>
      <nav>
        <ul>
          <li><a href="/">首頁</a></li>
          <li><a href="/home">產品介紹</a></li>
          <li><a href="/contactus">聯絡我們</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <section>
        <div>
          <h1>最專業的客製化藥局系統</h1>
          <p>你想得到的，我們幫你實現。</p>
          <button>立即諮詢</button>
        </div>
        <div>
          <img src="path/to/laptop-image.png" alt="Laptop with system interface">
        </div>
      </section>
    </main>
    <footer>
      <button @click="scrollToSection('service-features')">服務特色</button>
      <button @click="scrollToSection('service-process')">諮詢流程</button>
      <button>系統安全</button>
      <button>價格一覽</button>
      <button>免費服務</button>
    </footer>
    <section id="service-features">
      <h2>服務特色</h2>
      <p>貼心即時的服務 x 專業前沿的技術</p>
      <div>
        <div>
          <h3>直覺操作</h3>
          <p>無痛轉換最新規格</p>
          <p>定期提升使用者體驗 享受無痛升級新技術</p>
        </div>
        <div>
          <h3>快速專業</h3>
          <p>貼心快捷的諮詢管道</p>
          <p>遇到產品任何大小問題 專人在線即時為您處理</p>
        </div>
        <div>
          <h3>透明價格</h3>
          <p>公開合理的價格</p>
          <p>數位化系統定期升級 承諾不收取額外費用</p>
        </div>
        <div>
          <h3>簡潔介面</h3>
          <p>資料顯示好清楚</p>
          <p>調劑系統實現減法美學 藥師們不必再用眼過度</p>
        </div>
      </div>
    </section>
    <section id="service-process">
      <h2>服務流程</h2>
      <p>一站式解決藥局系統安裝大小事</p>
      <div>
        <div>
          <h3>產品安裝與試用</h3>
          <p>簡單快速的安裝過程</p>
          <p>提供核心功能的試用版本</p>
          <p>客服協助安裝與基本操作</p>
        </div>
        <div>
          <h3>功能設定與調整</h3>
          <p>根據業務需求客製化系統</p>
          <p>一鍵設置減少成本</p>
          <p>快速介紹與更新系統</p>
        </div>
        <div>
          <h3>資料無痛遷移</h3>
          <p>提供資料遷移工具支援系統資料匯入</p>
          <p>專業團隊確保資料完整與安全</p>
          <p>減少手動輸入節省時間與成本</p>
        </div>
        <div>
          <h3>用戶試用回饋與客製調整</h3>
          <p>試用期間收集用戶回饋進行調整</p>
          <p>確保系統符合用戶需求減少初期適應成本</p>
          <p>達到最佳工作流程</p>
        </div>
        <div>
          <h3>正式啟用與支援</h3>
          <p>提供正式啟用指導快速過渡</p>
          <p>提供技術支援確保順利使用</p>
          <p>持續更新與培訓提升效率</p>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  methods: {
    scrollToSection(sectionId) {
      const section = document.getElementById(sectionId);
      if (section) {
        section.scrollIntoView({ behavior: 'smooth' });
      }
    }
  }
}
</script>

<style>
header nav {
  display: flex;
  justify-content: center;
  padding: 15px 0;
}
header nav ul {
  display: flex;
  list-style: none;
  margin: 0;
  padding: 0;
}
header nav ul li {
  margin-right: 20px;
}
header nav ul li:last-child {
  margin-right: 0;
}
header nav ul li a {
  color: #333;
  font-size: 18px;
  font-weight: 500;
  padding: 8px 15px;
  text-decoration: none;
  transition: all 0.3s ease;
}
header nav ul li a:hover {
  background-color: #f8f9fa;
  border-radius: 4px;
  color: #007bff;
}
main {
  display: flex;
  justify-content: space-between;
  padding: 50px;
}
main section div:first-child {
  max-width: 50%;
}
main section div:first-child h1 {
  font-size: 36px;
  font-weight: bold;
}
main section div:first-child p {
  font-size: 18px;
  margin: 20px 0;
}
main section div:first-child button {
  background-color: #007bff;
  border: none;
  color: white;
  padding: 10px 20px;
  font-size: 16px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}
main section div:first-child button:hover {
  background-color: #0056b3;
}
main section div:last-child img {
  max-width: 100%;
  height: auto;
}
footer {
  display: flex;
  justify-content: center;
  padding: 20px 0;
}
footer button {
  background-color: transparent;
  border: 2px solid #007bff;
  color: #007bff;
  padding: 10px 20px;
  font-size: 16px;
  cursor: pointer;
  transition: background-color 0.3s ease, color 0.3s ease;
  margin: 0 10px;
}
footer button:hover {
  background-color: #007bff;
  color: white;
}
#service-features {
  padding: 50px;
  background-color: #f8f9fa;
}
#service-features h2 {
  font-size: 28px;
  font-weight: bold;
  margin-bottom: 20px;
}
#service-features p {
  font-size: 18px;
  margin-bottom: 20px;
}
#service-features div {
  display: flex;
  justify-content: space-between;
}
#service-features div div {
  max-width: 23%;
}
#service-features div div h3 {
  font-size: 22px;
  font-weight: bold;
  margin-bottom: 10px;
}
#service-features div div p {
  font-size: 16px;
  margin-bottom: 10px;
}
#service-process {
  padding: 50px;
  background-color: #ffffff;
}
#service-process h2 {
  font-size: 28px;
  font-weight: bold;
  margin-bottom: 20px;
}
#service-process p {
  font-size: 18px;
  margin-bottom: 20px;
}
#service-process div {
  display: flex;
  flex-direction: column;
}
#service-process div div {
  margin-bottom: 20px;
}
#service-process div div h3 {
  font-size: 22px;
  font-weight: bold;
  margin-bottom: 10px;
}
#service-process div div p {
  font-size: 16px;
  margin-bottom: 10px;
}
</style>
