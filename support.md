---
layout: single
title: "App Support"
permalink: /support/
author_profile: false
---

<style>
.app-support {
  max-width: 800px;
  margin: 0 auto;
  padding: 2rem 1rem;
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
}

.header {
  text-align: center;
  margin-bottom: 3rem;
}

.header h1 {
  font-size: 2.5rem;
  font-weight: 300;
  color: #333;
  margin-bottom: 0.5rem;
}

.header p {
  font-size: 1.1rem;
  color: #666;
  margin: 0;
}

.apps-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 2rem;
  margin-bottom: 3rem;
}

.app-card {
  background: #fff;
  border-radius: 12px;
  padding: 2rem;
  box-shadow: 0 2px 20px rgba(0,0,0,0.1);
  border: 1px solid #f0f0f0;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.app-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 25px rgba(0,0,0,0.15);
}

.app-header {
  display: flex;
  align-items: center;
  margin-bottom: 1.5rem;
}

.app-icon {
  width: 60px;
  height: 60px;
  border-radius: 12px;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  display: flex;
  align-items: center;
  justify-content: center;
  margin-right: 1rem;
  font-size: 1.5rem;
  color: white;
  font-weight: 500;
}

.app-icon.yomu {
  background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
}

.app-info h3 {
  font-size: 1.5rem;
  font-weight: 600;
  color: #333;
  margin: 0 0 0.25rem 0;
}

.app-info .category {
  font-size: 0.9rem;
  color: #007AFF;
  background: #f0f8ff;
  padding: 0.25rem 0.75rem;
  border-radius: 20px;
  display: inline-block;
}

.app-description {
  color: #555;
  line-height: 1.6;
  font-size: 1rem;
}

.contact-section {
  background: #f8f9fa;
  border-radius: 12px;
  padding: 2rem;
  text-align: center;
}

.contact-section h2 {
  font-size: 1.5rem;
  font-weight: 600;
  color: #333;
  margin-bottom: 1rem;
}

.contact-section p {
  color: #666;
  margin-bottom: 1.5rem;
  line-height: 1.6;
}

.email-link {
  display: inline-block;
  background: #007AFF;
  color: white;
  text-decoration: none;
  padding: 0.75rem 2rem;
  border-radius: 8px;
  font-weight: 500;
  transition: background-color 0.2s ease;
}

.email-link:hover {
  background: #0056b3;
  color: white;
  text-decoration: none;
}

@media (max-width: 768px) {
  .apps-grid {
    grid-template-columns: 1fr;
  }
  
  .header h1 {
    font-size: 2rem;
  }
  
  .app-support {
    padding: 1rem;
  }
}
</style>

<div class="app-support">
  <div class="header">
    <h1>App Support</h1>
    <p>생산성을 위한 미니멀 앱들</p>
  </div>

  <div class="apps-grid">
    <div class="app-card">
      <div class="app-header">
        <div class="app-icon">書</div>
        <div class="app-info">
          <h3>書く (Kaku)</h3>
          <span class="category">생산성</span>
        </div>
      </div>
      <div class="app-description">
        <p>간단하고 직관적인 메모 작성 앱입니다. 일상의 생각과 아이디어를 빠르게 기록하고 정리할 수 있습니다. 미니멀한 인터페이스로 글쓰기에만 집중할 수 있도록 도와줍니다.</p>
      </div>
    </div>

    <div class="app-card">
      <div class="app-header">
        <div class="app-icon yomu">読</div>
        <div class="app-info">
          <h3>読む (Yomu)</h3>
          <span class="category">생산성</span>
        </div>
      </div>
      <div class="app-description">
        <p>효율적인 읽기와 메모 관리를 위한 앱입니다. 읽은 내용을 체계적으로 정리하고, 중요한 정보를 쉽게 찾아볼 수 있습니다. 지식 축적과 관리를 도와주는 스마트한 도구입니다.</p>
      </div>
    </div>
  </div>

  <div class="contact-section">
    <h2>문의사항</h2>
    <p>
      앱 사용 중 문제가 발생하거나 궁금한 점이 있으시면<br>
      언제든지 아래 이메일로 연락 주세요.
    </p>
    <a href="mailto:daegunkor@gmail.com" class="email-link">
      daegunkor@gmail.com
    </a>
  </div>
</div>
