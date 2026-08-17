---
permalink: /offer/
title: "Offers"
excerpt: ""
author_profile: true
---

<style>
dl {
margin-bottom: 60px; /* 调整这个值以获得合适的间距 */
clear: both;
}
/* 全局文本颜色 */
body {
color: #333; /* 主要文本颜色 */
background-image: url('../images/bg.jpg'); /* 背景图片 */
background-size: cover;
background-position: center;
background-attachment: fixed;
}

/* 链接颜色 */
a {
color: #0066cc; /* 链接颜色 */
}

/* 作者名字颜色 */
strong {
color: #000; /* 作者名字颜色 */
}

/* 年份标题颜色 */
.year-title {
color: #666;
}

/* 会议标签样式 */
.conference-label {
position: absolute;
top: 10px;
left: -5px;
background-color: #2c3e50;  /* 深蓝色背景 */
color: white;  /* 白色文字 */
padding: 6px 12px;
border-radius: 6px;
font-size: 0.95em;
font-weight: 600;
letter-spacing: 0.5px;
box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
z-index: 1;
font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
font-style: italic;  /* 添加斜体 */
}

/* 鼠标悬停效果 */
.conference-label:hover {
background-color: #34495e;  /* 悬停时稍微变亮 */
transition: background-color 0.2s ease;
}

dl dt img {
width: 100%; /* 在移动端默认占满宽度 */
aspect-ratio: 2/1; /* 设置宽高比为2:1，即高度为宽度的一半 */
object-fit: cover; /* 确保图片不会被裁剪 */
display: block;
margin: 10px 10px 10px 0px; /* 适当的间距 */

/* 添加美化效果 */
border-radius: 8px; /* 让图片有轻微的圆角 */
border: 2px solid #ddd; /* 添加淡灰色的边框 */
box-shadow: 3px 3px 10px rgba(0, 0, 0, 0.2); /* 添加轻微阴影 */
padding: 5px; /* 给图片一些内边距，让它不贴着边框 */
background-color: #fff; /* 设置背景色，让图片更加干净 */
}

/* 在桌面端（宽度大于768px）时固定宽度 */
@media screen and (min-width: 768px) {
dl dt img {
width: 350px;
}
}

dl dt {
position: relative;
}

hr {
border: 1px solid #ebebeb; /* 调整分隔线的颜色和样式 */
/* margin: 10px;  */
clear: both; 
}

dl dd {
margin-top: 5px; 
margin-bottom: 5px;
}

dl dd strong {
font-weight: bold;
color: black;
}

.co-first {
color: red;
}

.down {
transform: rotate(180deg);
}

/* 教育和工作经历卡片样式 */
.experience-card, .education-card {
display: flex;
align-items: center;
gap: 25px;
margin-bottom: 30px;
padding: 20px;
background: #f8f9fa;
border-radius: 12px;
transition: all 0.3s ease;
border: 1px solid #e9ecef;
}

.experience-card:hover, .education-card:hover {
transform: translateY(-3px);
box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
border-color: #dee2e6;
}

.experience-info, .education-info {
flex: 1;
}

.experience-logo, .education-logo {
flex-shrink: 0;
width: 100px;
height: 100px;
display: flex;
align-items: center;
justify-content: center;
background: white;
border-radius: 10px;
padding: 10px;
box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
}

.experience-logo img, .education-logo img {
width: 100%;
height: 100%;
object-fit: contain;
}

.experience-title, .education-title {
font-size: 1.2em;
margin-bottom: 8px;
color: #2c3e50;
}

.experience-title a, .education-title a {
color: #2c3e50;
text-decoration: none;
transition: color 0.3s ease;
}

.experience-title a:hover, .education-title a:hover {
color: #3498db;
}

.experience-role, .education-role {
color: #666;
font-style: italic;
margin-bottom: 5px;
}

.experience-topics, .education-topics {
color: #666;
font-style: italic;
}

