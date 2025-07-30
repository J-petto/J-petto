![header](https://capsule-render.vercel.app/api?&type=waving&color=0:73c4a9,100:0f8ad7)
[![Typing SVG](https://readme-typing-svg.demolab.com?font=D2coding&pause=300&color=316C48&random=false&width=435&lines=%EC%BD%94%EB%94%A9+%EA%B3%B5%EB%B6%80+ing...)](https://git.io/typing-svg)

## Profile

> 이름 : 황민지
>
> 생년월일 : 1999.07.15
>
> 좌우명 : 흘러가는대로 살자
>
> 블로그 : [제펫토 블로그](https://j-petto.github.io/)

#### Studying
<img src="https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=ffffff&labelColor=#000000"/>

#### Tech Stack
<img src="https://img.shields.io/badge/java-ED8B00?style=for-the-badge&logo=![img.png](img.png)&labelColor=#ED8B00"/> <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=ffffff&labelColor=#E34F26"/> <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=ffffff&labelColor=#F7DF1E"/> <img src="https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=ffffff&labelColor=#1572B6"/> <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=ffffff&labelColor=#6DB33F"/> <img src="https://img.shields.io/badge/unity-000000?style=for-the-badge&logo=unity&logoColor=ffffff&labelColor=#000000"/> <img src="https://img.shields.io/badge/react, react--native-61DAFB?style=for-the-badge&logo=react&logoColor=ffffff&labelColor=#61DAFB"/> <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=ffffff&labelColor=#4479A1"/> <img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=ffffff&labelColor=#2496ED"/> <img src="https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=ffffff&labelColor=#3178C6"/> <img src="https://img.shields.io/badge/postgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=ffffff&labelColor=#4169E1"/>


#### Tools
<img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=ffffff&labelColor=#F05032"/> <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=ffffff&labelColor=#181717"/> <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=ffffff&labelColor=#000000"/> <img src="https://img.shields.io/badge/intelli__J_idea-000000?style=for-the-badge&logo=intellijidea&logoColor=ffffff&labelColor=#000000"/> <img src="https://img.shields.io/badge/eclipse_ide-2C2255?style=for-the-badge&logo=eclipseide&logoColor=ffffff&labelColor=#2C2255"/> <img src="https://img.shields.io/badge/jira-0052CC?style=for-the-badge&logo=jira&logoColor=ffffff&labelColor=#0052CC"/> <img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=ffffff&labelColor=#F24E1E"/> <img src="https://img.shields.io/badge/postman-FF6C37?style=for-the-badge&logo=postman&logoColor=ffffff&labelColor=#FF6C37"/>


#### Project
[숨은 사람 친구] 축제, 공연 정보를 확인하고 같이 갈 사람을 모집하는 웹사이트
2025. 01  ~ 2025. 02

[→BackRepo](https://github.com/BackEndSchoolPlus3th/hfBackend) / [→FrontRepo](https://github.com/BackEndSchoolPlus3th/hfFrontend)

### 💬 맡은 부분
**팀장**, ElasticSearch 기반 검색 구현 및 CI / CD 담당

### ⚙️ 사용 기술
[GitAction] [Terraform] [ELK] [SpringBoot] [React + Typescript] [MySQL]

### 수행 업무
1. Git Convention 및 PR 리뷰 도입을 통한 병합 진행
    - 병합 중 충돌에 따른 갈등을 줄이기 위해 PR 리뷰 시스템 도입.
      <img width="1238" height="980" alt="2" src="https://github.com/user-attachments/assets/f01a90d1-611c-4d6f-89bc-9c77319ad68b" />
    - 팀원들의 코드를 미리 확인하고 충돌이 날 수 있는 부분을 인지 후 병합을 진행, 만약 병합 중 충돌이 일어나면 대면으로 해결하여 갈등을 최소화하였다. 총 **113개의 PR을 확인하고 Close함**
2. Terraform을 사용하여 AWS ec2, NCP Server 자동 구축
    - EC2와 NCP 서버를 Terraform을 통해 코드화, 동일한 스펙의 서버를 terraform apply, destroy 명령어로 간단하게 삭제하고 생성이 가능하게 구현했다. 이를 통해 서버의 일관성을 유지하고 자동화를 통해 효율성을 극대화했다.
3. GitAction과 Vercel을 이용한 백, 프론트 자동 배포
4. ElasticSearch 배포와 구현 및 K6 성능 테스트
    - K6를 통한 실제 배포 서버 QueryDSL 검색과 ElasticSearch 검색 속도 비교 진행
    QueryDSL : 평균 응답 속도 **3.78초**, 최대 응답 시간 **5.01초 
    →** ElasticSearch : 평균 응답 속도 **0.57초**, 최대 응답 시간 **1.5초로** 줄어듦 ****
    - 검색 API의 **평균 응답 속도**를 약 **86.6% 감소**시키고 **최대 응답 시간**도 약 **62.3% 단축**하여 성능 개선에 성공함
    
    ```bash
    # QueryDSL
    http_req_duration : 
    		avg=3.78s min=600.38ms med=4.2s max=5.01s p(90)=4.48s p(95)=4.64s
    		
    # ElasticSearch
    http_req_duration :
        avg=507.82ms min=92.5ms med=346.45ms max=1.89s p(90)=1.43s p(95)=1.51s
    ```
   
**미니 프로젝트**  
[1. CLI 가계부](https://jeppetto.notion.site/046c594a0e5249d98e1fe7de41c13e60)  
[2. CLI TodoList](https://jeppetto.notion.site/cdc4fc25125c4b6a917e6d44155e99c7)  
[3. CLI 도서대출시스템](https://jeppetto.notion.site/7a763fd599c8425ab0785687cd035e13)  
[4. CLI 빙고게임](https://jeppetto.notion.site/20ae059e95ea45ccbb1b65d698e0c6b8)  

---
<div align="center">

<a href="https://github.com/devxb/gitanimals">
<img
  src="https://render.gitanimals.org/farms/J-petto"
  width="600"
  height="300"
/>
</a>   


<!--![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=J-petto&hide=contribs,prs&show_icons=true)-->
![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=J-petto&theme=vue&hide_border=false)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=J-petto&layout=compact)

![footer](https://capsule-render.vercel.app/api?section=footer&type=waving&color=0:73c4a9,100:0f8ad7)

</div>

<!--
**J-petto/J-petto** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


