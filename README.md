<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:1e40af&height=220&section=header&text=J0JIN&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Security%20Platform%20Engineer%20%7C%20SOC%20Platform%20%7C%20Splunk%20API%20%7C%20PostgreSQL%20%7C%20SOAR&descAlignY=55&descAlign=50" />
</p>

<h3 align="center">Security Platform Engineer</h3>

<p align="center">
  SOC Platform · Splunk API · PostgreSQL Performance · SOAR Automation
</p>

<p align="center">
  <a href="https://blog.naver.com/my-dev-note">
    <img src="https://img.shields.io/badge/Naver%20Blog-03C75A?style=for-the-badge&logo=naver&logoColor=white"/>
  </a>
  <a href="https://velog.io/@tl5235566/posts">
    <img src="https://img.shields.io/badge/Velog-20C997?style=for-the-badge&logo=velog&logoColor=white"/>
  </a>
  <a href="https://github.com/J0JIN">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

## About Me

Python/Django 기반 보안관제 플랫폼을 개발·운영하며,  
대량 보안 이벤트 처리, PostgreSQL 성능 개선, Splunk API 연동 최적화, SOAR 기반 자동 대응을 다루고 있습니다.

운영 환경에서 반복되는 문제를 단순 처리하지 않고,  
API·DB·배치·보안장비 연동 구조 개선을 통해 관제 지연과 장애 가능성을 줄이는 데 관심이 있습니다.

---

## Core Skills

### Backend & Platform
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white"/>
  <img src="https://img.shields.io/badge/REST%20API-005571?style=flat-square"/>
  <img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white"/>
</p>

### Database
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Query%20Tuning-334155?style=flat-square"/>
  <img src="https://img.shields.io/badge/EXPLAIN%20ANALYZE-334155?style=flat-square"/>
  <img src="https://img.shields.io/badge/LATERAL%20JOIN-334155?style=flat-square"/>
</p>

### Security Platform
<p>
  <img src="https://img.shields.io/badge/SOC%20Portal-0F172A?style=flat-square"/>
  <img src="https://img.shields.io/badge/SIEM-1E40AF?style=flat-square"/>
  <img src="https://img.shields.io/badge/Splunk%20API-000000?style=flat-square&logo=splunk&logoColor=white"/>
  <img src="https://img.shields.io/badge/SOAR-7C3AED?style=flat-square"/>
  <img src="https://img.shields.io/badge/WAF%2FIPS%20Integration-B91C1C?style=flat-square"/>
</p>

### Infra & Operation
<p>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white"/>
  <img src="https://img.shields.io/badge/Zero%20Downtime-475569?style=flat-square"/>
</p>

---

## Featured Work

### Splunk Event Pipeline Optimization

> SOC 환경에서 대량 보안 이벤트 유입 시 발생하던 Splunk 연동 지연 문제를 개선했습니다.

- `jobs.create + job.results / ResultsReader` 기반 수집 구조를 `search/jobs/export` streaming 방식으로 전환
- 중복 검사 로직을 HashSet 기반 조회 구조로 개선
- 1,000건 처리 시간 **30분 이상 → 약 5초**
- Docker 기반 benchmark와 Splunk Python SDK 내부 분석 수행

<p>
  <a href="https://github.com/J0JIN/splunk-api-benchmark">
    <img src="https://img.shields.io/badge/Repository-Splunk%20API%20Benchmark-181717?style=for-the-badge&logo=github"/>
  </a>
  <!-- <a href="https://github.com/splunk/splunk-sdk-python/pull/742">
    <img src="https://img.shields.io/badge/OpenSource%20PR-Splunk%20SDK-000000?style=for-the-badge&logo=splunk"/>
  </a> -->
</p>

---

### PostgreSQL Query Performance Optimization

> SOC 포탈 대용량 조회 화면의 PostgreSQL 실행계획을 분석하고 조회 성능을 개선했습니다.

- Full Scan 발생 구간을 EXPLAIN 기반으로 분석
- 복합 인덱스, LATERAL JOIN, HOT/COLD 데이터 분리 적용
- 주요 조회 화면 응답시간 **10초 → 0.5초**, **30초 → 0.3초**

---

### SOAR Security Automation

> SOAR를 보안장비 API Relay/실행 계층으로 활용하여 자동 대응 구조를 설계했습니다.

- Imperva WAF 기반 고객사 SaaS형 서비스 40개 연동
- 온프레미스 WINS IPS 16대 연동
- DDoS 임계치 기반 자동 차단 플레이북 구현
- 수동 차단·해제 작업 **3~5분 → 30초 이내**

---

## Writing

<p>
  <a href="https://blog.naver.com/my-dev-note">
    <img src="https://img.shields.io/badge/Technical%20Blog-Naver-03C75A?style=for-the-badge&logo=naver&logoColor=white"/>
  </a>
  <a href="https://velog.io/@tl5235566/posts">
    <img src="https://img.shields.io/badge/Dev%20Notes-Velog-20C997?style=for-the-badge&logo=velog&logoColor=white"/>
  </a>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1e40af,100:0f172a&height=120&section=footer"/>
</p>
