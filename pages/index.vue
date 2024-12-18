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
          <img src="../Image/Herosection.png" alt="Laptop with system interface">
        </div>
      </section>
    </main>
    <footer>
      <button @click="scrollToSection('service-features')">服務特色</button>
      <button @click="scrollToSection('service-process')">諮詢流程</button>
      <button @click="scrollToSection('service-security')">系統安全</button>
      <button>價格一覽</button>
      <button>免費服務</button>
    </footer>
    <ServiceFeatures/>
    <ServiceProcess/>
    <ServiceSecurity/>
    
    
  </div>
</template>

<script>
import ServiceFeatures from "./service-features.vue";
import ServiceProcess from "./service-process.vue"; 
import ServiceSecurity from "./system-security.vue";

export default {
  components: {
    ServiceFeatures,
    ServiceProcess,
    ServiceSecurity,
  },
  methods: {
    scrollToSection(sectionId) {
      const section = document.getElementById(sectionId);
      if (section) {
        section.scrollIntoView({ behavior: "smooth" });
      }
    },
  },
};
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