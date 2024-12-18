<template>
  <section id="system-security">
    <h2>系統安全保證</h2>
    <div>
      <div>
        <h3>通訊公私鑰加密</h3>
        <p>確保通訊過程中的數據安全</p>
      </div>
      <div>
        <h3>資料庫敏感欄位加密</h3>
        <p>保護敏感數據免受未經授權的訪問</p>
      </div>
      <div>
        <h3>安全的資料傳輸</h3>
        <p>確保數據在傳輸過程中的完整性和安全性</p>
      </div>
    </div>
    <p>我們致力於提供最安全的系統，確保您的數據始終受到保護。</p>
  </section>
</template>

<script>
export default {
  name: 'SystemSecurity'
}
</script>

<style scoped>
#system-security {
  padding: 50px;
  background-color: #f8f9fa;
}
#system-security h2 {
  font-size: 28px;
  font-weight: bold;
  margin-bottom: 20px;
}
#system-security div {
  display: flex;
  justify-content: space-between;
}
#system-security div div {
  max-width: 30%;
}
#system-security div div h3 {
  font-size: 22px;
  font-weight: bold;
  margin-bottom: 10px;
}
#system-security div div p {
  font-size: 16px;
  margin-bottom: 10px;
}
#system-security p {
  font-size: 18px;
  margin-top: 20px;
}
</style>