.section-title {
font-size: 1.8em;
color: #2c3e50;
margin: 40px 0 20px;
padding-bottom: 10px;
border-bottom: 2px solid #ecf0f1;
}

/* 奖学金和荣誉部分样式 */
.honors-list {
list-style: none;
padding: 0;
}

.honors-list li {
margin-bottom: 15px;
padding: 15px 20px;
background: #f8f9fa;
border-radius: 8px;
border-left: 4px solid #3498db;
transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.honors-list li:hover {
transform: translateX(5px);
box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

.honors-list li strong {
color: #2c3e50;
}

.honors-list li a {
color: #3498db;
text-decoration: none;
transition: color 0.3s ease;
}

.honors-list li a:hover {
color: #2980b9;
}

/* 服务部分样式 */
.service-section {
margin-bottom: 30px;
}

.service-section h3 {
color: #2c3e50;
font-size: 1.3em;
margin: 25px 0 15px;
padding-bottom: 8px;
border-bottom: 2px solid #ecf0f1;
}

.service-list {
list-style: none;
padding: 0;
}

.service-list li {
margin-bottom: 12px;
padding: 12px 15px;
background: #f8f9fa;
border-radius: 6px;
transition: transform 0.3s ease;
}

.service-list li:hover {
transform: translateX(5px);
}

.service-list li a {
color: #3498db;
text-decoration: none;
transition: color 0.3s ease;
}

.service-list li a:hover {
color: #2980b9;
}
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>


I received my Ph.D. degree from the University of Hong Kong in 2026, where I was advised by  <a href="https://ece.hku.hk/people/echngai//">Prof. Edith C. H. Ngai</a> and co-advised by  <a href="https://xjqi.github.io/">Prof. Xiaojuan Qi</a>.

I have extensive research experience and a strong publication record in recommendation and graph learning. I have also explored multimodal understanding and the application of graph-based methods to downstream tasks, with several publications in these areas. Currently, I am actively pursuing new directions in graph learning for scientific discovery and generative recommendation.

I look forward to academic collaborations and enjoy making new friends.

Feel free to contact me via <a href="mailto:jinfeng@connect.hku.hk">Email</a> or <a href="https://Jinfeng-Xu.github.io/images/WeChat.jpeg">WeChat</a>. 

<hr>
# 🔥 News

<div style="max-height: 350px; overflow-y: auto; padding: 20px; background: #f8f9fa; border-left: 4px solid #2c3e50; margin: 0px 0;">
<style>
/* 为 Webkit 浏览器（Chrome, Safari, Edge）设置滚动条样式 */
div::-webkit-scrollbar {
width: 8px;
}

div::-webkit-scrollbar-track {
background: #e9ecef;
border-radius: 4px;
}

div::-webkit-scrollbar-thumb {
background: #2c3e50;
border-radius: 4px;
}

div::-webkit-scrollbar-thumb:hover {
background: #1a252f;
}

/* 为 Firefox 设置滚动条样式 */
div {
scrollbar-width: thin;
scrollbar-color: #2c3e50 #e9ecef;
}
</style>

<ul style="list-style-type: none; padding-left: 0; margin: 0;">
<li><em>2026.03:</em> 🎉 获腾讯青云计划顶尖人才计划正式offer <strong>3,600,000CNY/年</strong>. </li>
<li><em>2026.02:</em> 🎉 获小红书RedStar顶尖人才计划正式offer <strong>3,800,000CNY/年</strong>. </li>
<li><em>2025.11:</em> 🎉 获字节跳动筋斗云顶尖人才计划正式offer <strong>2,200,000CNY/年</strong>. </li>
<li><em>2025.07:</em> 🎉 获达摩院阿里星顶尖人才实习计划 <strong>2500CNY/天</strong>. </li>
<li><em>2025.01:</em> 🎉 获小红书RedStar顶尖人才实习计划 <strong>3200CNY/天</strong>. </li>













</ul>
</div>
