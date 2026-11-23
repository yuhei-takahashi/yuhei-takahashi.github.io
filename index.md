---
layout: single
permalink: /
title: ""
author_profile: false
classes: wide
---

<div class="academic-home">
  <section class="home-hero" aria-labelledby="home-name">
    <div class="home-hero__intro">
      <p class="home-kicker">YUHEI TAKAHASHI · ACADEMIC WEBSITE</p>
      <div class="home-identity">
        <div class="home-identity__text">
          <h1 id="home-name" class="home-name">高橋 侑平 <span>Yuhei Takahashi</span></h1>
          <div class="home-affiliation">
            <p>同志社大学大学院 理工学研究科 博士後期課程</p>
            <p>株式会社日立製作所 鉄道ビジネスユニット</p>
          </div>
        </div>
        <img class="home-profile-image"
             src="{{ '/assets/images/profile.PNG' | relative_url }}"
             alt="高橋侑平のプロフィール写真" width="148" height="182"
             loading="eager" decoding="async">
      </div>
      <p class="home-introduction">無線通信に関する研究を行っています。特に、ランダムアクセス方式の理論解析、複数受信アンテナを用いたパケット復号、およびデバイス認証に取り組んでいます。</p>
      <div class="home-actions">
        <a class="home-button home-button--primary" href="{{ '/publications/' | relative_url }}">研究業績 <span aria-hidden="true">→</span></a>
        <a class="home-button home-button--outline" href="{{ '/assets/pdf/publications.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer">業績一覧（PDF） <span aria-hidden="true">↗</span></a>
      </div>
    </div>

    <aside class="home-focus" aria-labelledby="interests-title">
      <p class="home-focus__eyebrow">RESEARCH INTERESTS</p>
      <h2 id="interests-title">主な研究分野</h2>
      <div class="home-focus__item">
        <h3>ランダムアクセス方式</h3>
        <p>Slotted ALOHA / フェージング / マルチアンテナ</p>
      </div>
      <div class="home-focus__item">
        <h3>デバイス認証</h3>
        <p>無線周波数フィンガープリント（RFF）を用いた認証</p>
      </div>
    </aside>
  </section>

  <section class="home-section" aria-labelledby="home-about-title">
    <div class="home-section__heading">
      <div><p class="home-section__eyebrow">ABOUT</p><h2 id="home-about-title">研究について</h2></div>
    </div>
    <p class="home-research-text">多数の端末が無線通信路を共有する環境を対象に、ランダムアクセス方式の性能と理論限界を研究しています。特に、フェージング環境でのパケット復号、複数受信アンテナを用いた逐次干渉除去（SIC）、および無線周波数フィンガープリント（RFF）によるデバイス認証に関心があります。</p>
    <nav class="home-secondary-links" aria-label="関連ページ">
      <a href="{{ '/biography/' | relative_url }}">経歴を見る <span aria-hidden="true">↗</span></a>
      <a href="{{ '/repositories/' | relative_url }}">公開コードを見る <span aria-hidden="true">↗</span></a>
      <a href="mailto:yuhei-takahashi@ieee.org">お問い合わせ <span aria-hidden="true">↗</span></a>
    </nav>
  </section>

  <section class="home-section" aria-labelledby="home-news-title">
    <div class="home-section__heading">
      <div><p class="home-section__eyebrow">NEWS</p><h2 id="home-news-title">お知らせ</h2></div>
      <a class="home-more" href="{{ '/news/' | relative_url }}">すべて見る <span aria-hidden="true">→</span></a>
    </div>
    <div class="home-news-list">
      <div class="home-news-item"><time datetime="2025-10">2025年10月</time><p>複数受信アンテナを用いたSlotted ALOHAに関する研究の<a href="https://github.com/yuhei-takahashi/Multi-Antenna_SA">ソースコードを公開</a>しました。</p></div>
      <div class="home-news-item"><time datetime="2025-03">2025年3月</time><p>「Coded Slotted ALOHA over Rayleigh Block Fading Channels」の<a href="https://youtu.be/15SwQzBBuZs">研究発表動画を公開</a>しました。</p></div>
      <div class="home-news-item"><time datetime="2024-08">2024年8月</time><p>SICを用いた2端末Slotted ALOHAに関する論文がISITA 2024に採択されました。</p></div>
    </div>
  </section>
</div>
