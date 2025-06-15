---
layout: archive
title: "Links"
permalink: /Links/
author_profile: true
---

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Friendlinks</title>
  <style>
    /* 好友链接列表样式 */
    .friend-links-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      margin-top: 20px;
    }
    /* 每个好友的卡片样式 */
    .friend-card {
      background-color: #f0f0f0;
      border-radius: 10px;
      padding: 15px;
      width: 200px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      cursor: pointer;
      transition: transform 0.2s ease;
    }
    .friend-card:hover {
      transform: translateY(-5px);
    }
    /* 好友头像样式 */
    .avatar {
      width: 80px;
      height: 80px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 10px;
    }
    /* 好友名字样式 */
    .friend-name {
      font-size: 18px;
      font-weight: bold;
      color: #333;
    }
    /* 好友介绍样式 */
    .friend-intro {
      font-size: 14px;
      color: #777;
    }
  </style>
</head>
<body>


<h2>下载专区</h2>
<ul>
  <li><a href="../files/北京大学2025-2026学年校历.pdf">北京大学2025-2026学年校历</a></li>
</ul>

<h2>友链</h2>

<br/><br/>
<div class="friend-links-container">
    <!-- 每个好友卡片 -->
    <div class="friend-card" style="background-color: #f0f0f0;">
      <a href="https://i.pkuhub.cn" target="_blank">
        <img src="../images/avastars/pkuhub.jpg" alt="PKUHUB" class="avatar" onerror="this.onerror=null;this.src='../images/default-avatar.jpg';">
        <div class="friend-name">PKUHUB</div>
        <div class="friend-intro">笔记共享(PKU校园网)</div>
      </a>
    </div>
    <div class="friend-card" style="background-color: #f0f0f0;">
      <a href="https://ycyue10001.github.io" target="_blank">
        <img src="../images/male.jpg" alt="ycyue10001's Blog" class="avatar" onerror="this.onerror=null;this.src='../images/default-avatar.jpg';">
        <div class="friend-name">ycyue10001's Blog</div>
        <div class="friend-intro">闻数起舞，虽远必诛</div>
      </a>
    </div>
    <div class="friend-card" style="background-color: #f0f0f0;">
      <a href="https://ICUlizhi.github.io" target="_blank">
        <img src="../images/avastars/xj.jpg" alt="ICUlizhi" class="avatar" onerror="this.onerror=null;this.src='../images/default-avatar.jpg';">
        <div class="friend-name">PKUHUB</div>
        <div class="friend-intro">ICUlizhi's Blog</div>
      </a>
    </div>
    <div class="friend-card" style="background-color: #f0f0f0;">
      <a href="https://blog.imyangty.com/" target="_blank">
        <img src="../images/avastars/YangTY.jpg" alt="YangTY's Blog" class="avatar" onerror="this.onerror=null;this.src='../images/default-avatar.jpg';">
        <div class="friend-name">YangTY's Blog</div>
        <div class="friend-intro">越过山川</div>
      </a>
    </div>
  </div>
<br/><br/><br/>




<br/>

<!-- Giscus 评论系统嵌入 -->

<script src="https://giscus.app/client.js"
        data-repo="ycyue10001/ycyue10001.github.io"
        data-repo-id="R_kgDOO3Tdyw"
        data-category="Announcements"
        data-category-id="DIC_kwDOO3Tdy84Crfqv"
        data-mapping="title"
        data-strict="0"
        data-reactions-enabled="1"
        data-emit-metadata="1"
        data-input-position="top"
        data-theme="preferred_color_scheme"
        data-lang="zh-CN"
        data-loading="lazy"
        crossorigin="anonymous"
        async>
</script>
