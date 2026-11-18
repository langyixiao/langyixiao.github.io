[index.html](https://github.com/user-attachments/files/35024633/index.html)
<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="个人作品集网站 - 展示我的技能与项目" />
  <title>郎一骁 | 个人作品集</title>

  <!-- 字体：Inter（英文）+ Noto Sans SC（中文） -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Noto+Sans+SC:wght@400;500;700&display=swap" rel="stylesheet" />

  <link rel="stylesheet" href="css/style.css" />
</head>
<body>

  <!-- ============ 导航栏 ============ -->
  <header class="site-header" id="header">
    <nav class="nav container">
      <a href="#home" class="logo">郎一骁<span class="dot">.</span></a>

      <ul class="nav-links" id="navLinks">
        <li><a href="#home">首页</a></li>
        <li><a href="#about">关于</a></li>
        <li><a href="#skills">技能</a></li>
        <li><a href="#projects">作品</a></li>
        <li><a href="#contact">联系</a></li>
      </ul>

      <button class="menu-toggle" id="menuToggle" aria-label="打开菜单">
        <span></span><span></span><span></span>
      </button>
    </nav>
  </header>

  <!-- ============ Hero 区 ============ -->
  <section class="hero" id="home">
    <div class="hero-bg-grid"></div>
    <div class="container hero-inner">
      <div class="hero-text reveal">
        <p class="hero-greeting">你好，我是 <span class="wave">👋</span></p>
        <h1 class="hero-title">
          我是 <span class="gradient-text">郎一骁</span>,<br />
          一名<span class="gradient-text">创意开发者</span>
        </h1>
        <p class="hero-subtitle">
          热爱设计与技术，专注于打造美观、易用且富有创意的数字产品。
          用代码将想法变为现实，用设计让体验更加美好。
        </p>
        <div class="hero-actions">
          <a href="#projects" class="btn btn-primary">查看作品</a>
          <a href="#contact" class="btn btn-outline">联系我</a>
        </div>
        <div class="hero-social">
          <a href="https://github.com/你的用户名" target="_blank" rel="noopener" aria-label="GitHub">GitHub</a>
          <a href="https://www.linkedin.com/" target="_blank" rel="noopener" aria-label="LinkedIn">LinkedIn</a>
          <a href="#" target="_blank" rel="noopener" aria-label="Twitter">Twitter</a>
          <a href="mailto:3285003323@qq.com" aria-label="邮箱">邮箱</a>
        </div>
      </div>

      <div class="hero-visual reveal">
        <div class="avatar-card">
          <div class="avatar">
            <span>你的<br />照片</span>
          </div>
          <div class="avatar-badge">✨ 开放合作中</div>
        </div>
        <div class="floating-card card-code">
          <span class="fc-dot"></span> 前端开发
        </div>
        <div class="floating-card card-design">
          <span class="fc-dot"></span> UI/UX 设计
        </div>
      </div>
    </div>
  </section>

  <!-- ============ 关于我 ============ -->
  <section class="section about" id="about">
    <div class="container">
      <div class="section-heading reveal">
        <span class="section-label">关于我</span>
        <h2 class="section-title">一点点<a href="#projects">了解我</a></h2>
      </div>

      <div class="about-grid">
        <div class="about-text reveal">
          <p>
            我是一名充满热情的开发者与设计师，喜欢把复杂的问题简化成优雅的解决方案。
            我相信好的设计不止于外观，更在于它如何让人与产品产生连接。
          </p>
          <p>
            在工作之外，我喜欢探索新技术、写博客分享经验，也享受摄影和旅行带来的灵感。
            如果你有有趣的想法或项目，欢迎随时和我聊聊！
          </p>
          <a href="mailto:3285003323@qq.com" class="btn btn-primary">下载简历</a>
        </div>

        <div class="about-stats reveal">
          <div class="stat">
            <span class="stat-num" data-count="5">0</span><span class="stat-suffix">+</span>
            <p>年经验</p>
          </div>
          <div class="stat">
            <span class="stat-num" data-count="30">0</span><span class="stat-suffix">+</span>
            <p>完成项目</p>
          </div>
          <div class="stat">
            <span class="stat-num" data-count="15">0</span><span class="stat-suffix">+</span>
            <p>合作客户</p>
          </div>
          <div class="stat">
            <span class="stat-num" data-count="8">0</span><span class="stat-suffix">+</span>
            <p>获得奖项</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ============ 技能 ============ -->
  <section class="section skills" id="skills">
    <div class="container">
      <div class="section-heading reveal">
        <span class="section-label">我的技能</span>
        <h2 class="section-title">我擅长的<a href="#contact">领域</a></h2>
      </div>

      <div class="skills-grid">
        <div class="skill-card reveal">
          <div class="skill-icon">💻</div>
          <h3>前端开发</h3>
          <p>HTML、CSS、JavaScript、React、Vue，构建现代化响应式界面。</p>
          <div class="skill-bar"><span style="--level: 90%"></span></div>
        </div>
        <div class="skill-card reveal">
          <div class="skill-icon">🎨</div>
          <h3>UI / UX 设计</h3>
          <p>从视觉到交互，打造直观、美观且以用户为中心的产品体验。</p>
          <div class="skill-bar"><span style="--level: 85%"></span></div>
        </div>
        <div class="skill-card reveal">
          <div class="skill-icon">⚙️</div>
          <h3>后端开发</h3>
          <p>Node.js、Python、数据库设计，为产品提供稳定可靠的服务。</p>
          <div class="skill-bar"><span style="--level: 75%"></span></div>
        </div>
        <div class="skill-card reveal">
          <div class="skill-icon">📱</div>
          <h3>移动开发</h3>
          <p>跨平台移动应用开发，让产品在各类设备上流畅运行。</p>
          <div class="skill-bar"><span style="--level: 70%"></span></div>
        </div>
      </div>

      <div class="tech-stack reveal">
        <span class="tech-title">常用技术栈：</span>
        <div class="tech-tags">
          <span>HTML5</span><span>CSS3</span><span>JavaScript</span><span>TypeScript</span>
          <span>React</span><span>Vue</span><span>Node.js</span><span>Python</span>
          <span>Figma</span><span>Git</span>
        </div>
      </div>
    </div>
  </section>

  <!-- ============ 作品集 ============ -->
  <section class="section projects" id="projects">
    <div class="container">
      <div class="section-heading reveal">
        <span class="section-label">精选作品</span>
        <h2 class="section-title">我的一些<a href="#contact">项目</a></h2>
      </div>

      <div class="projects-grid">
        <!-- 项目卡片 1 -->
        <article class="project-card reveal">
          <div class="project-img img-1"><span>项目预览图</span></div>
          <div class="project-info">
            <span class="project-tag">Web 应用</span>
            <h3>项目一：任务管理平台</h3>
            <p>一个功能完整的团队协作与任务管理工具，支持实时更新与多端同步。</p>
            <div class="project-links">
              <a href="#" target="_blank" rel="noopener">在线预览 ↗</a>
              <a href="#" target="_blank" rel="noopener">源码 ↗</a>
            </div>
          </div>
        </article>

        <!-- 项目卡片 2 -->
        <article class="project-card reveal">
          <div class="project-img img-2"><span>项目预览图</span></div>
          <div class="project-info">
            <span class="project-tag">移动应用</span>
            <h3>项目二：生活方式 App</h3>
            <p>记录日常、管理习惯的移动端应用，以简洁设计提升生活品质。</p>
            <div class="project-links">
              <a href="#" target="_blank" rel="noopener">在线预览 ↗</a>
              <a href="#" target="_blank" rel="noopener">源码 ↗</a>
            </div>
          </div>
        </article>

        <!-- 项目卡片 3 -->
        <article class="project-card reveal">
          <div class="project-img img-3"><span>项目预览图</span></div>
          <div class="project-info">
            <span class="project-tag">品牌设计</span>
            <h3>项目三：品牌官网设计</h3>
            <p>为初创品牌打造的完整视觉识别与官方网站，突出品牌个性。</p>
            <div class="project-links">
              <a href="#" target="_blank" rel="noopener">在线预览 ↗</a>
              <a href="#" target="_blank" rel="noopener">源码 ↗</a>
            </div>
          </div>
        </article>

        <!-- 项目卡片 4 -->
        <article class="project-card reveal">
          <div class="project-img img-4"><span>项目预览图</span></div>
          <div class="project-info">
            <span class="project-tag">数据可视化</span>
            <h3>项目四：数据分析面板</h3>
            <p>交互式数据大屏，直观呈现关键业务指标与趋势变化。</p>
            <div class="project-links">
              <a href="#" target="_blank" rel="noopener">在线预览 ↗</a>
              <a href="#" target="_blank" rel="noopener">源码 ↗</a>
            </div>
          </div>
        </article>

        <!-- 项目卡片 5 -->
        <article class="project-card reveal">
          <div class="project-img img-5"><span>项目预览图</span></div>
          <div class="project-info">
            <span class="project-tag">开源工具</span>
            <h3>项目五：开发者工具库</h3>
            <p>提升开发效率的实用工具集合，已在 GitHub 开源并获得社区好评。</p>
            <div class="project-links">
              <a href="#" target="_blank" rel="noopener">在线预览 ↗</a>
              <a href="#" target="_blank" rel="noopener">源码 ↗</a>
            </div>
          </div>
        </article>

        <!-- 项目卡片 6 -->
        <article class="project-card reveal">
          <div class="project-img img-6"><span>项目预览图</span></div>
          <div class="project-info">
            <span class="project-tag">电商平台</span>
            <h3>项目六：在线商城</h3>
            <p>全栈电商解决方案，包含商品管理、购物车与在线支付流程。</p>
            <div class="project-links">
              <a href="#" target="_blank" rel="noopener">在线预览 ↗</a>
              <a href="#" target="_blank" rel="noopener">源码 ↗</a>
            </div>
          </div>
        </article>
      </div>
    </div>
  </section>

  <!-- ============ 联系我 ============ -->
  <section class="section contact" id="contact">
    <div class="container contact-inner reveal">
      <span class="section-label">保持联系</span>
      <h2 class="contact-title">有想法？<span class="gradient-text">聊聊吧</span></h2>
      <p>无论是合作项目、工作机会，还是想打个招呼，我都很乐意听到你的消息。</p>
      <a href="mailto:3285003323@qq.com" class="btn btn-primary btn-large">给我发邮件</a>
      <div class="contact-social">
        <a href="https://github.com/langyixiao" target="_blank" rel="noopener">GitHub</a>
        <a href="https://www.linkedin.com/" target="_blank" rel="noopener">LinkedIn</a>
        <a href="#" target="_blank" rel="noopener">Twitter</a>
        <a href="mailto:3285003323@qq.com">邮箱</a>
      </div>
    </div>
  </section>

  <!-- ============ 页脚 ============ -->
  <footer class="site-footer">
    <div class="container">
      <p>© <span id="year">2026</span> 郎一骁. 保留所有权利.</p>
      <p>Made with ❤️ and 代码</p>
    </div>
  </footer>

  <!-- 回到顶部 -->
  <a href="#home" class="back-to-top" id="backToTop" aria-label="回到顶部">↑</a>

  <script src="js/script.js"></script>
</body>
</html>
