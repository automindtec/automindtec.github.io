<template>
  <section id="service-features">
    <h2>服務特色</h2>
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
</template>

<script>
export default {
  name: 'ServiceFeatures'
}
</script>

<style scoped>
#service-features, #service-process {
  padding: 50px;
  background-color: #f8f9fa;
}
#service-features h2, #service-process h2 {
  font-size: 28px;
  font-weight: bold;
  margin-bottom: 20px;
}
#service-features div, #service-process div {
  display: flex;
  justify-content: space-between;
}
#service-features div div, #service-process div div {
  max-width: 23%;
}
#service-features div div h3, #service-process div div h3 {
  font-size: 22px;
  font-weight: bold;
  margin-bottom: 10px;
}
#service-features div div p, #service-process div div p {
  font-size: 16px;
  margin-bottom: 10px;
}
</style>
