---
layout: default
title: about
permalink: /

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Shanghai, China</p>
    <p>applesoup@sjtu.edu.cn</p>

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<div class="post">
  <header class="post-header">
    <h1 class="post-title"><span class="font-weight-bold">Wenjing</span> Tang</h1>
  </header>

  <article>
    <div class="profile float-right">
      {% include figure.liquid loading="eager" path="assets/img/prof_pic.jpg" class="img-fluid z-depth-1 rounded" sizes="(min-width: 930px) 270px, (min-width: 576px) 30vw, 95vw" alt="Wenjing Tang" cache_bust=true %}
      <div class="more-info">
        <p>Shanghai, China</p>
        <p>applesoup@sjtu.edu.cn</p>
      </div>
    </div>

    <div class="clearfix">
      <p>
        I am <strong>Wenjing Tang (汤雯婧)</strong>, a Ph.D. student in the
        <a href="https://www.cs.sjtu.edu.cn/">School of Computer Science</a> at Shanghai Jiao Tong University, advised by
        <a href="https://www.ropl.ai/author/panpan-cai/">Prof. Panpan Cai</a>. I am currently a visiting student at the Shanghai Innovation Institute and a member of the
        <a href="https://www.ropl.ai/">Robotics and Planning Lab (RoPL)</a>.
      </p>

      <p>
        My research focuses on <strong>robot task planning under uncertainty</strong>. I am particularly interested in robot task planning, planning under uncertainty, POMDPs and belief-space planning, and symbolic planning. My long-term goal is to develop intelligent robots that can reason, plan, and act reliably in open-world environments.
      </p>
    </div>

    <h2>news</h2>
    {% include news.liquid limit=true %}

    <h2><a href="{{ '/publications/' | relative_url }}" style="color: inherit">highlights</a></h2>
    {% include selected_papers.liquid %}

    <div class="social">
      <div class="contact-icons">{% social_links %}</div>
      <div class="contact-note">{{ site.contact_note }}</div>
    </div>

  </article>
</div>
