<template>
  <header>
    <nav>
      <ul>
        <li><NuxtLink to="/">首頁</NuxtLink></li> 
        <li><NuxtLink to="/home">產品介紹</NuxtLink></li> 
      </ul>
    </nav>
  </header>

  <NuxtPage />
</template>

 <style>
header nav {
  display: flex;
  justify-content: center; /* 水平置中 */
  padding: 15px 0; /* 上下增加一些內距 */
}

header nav ul {
  display: flex;
  list-style: none;
  padding: 0;
  margin: 0;
}

header nav ul li {
  margin-right: 20px;
}

header nav ul li:last-child {
  margin-right: 0;
}

/* 連結的基本樣式 */
header nav ul li a {
  color: #333;
  text-decoration: none;
  padding: 8px 15px; /* 增加內距 */
  transition: all 0.3s ease;
  font-size: 18px; /* 加大字體 */
  font-weight: 500; /* 稍微加粗 */
}

/* hover 效果 */
header nav ul li a:hover {
  color: #007bff; /* 懸停時的文字顏色 */
  background-color: #f8f9fa; /* 懸停時的背景顏色 */
  border-radius: 4px; /* 添加圓角 */
}
 </style>