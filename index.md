---
layout: default
---

<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>정석진 - 이력서</title>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+KR:wght@300;400;500;700;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <!-- 헤더 섹션 -->
        <header class="resume-header">
            <div class="profile-container">
                <div class="profile-img" style="background-image: url('images/jeongseokjin.jpg')"></div>
                <div class="profile-text">
                    <h1>정석진</h1>
                    <h2>백엔드 개발자 </h2>
                    
                    <ul class="contact-info">
                        <li><i class="fas fa-envelope"></i> <a href="mailto:sj_jeong384@naver.com">sj_jeong384@naver.com</a></li>
                        <li><i class="fab fa-github"></i> <a href="https://github.com/Jeongseokjin" target="_blank">github.com/Jeongseokjin</a></li>
                        <li><i class="fas fa-blog"></i> <a href="https://1223tjrwls.tistory.com/" target="_blank">1223tjrwls.tistory.com</a></li>
                    </ul>
                    
                     <p class="about-content">저는 Java/Spring 백엔드 개발자로서, 기술로 문제를 해결하며 조직의 성공을 이끄는 데 집중합니다.</p>
  <p class="about-content">시스템 효율성을 극대화하고 혁신적인 솔루션으로 시간과 비용을 절감하는 개발자가 목표입니다.</p>
  <p class="about-content">끊임없는 성장을 통해 조직에 실질적인 가치를 더하겠습니다.</p>
                </div>
            </div>
        </header>

        <!-- 스킬 섹션 -->
        <section class="resume-section">
            <h2 class="section-title">Skills</h2>
            <div class="skills-container">
                <div class="skill-category">
                    <h3 class="skill-heading">Backend</h3>
                    <ul class="skill-list">
                        <li>Java, Spring Boot, Spring Data JPA, Spring Cloud Stream</li>
                        <li>Kafka, Event Sourcing</li>
                        <li>Hibernate, Flyway</li>
                        <li>JUnit5, Mockito, Testcontainers</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h3 class="skill-heading">Cloud & DevOps</h3>
                    <ul class="skill-list">
                        <li>AWS (EC2, ELB, Route 53, S3, RDS, CloudWatch)</li>
                        <li>GitHub Actions, CodePipeline</li>
                        <li>Docker, Kubernetes</li>
                        <li>Prometheus, Grafana</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h3 class="skill-heading">Database</h3>
                    <ul class="skill-list">
                        <li>MySQL, JPQL, QueryDSL, Flyway</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h3 class="skill-heading">Frontend</h3>
                    <ul class="skill-list">
                        <li>React.js, Next.js, Three.js</li>
                        <li>HTML, CSS3, JavaScript (ES6)</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h3 class="skill-heading">Tools & Collaboration</h3>
                    <ul class="skill-list">
                        <li>IntelliJ, VS Code</li>
                        <li>Git, GitHub</li>
                        <li>Jira, Slack</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- 경력 및 프로젝트 섹션 -->
        <section class="resume-section">
            <h2 class="section-title">Projects & Work Experience</h2>
            
            <!-- IT MOO U -->
            <div class="experience-item">
                <div class="experience-header">
                    <div>
                        <h3 class="experience-title">IT MOO U</h3>
                        <p class="experience-company">백엔드 개발자 | 물류 최적화 개발자</p>
                    </div>
                    <span class="experience-period">2024.03 - 현재</span>
                </div>
                
                <div class="tech-stack">
                    <span class="tech-tag">Java</span>
                    <span class="tech-tag">Spring Boot</span>
                    <span class="tech-tag">Kafka</span>
                    <span class="tech-tag">Spring Cloud Stream</span>
                    <span class="tech-tag">MySQL</span>
                    <span class="tech-tag">Docker</span>
                    <span class="tech-tag">Kubernetes</span>
                    <span class="tech-tag">AWS</span>
                </div>
                
                <a href="https://github.com/Jeongseokjin/allogic-platform" target="_blank" class="link-button">
                    <i class="fab fa-github"></i>GitHub
                </a>
                
                <ul>
                    <li>팔레트 물류 최적화를 위한 MVP를 설계 및 개발하며 초기 서비스 검증 주도</li>
                    <li>Kafka 기반 이벤트 드리븐 아키텍쳐(EDA)를 설계해 시스템 간 비동기 통신 최적화</li>
                    <li>ECS 기반 배포 파이프라인을 구축해 운영비용 15% 절감 및 배포 안정성 확보</li>
                    <li>AI 기술을 전략적으로 활용하여 기획부터 배포까지의 프로세스를 효율화함으로써, 초기 제품 검증 단계를 대폭 가속화</li>
                    <li>물류 시스템의 확장성을 고려한 클라우드 네이티브 아키텍처 설계</li>
                </ul>
            </div>
            
            <!-- WOORI ZIP 프로젝트 -->
            <div class="experience-item">
                <div class="experience-header">
                    <div>
                        <h3 class="experience-title">WOORI ZIP</h3>
                    </div>
                    <span class="experience-period">2024.10.21 - 2024.12.06</span>
                </div>
                
                <div class="tech-stack">
                    <span class="tech-tag">React</span>
                    <span class="tech-tag">Next.js</span>
                    <span class="tech-tag">Spring Boot</span>
                    <span class="tech-tag">JPA</span>
                    <span class="tech-tag">MySQL</span>
                    <span class="tech-tag">AWS</span>
                    <span class="tech-tag">Prometheus</span>
                    <span class="tech-tag">Kakao Maps API</span>
                </div>
                
                <a href="https://github.com/woorifisa-projects-3rd/woori-zip-BE/tree/main" target="_blank" class="link-button">
                    <i class="fab fa-github"></i>WOORI ZIP GitHub
                </a>
                
                <ul>
                    <li>Spring Boot와 ML 모델을 활용한 금융 데이터 기반 맞춤형 부동산 추천 시스템 설계 및 구현</li>
                    <li>OAuth 2.0과 JWT를 활용한 우리은행 계정 연동 및 권한별 인증 시스템 구축</li>
                    <li>AOP 기반 로깅 시스템을 주도적으로 개선하여 MDC와 ELK 스택으로 API 요청/응답 추적 및 실시간 모니터링 체계 확립</li>
                    <li>AWS(EC2, RDS, S3) 기반 클라우드 인프라를 설계하고 CI/CD 파이프라인 구축으로 배포 자동화</li>
                    <li>사용자 주택 조건 및 금융 정보에 따른 최적 대출 상품 매칭 알고리즘 개발</li>
                </ul>
            </div>

            <!-- 대원프리시전 -->
            <div class="experience-item">
                <div class="experience-header">
                    <div>
                        <h3 class="experience-title">(주)대원프리시전</h3>
                        <p class="experience-company">설비OP 자동차 ESS 설비 기술 주임</p>
                    </div>
                    <span class="experience-period">2020.10 ~ 2024.04 (3년 6개월)</span>
                </div>
                
                <ul>
                    <li>배터리 사업의 경쟁력을 위해 비용 절감을 최우선 목표로 설정하고, 불량률 감소에 주력</li>
                    <li>SCADA 시스템을 도입해 설비 데이터를 실시간으로 수집 및 시각화하며, 장력 불규칙성이 주요 원인임을 규명</li>
                    <li>설계팀과 협업하여 전극 장력 조절 롤러 시스템을 개발하고, 센서 데이터를 PLC 시스템과 연동해 장력을 자동으로 조절할 수 있는 시스템 설계</li>
                    <li>작업자가 설비 상태를 직관적으로 확인할 수 있도록 HMI 인터페이스를 도입하고, 장력이 임계값을 초과하면 자동으로 설비를 정지하는 기능 구현</li>
                </ul>
            </div>

            <!-- 이한산업 -->
            <div class="experience-item">
                <div class="experience-header">
                    <div>
                        <h3 class="experience-title">(주)이한산업</h3>
                        <p class="experience-company">설비OP 설비 개발 사원</p>
                    </div>
                    <span class="experience-period">2020.03 ~ 2020.09 (7개월)</span>
                </div>
                
                <ul>
                    <li>설계팀, 생산팀과 긴밀히 협력하여 친환경 소재 압축을 위한 유압 프레스 설비의 개발과 안정화 작업을 수행하며, 설비 운영 중 발생 가능한 위험 요소를 파악</li>
                    <li>설비 안전성을 강화하기 위해 안전 센서 및 비상 정지 장치의 도입과 개선 방안을 논의하고 적극적으로 참여하여 개선 방안을 마련</li>
                </ul>
            </div>
        </section>

        <!-- 아티클 섹션 -->
        <section class="resume-section">
            <h2 class="section-title">Article</h2>
            
            <div class="experience-item">
                <div class="experience-header">
                    <div>
                        <h3 class="experience-title">기술 서적 리뷰 참여</h3>
                    </div>
                </div>
                
                <ul>
                    <li><strong>&lt;코딩 자율학습 자바 입문&gt; 베타 학습단</strong>
                        <ul>
                            <li><a href="https://www.notion.so/11f81bfd238b804fb737cccd27bebf52?pvs=4#1c181bfd238b80b1a9abfb792d61d9c8" target="_blank">코딩 자율학습 자바 입문 리뷰.pdf</a></li>
                            <li><a href="https://rune-lan-2a9.notion.site/1b981bfd238b8054973de480f30a200e?pvs=4" target="_blank">학습단 참여 확인서_정석진.pdf</a></li>
                        </ul>
                    </li>
                    <li><strong>[길벗] &lt;아는 만큼 보이는 IT 지식&gt; 베타 리뷰</strong>
                        <ul>
                            <li><a href="https://www.notion.so/11f81bfd238b804fb737cccd27bebf52?pvs=4#1c181bfd238b80c99e87e89b4c80dea4" target="_blank">베타 리더 리뷰</a></li>
                        </ul>
                    </li>
                </ul>
            </div>
            
            <div class="experience-item">
                <div class="experience-header">
                    <div>
                        <h3 class="experience-title">개인 블로그 활동</h3>
                    </div>
                </div>
                
                <a href="https://1223tjrwls.tistory.com/" target="_blank" class="link-button">
                    <i class="fas fa-blog"></i>정석진 개인 블로그
                </a>
                
                <ul>
                    <li>이슈 해결 사례 및 기술 노하우 공유</li>
                    <li>물류 최적화 및 이벤트 드리븐 아키텍처 관련 기술 분석</li>
                </ul>
            </div>
        </section>

        <!-- 교육 섹션 -->
        <section class="resume-section">
            <h2 class="section-title">Education</h2>
            
            <div class="education-item">
                <div class="education-header">
                    <div>
                        <h3 class="education-title">우리 FISA 3기</h3>
                    </div>
                    <span class="education-period">2024.07 - 2024.12</span>
                </div>
                
                <ul>
                    <li>AWS 기반 클라우드 서비스 개발, 서버 배포 및 관리 교육</li>
                    <li>Java와 Spring Boot로 RESTful API 설계 및 구현 학습</li>
                    <li>MySQL, JPA로 데이터베이스 연동 및 쿼리 작성 (JPQL, QueryDSL) 실습</li>
                    <li>Flyway로 데이터베이스 스키마 버전 관리 및 자동 마이그레이션 학습</li>
                    <li>WOORI ZIP 프로젝트 진행 (2024.10.21 - 2024.12.06), 풀스택 및 DevOps 기술 학습</li>
                </ul>
            </div>
            
            <div class="education-item">
                <div class="education-header">
                    <div>
                        <h3 class="education-title">청주대학교</h3>
                    </div>
                    <span class="education-period">2015.03 - 2021.02</span>
                </div>
                
                <ul>
                    <li>전공: 컴퓨터정보공학과</li>
                    <li>학생회장 활동으로 리더십, 협동심, 문제해결능력 강화</li>
                </ul>
            </div>
        </section>
     </div>
    
    <!-- 푸터 섹션 -->
    <footer class="resume-footer">
        <div class="footer-content">
            <span class="footer-name">정석진</span>
            <span class="footer-separator">•</span>
            <a href="mailto:sj_jeong384@naver.com" class="footer-email">sj_jeong384@naver.com</a>
            <span class="footer-separator">•</span>
            <span class="footer-reference">References on request</span>
        </div>
    </footer>
</body>
</html>