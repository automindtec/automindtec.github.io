<template>
  <section id="free-services">
    <h2>購買後持續提供免費服務</h2>
    <p>這些通通免費，絕對有感的好用服務</p>
    <div>
      <div>
        <h3>舊資料轉移</h3>
        <p>無痛轉換新系統</p>
      </div>
      <div>
        <h3>高效資料維護</h3>
        <p>即時資料免費更新</p>
      </div>
      <div>
        <h3>配合法規更新</h3>
        <p>無須額外處理費用</p>
      </div>
      <div>
        <h3>免費即時諮詢</h3>
        <p>支持軟體使用問題</p>
      </div>
    </div>
    <button>立即諮詢</button>
  </section>
</template>

<script>
export default {
  name: 'FreeServices'
}
</script>

<style scoped>
#free-services {
  padding: 50px;
  background-color: #f8f9fa;
}
#free-services h2 {
  font-size: 28px;
  font-weight: bold;
  margin-bottom: 20px;
}
#free-services p {
  font-size: 18px;
  margin-bottom: 20px;
}
#free-services div {
  display: flex;
  justify-content: space-between;
}
#free-services div div {
  max-width: 23%;
}
#free-services div div h3 {
  font-size: 22px;
  font-weight: bold;
  margin-bottom: 10px;
}
#free-services div div p {
  font-size: 16px;
  margin-bottom: 10px;
}
#free-services button {
  background-color: #007bff;
  border: none;
  color: white;
  padding: 10px 20px;
  font-size: 16px;
  cursor: pointer;
  transition: background-color 0.3s ease;
}
#free-services button:hover {
  background-color: #0056b3;
}
</style>
