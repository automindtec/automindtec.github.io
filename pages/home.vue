<template>
  <div>
    <h1>首頁</h1>
    <section id="hero-section">
      <h2>最專業的客製化藥局系統</h2>
      <p>你想得到的，我們幫你實現。</p>
      <button @click="scrollToSection('service-features')">立即諮詢</button>
    </section>
    <section id="service-features">
      <h2>服務特色</h2>
      <p>貼心即時的服務 x 專業前沿的技術</p>
      <div>
        <div>
          <h3>直覺操作</h3>
          <p>無痛轉換最新規格 定期提升使用者體驗 享受無痛升級新技術</p>
        </div>
        <div>
          <h3>快速專業</h3>
          <p>貼心快速的諮詢管道 遇到產品任何大小問題 專人在線即時為您處理</p>
        </div>
        <div>
          <h3>透明價格</h3>
          <p>公開合理的價格 數位化系統定期升級 承諾不收取額外費用</p>
        </div>
        <div>
          <h3>簡潔介面</h3>
          <p>資料顯示好清楚 調劑系統實現減法美學 藥師們不必再用眼過度</p>
        </div>
      </div>
      <div>
        <h3>專為藥師設計的軟體服務</h3>
        <p>七年觀察產業脈動，正式推出最符合藥師需求的藥局調劑系統。告別傳統軟體的僵化操作，Auto Pharmacy 系統專為藥師作業流程設計，全系統支援健保 Web API 2.0，同時確保系統定期配合相關政策送代優化。</p>
        <p>重新定義台灣藥局 HIS & POS 軟體，開啟現代化藥局的第一步。</p>
      </div>
    </section>
    <div>
      <button @click="scrollToSection('service-features')">服務特色</button>
      <button @click="scrollToSection('consultation-process')">諮詢流程</button>
      <button @click="scrollToSection('system-security')">系統安全</button>
      <button @click="scrollToSection('price-list')">價格一覽</button>
      <button @click="scrollToSection('free-services')">免費服務</button>
    </div>
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
