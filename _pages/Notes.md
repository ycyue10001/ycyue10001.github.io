---
layout: archive
title: "Notes"
permalink: /Notes/
author_profile: true
---

{% include base_path %}




## 观点与本站发展


  <style>

        /* 时间线容器 */
        .timeline-container {
            position: relative;
            max-width: 800px;
            margin: 0 auto;
        }

        /* 时间线竖线 */
        .timeline-container::after {
            content: '';
            position: absolute;
            width: 2px;
            background-color: #3498db;
            top: 0;
            bottom: 0;
            left: 20px;
        }

        /* 单个时间线项目 */
        .timeline-item {
            position: relative;
            margin-bottom: 40px;
            padding-left: 60px;
        }

        /* 时间节点圆点 */
        .timeline-node {
            position: absolute;
            left: 10px;
            top: 5px;
            width: 20px;
            height: 20px;
            background: #fff;
            border: 3px solid #3498db;
            border-radius: 50%;
            z-index: 1;
        }

        /* 内容区域 */
        .content {
            position: relative;
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        /* 时间标题 */
        .content h3 {
            color: #3498db;
            margin-bottom: 8px;
        }

        /* 时间日期 */
        .time {
            display: block;
            color: #666;
            font-size: 0.9em;
            margin-bottom: 10px;
        }

        /* 响应式设计 */
        @media (max-width: 600px) {
            .timeline-container::after {
                left: 10px;
            }
            
            .timeline-item {
                padding-left: 40px;
            }
            
            .timeline-node {
                left: 0;
            }
        }
    </style>
   <details><summary>点击展开 </summary>
  <div class="timeline-container">
    <!-- 2023 秋 -->
    <div class="timeline-item">
    <div class="timeline-node"></div>
    <div class="content">
              <h3>你好, PKU</h3>
              <span class="time">2023 秋</span>
              <p>初入燕园</p>
        </div>
    </div>
    <!-- 2023 秋 -->
    <div class="timeline-item">
    <div class="timeline-node"></div>
    <div class="content">
              <h3>高数D和计概C给我的自信</h3>
              <span class="time">2023 秋</span>
              <p>大一上是我在校本部读医学预科最快乐的时光，那时候上英语课的我，课上喜欢开小差，算算题，敲敲代码，帮同学处理数学和代码相关的问题，颇有成就感，这两门课让我大一上的GPA更加美观~</p>
        </div>
    </div>
    </div>
</details>



## 专业课

{% assign paths = "Histology-and-embryology.md" | split: "," %}

{% for post in site.Notes reversed %}
  {% for path in paths %}
    {% if post.path contains path %}
      {% include archive-single.html %}
      {% break %}
    {% endif %}
  {% endfor %}
{% endfor %}

## 经济学双学位

{% assign paths = "Intermediate-Microeconomics.md" | split: "," %}

{% for post in site.Notes reversed %}
  {% for path in paths %}
    {% if post.path contains path %}
      {% include archive-single.html %}
      {% break %}
    {% endif %}
  {% endfor %}
{% endfor %}






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
