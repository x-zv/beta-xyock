# 🌌 Xyock / xykck Wiki

> xyock의 프로젝트, **xykck**에 대한 공식 위키입니다.
> 모든 정보는 연결된 GitHub 저장소 `x-zv/beta-xyock`의 실제 내용을 기반으로 작성되었습니다.

---

## 🚀 프로젝트 소개

`Xyock / xykck`는 xyock이 구축하는 실험적 웹 프로젝트 베타입니다.
미니멀한 디자인과 직관적인 인터페이스를 지향하며, 현재 저장소에는 정적 페이지와 간편 계산기 도구가 포함되어 있습니다.

---

## 📂 저장소 구조 (실제 파일 기준)

| 경로 | 설명 |
|------|------|
| `index.html` | 메인 진입점 / 계산기 페이지 |
| `계산기.html` | 전용 계산기 페이지 |
| `beta.html` | 베타 버전 페이지 |
| `x.html` | 보조 페이지 |
| `.github/workflows/pages.yml` | GitHub Pages 배포 워크플로 |
| `.nojekyll` | Jekyll 처리 비활성화 파일 |

> 위 목록은 연결된 저장소의 실제 파일 목록을 반영합니다.

---

## 🧮 계산기 기능

`index.html`에 내장된 계산기는 다음과 같은 기능을 제공합니다.

- 기본 사칙연산: 덧셈, 뺄셈, 곱셈, 나눗셈
- 소수점 입력 및 초기화 (`C`)
- 연산자 연속 입력 시 자동 계산
- 0으로 나누기 시 오류 처리

사용 예:

```html
<button onclick="appendNumber('7')">7</button>
<button class="operator" onclick="appendOperator('+')">+</button>
<button class="equal" onclick="calculate()">=</button>
```

---

## 🛠 시작하기

1. 저장소를 클론합니다.
   ```bash
   git clone https://github.com/x-zv/beta-xyock.git
   ```
2. `index.html` 또는 원하는 HTML 파일을 브라우저에서 엽니다.
3. GitHub Pages로 배포하려면 `.github/workflows/pages.yml` 설정을 확인하세요.

---

## 🤝 기여 방법

xyock의 프로젝트에 기여하고 싶다면:

1. 이슈로 버그나 제안을 등록하세요.
2. 포크 후 브랜치를 만들어 수정합니다.
3. 풀 리퀘스트를 보내주세요.

모든 기여는 존중과 협력을 바탕으로 진행됩니다.

---

## 📜 라이선스

별도 명시가 없는 한, 저장소 내 파일들은 각 파일의 기존 고지 사항을 따릅니다.

---

> Made with ❤️ by xyock
> `xykck` 위키는 프로젝트와 함께 지속적으로 업데이트됩니다.