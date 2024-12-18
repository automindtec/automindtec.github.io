<template>
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
  name: 'ServiceProcess'
}
</script>

<style scoped>
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
