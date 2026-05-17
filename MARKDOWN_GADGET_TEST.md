# Markdown Gadget Test Lab

> GitHub README에서 쓸 수 있는 배지, 카드, 그래프, 이미지, 애니메이션, 접기 UI, Mermaid 다이어그램 등을 한곳에 모아둔 테스트 파일입니다.
>
> 일부 이미지는 외부 동적 서비스에 의존하므로 GitHub/서비스 상태, 캐시, rate limit에 따라 잠시 안 보일 수 있습니다.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=180&color=gradient&text=Jungoari%20Markdown%20Lab&fontAlign=50&fontAlignY=35&animation=fadeIn&desc=badges%20%7C%20cards%20%7C%20graphs%20%7C%20animations&descAlign=50&descAlignY=58" alt="header" />
</p>

<p align="center">
  <a href="https://github.com/Jungoari"><img src="https://img.shields.io/badge/GitHub-Jungoari-181717?style=for-the-badge&logo=github" alt="GitHub" /></a>
  <img src="https://img.shields.io/badge/Markdown-Test%20File-7C3AED?style=for-the-badge&logo=markdown&logoColor=white" alt="Markdown Test" />
  <img src="https://img.shields.io/badge/Status-Experiment-FFB000?style=for-the-badge" alt="Status" />
  <img src="https://img.shields.io/badge/Prusa-Enclosure-orange?style=for-the-badge&logo=prusa" alt="Prusa" />
</p>

---

## 1. Shields.io 배지

Shields.io는 README에서 가장 많이 쓰는 작은 상태 박스입니다. Prusa-Enclosure의 `status work in progress` 같은 느낌을 만들 때 좋습니다.

