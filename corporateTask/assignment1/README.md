[Assignment 1] 하얀마인드
======  
<br/>

## Objective
`Infinite Scroll 구현하기`

<br/>

## 팀 구성원

- 조영후
- 오선주
- 김준영

<br/>

## 설치 및 실행 방법
* 설치  
`npm install `

* 실행  
`npm start`

<br/>

## 구현된 영상

![인피니트스크롤](https://user-images.githubusercontent.com/67793530/127171267-13a4330b-d63d-4c46-b30e-aa25d6a29bc9.gif)

<br/>

## 공동 구현 사항
- `IntersectionObserver`를 이용한 무한스크롤 구현
  - 빈 `footer`를 `observe target`으로 사용
  - `IntersectionObserver`의 `option` 중 `rootMargin`을 적절히 주어 사용자 사용성 고려
- 데이터를 더 이상 호출할 수 없을 경우도 핸들하여 Side Effect 방지
- figma의 카드 디자인 style 값을 철저히 지키며 구현
  - figma 링크 : https://www.figma.com/file/T9P3B5qjnTqhWi1Ou5BmIL/HayanMind-FrontEnd-TA?node-id=0%3A1
- 폴더 구조 논의 및 적용
  - 컴포넌트별 index.js, style.css를 두면서 모듈화
  - 이를 통해 컴포넌트별 수정 및 관리 용이

<br/>

## 개인 추가 구현 사항
- useIntersectionObserver 커스텀훅을 추가하여 효율적 재사용성 고려
- 코드 컨벤션 재정리
