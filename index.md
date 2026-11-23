<div class="academic-home">

  <section class="home-hero" aria-labelledby="home-name">
    <div class="home-hero__intro">
      <div class="home-identity">
        <div class="home-identity__text">
          <p class="home-kicker">RESEARCH WEBSITE</p>
          <h1 id="home-name" class="home-name">高橋 侑平 <span>Yuhei Takahashi</span></h1>
        </div>
        <img
          class="home-profile-image"
          src="{{ '/assets/images/profile.PNG' | relative_url }}"
          alt="高橋侑平のプロフィール写真"
          width="136"
          height="170"
          loading="eager"
          decoding="async"
        >
      </div>
      <div class="home-affiliation">
        <p>同志社大学大学院 理工学研究科 博士後期課程</p>
        <p>株式会社日立製作所 鉄道ビジネスユニット</p>
      </div>
      <p class="home-introduction">
        無線通信に関する研究を行っています。
        特に、ランダムアクセス方式の理論解析、複数受信アンテナを用いたパケット復号、
        およびデバイス認証に取り組んでいます。
      </p>
      <div class="home-actions">
        <a class="home-button home-button--primary" href="{{ '/publications/' | relative_url }}">研究業績を見る <span aria-hidden="true">→</span></a>
        <a class="home-button home-button--outline" href="{{ '/assets/pdf/publications.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer">業績一覧（PDF） <span aria-hidden="true">↗</span></a>
      </div>
    </div>

    <aside class="home-focus" aria-label="主な研究分野">
      <p class="home-focus__eyebrow">RESEARCH INTERESTS</p>
      <h2>主な研究分野</h2>
      <ul>
        <li><strong>ランダムアクセス方式</strong><span>Slotted ALOHA / フェージング / マルチアンテナ</span></li>
        <li><strong>デバイス認証</strong><span>無線周波数フィンガープリント（RFF）を用いた認証</span></li>
      </ul>
    </aside>
  </section>

  <section class="home-section home-section--research" aria-labelledby="home-research-title">
    <div class="home-section__heading">
      <div>
        <p class="home-section__eyebrow">ABOUT MY RESEARCH</p>
        <h2 id="home-research-title">研究について</h2>
      </div>
    </div>
    <p class="home-research-text">
      多数の端末が無線通信路を共有する環境を対象に、衝突した信号を効率的に復号するための
      ランダムアクセス方式を研究しています。確率モデルや反復復号の解析手法を用いて、
      通信方式の達成性能と理論限界を明らかにすることを目指しています。
    </p>
    <nav class="home-secondary-links" aria-label="研究関連ページ">
      <a href="{{ '/biography/' | relative_url }}">経歴 <span aria-hidden="true">↗</span></a>
      <a href="{{ '/repositories/' | relative_url }}">公開コード <span aria-hidden="true">↗</span></a>
      <a href="mailto:yuhei-takahashi@ieee.org">お問い合わせ <span aria-hidden="true">↗</span></a>
    </nav>
  </section>

  <section class="home-section home-section--news" aria-labelledby="home-news-title">
    <div class="home-section__heading">
      <div>
        <p class="home-section__eyebrow">NEWS</p>
        <h2 id="home-news-title">お知らせ</h2>
      </div>
      <a class="home-more" href="{{ '/news/' | relative_url }}">一覧を見る <span aria-hidden="true">→</span></a>
    </div>
    <div class="home-news-list">
      <div class="home-news-item">
        <time datetime="2025-10">2025.10</time>
        <p>複数受信アンテナを用いたSlotted ALOHAに関する研究の<a href="https://github.com/yuhei-takahashi/Multi-Antenna_SA">ソースコードを公開</a>しました。</p>
      </div>
      <div class="home-news-item">
        <time datetime="2025-03">2025.03</time>
        <p>「Coded Slotted ALOHA over Rayleigh Block Fading Channels」の<a href="https://youtu.be/15SwQzBBuZs">研究発表動画を公開</a>しました。</p>
      </div>
      <div class="home-news-item">
        <time datetime="2024-08">2024.08</time>
        <p>SICを用いた2端末Slotted ALOHAに関する論文がISITA 2024に採択されました。</p>
      </div>
    </div>
  </section>

</div>