![status](https://img.shields.io/badge/status-work%20in%20progress-orange)
![version](https://img.shields.io/badge/version-v0.1.0-blue)
![license](https://img.shields.io/badge/license-MIT-green)
![platform](https://img.shields.io/badge/platform-Raspberry%20Pi%20%7C%20WSL%20%7C%20GitHub-lightgrey)
![made-with](https://img.shields.io/badge/made%20with-Markdown-black?logo=markdown)
![stars](https://img.shields.io/github/stars/Jungoari/Prusa-Enclosure?style=social)
![last commit](https://img.shields.io/github/last-commit/Jungoari/Prusa-Enclosure)
![repo size](https://img.shields.io/github/repo-size/Jungoari/Prusa-Enclosure)

```md
![status](https://img.shields.io/badge/status-work%20in%20progress-orange)
![last commit](https://img.shields.io/github/last-commit/Jungoari/Prusa-Enclosure)
```

---

## 2. GitHub Readme Stats 카드

동적으로 GitHub 통계와 언어 비율을 보여주는 카드입니다.

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Jungoari&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jungoari&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />
</p>

```md
![stats](https://github-readme-stats.vercel.app/api?username=Jungoari&show_icons=true&theme=tokyonight)
![langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Jungoari&layout=compact&theme=tokyonight)
```

---

## 3. GitHub Streak 카드

연속 contribution streak를 보여주는 카드입니다.

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Jungoari&theme=tokyonight&hide_border=true&border_radius=12" alt="GitHub streak" />
</p>

```md
![streak](https://streak-stats.demolab.com?user=Jungoari&theme=tokyonight)
```

---

## 4. Activity Graph

최근 GitHub 활동 그래프입니다. README 하단에 넣으면 포트폴리오 느낌이 납니다.

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Jungoari&theme=tokyo-night&hide_border=true&radius=12&area=true" alt="activity graph" />
</p>

```md
![activity](https://github-readme-activity-graph.vercel.app/graph?username=Jungoari&theme=tokyo-night)
```

---

## 5. Trophy 카드

GitHub 활동을 트로피처럼 보여주는 장식입니다.

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Jungoari&theme=onedark&no-frame=true&row=1&column=6" alt="trophy" />
</p>

```md
![trophy](https://github-profile-trophy.vercel.app/?username=Jungoari&theme=onedark&no-frame=true)
```

---

## 6. Repository Pin 카드

특정 레포를 카드처럼 꽂아둘 수 있습니다.

<p align="center">
  <a href="https://github.com/Jungoari/Prusa-Enclosure">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Jungoari&repo=Prusa-Enclosure&theme=tokyonight&hide_border=true" alt="Prusa-Enclosure pin" />
  </a>
  <a href="https://github.com/Jungoari/CAN-RS4">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Jungoari&repo=CAN-RS4&theme=tokyonight&hide_border=true" alt="CAN-RS4 pin" />
  </a>
</p>

---

## 7. Capsule Render 헤더/푸터

README 맨 위나 아래에 웨이브, 실린더, blur, gradient 같은 큰 SVG 장식을 넣을 수 있습니다.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&height=180&color=0:0EA5E9,100:8B5CF6&text=Hardware%20%2B%20AI%20%2B%20IoT&fontColor=ffffff&animation=twinkling&fontSize=34" alt="capsule" />
</p>

```md
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&text=Hello" />
```

---

## 8. 움직이는 텍스트 / Typing SVG

타이핑되는 것처럼 보이는 SVG입니다.

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=2600&pause=700&color=38BDF8&center=true&vCenter=true&width=760&lines=Prusa+Enclosure+%7C+Klipper+%7C+Sensors;CAN+Gimbal+Control+%7C+Raspberry+Pi+%7C+IoT;Markdown+can+look+alive+without+JavaScript" alt="Typing SVG" />
</p>

---

## 9. HTML 정렬과 이미지 카드

GitHub Markdown은 일부 HTML을 허용합니다. `p align`, `img width`, `picture` 태그를 활용할 수 있습니다.

<p align="center">
  <a href="https://github.com/Jungoari/Prusa-Enclosure">
    <img width="360" src="https://raw.githubusercontent.com/Jungoari/Prusa-Enclosure/main/docs/images/01_overall_enclosure.jpg" alt="Prusa enclosure" />
  </a>
</p>

<p align="center"><sub>이미지를 클릭하면 Prusa-Enclosure 레포로 이동합니다.</sub></p>

---

## 10. Details / 접기 UI

길이가 긴 설명, 설치법, 로그, 코드 등을 접어서 숨길 수 있습니다.

<details>
<summary><strong>클릭해서 Prusa-Enclosure 설명 펼치기</strong></summary>

- Prusa MK3S 기반 커스텀 인클로저
- Klipper 전환
- HEPA + 활성탄 필터
- PMS7003 / SGP30 / DHT22 센서
- OLED 대시보드
- 센서 데이터 기반 노즐 막힘 조기 감지 실험

</details>

```md
<details>
<summary>펼치기</summary>
숨겨진 내용
</details>
```

---

## 11. Mermaid 다이어그램

GitHub는 Mermaid 다이어그램 렌더링을 지원합니다. 프로젝트 구조, 데이터 흐름, 상태 전이를 문서화할 때 좋습니다.

```mermaid
flowchart LR
    A[Sensor Data] --> B[Raspberry Pi]
    B --> C[Python Pipeline]
    C --> D[Dashboard]
    C --> E[GitHub README]
    D --> F[Human Feedback]
```

```mermaid
sequenceDiagram
    participant User
    participant README
    participant ExternalSVG
    User->>README: open markdown
    README->>ExternalSVG: request badge/card image
    ExternalSVG-->>README: SVG/PNG response
    README-->>User: rendered visual card
```

---

## 12. GitHub 기본 Markdown 체크리스트

- [x] Badge 테스트
- [x] Stats 카드 테스트
- [x] Activity graph 테스트
- [x] Mermaid 테스트
- [ ] 실제 프로필 README에 적용할 항목 선별
- [ ] Prusa-Enclosure README에 어울리는 장식만 추려서 반영

---

## 13. 표 + 이모지 + 링크 카드 느낌

| Feature | Use Case | Example |
|---|---|---|
| 🛡️ Shields | 상태/버전/기술스택 | `status`, `license`, `last commit` |
| 📊 Stats | GitHub 계정 통계 | GitHub Readme Stats |
| 🔥 Streak | 꾸준함 강조 | Streak Stats |
| 📈 Graph | 활동량 시각화 | Activity Graph |
| 🏆 Trophy | 프로필 장식 | GitHub Profile Trophy |
| 🌊 Capsule | 큰 헤더/푸터 | Capsule Render |
| ⌨️ Typing | 움직이는 자기소개 | Readme Typing SVG |
| 🧭 Mermaid | 구조도/흐름도 | flowchart, sequenceDiagram |

---

## 14. Prusa-Enclosure에 바로 쓸 만한 조합 예시

```md
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=160&color=0:111827,100:f97316&text=Prusa%20Enclosure%20V1.0&fontColor=ffffff&animation=fadeIn" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/status-work%20in%20progress-orange" />
  <img src="https://img.shields.io/badge/firmware-Klipper-blue" />
  <img src="https://img.shields.io/badge/sensors-PMS7003%20%7C%20SGP30%20%7C%20DHT22-green" />
  <img src="https://img.shields.io/badge/filter-HEPA%20%2B%20Carbon-black" />
</p>
```

---

## 15. 주의할 점

- 외부 동적 SVG 서비스는 rate limit이나 장애가 있을 수 있습니다.
- 너무 많은 이미지를 README 첫 화면에 넣으면 로딩이 느려질 수 있습니다.
- 중요한 프로젝트 README에서는 장식보다 정보 구조가 우선입니다.
- API 키, 토큰, 계정번호 등 민감 정보는 절대 badge URL이나 이미지 URL에 넣으면 안 됩니다.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=gradient" alt="footer" />
</p>
