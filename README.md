# 엘리스 디지털코딩체

[배포처 바로가기](https://elice.io/ko/elice/brand#elice_digital_coding)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Elice Digital Coding`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/EliceDigitalCoding/EliceDigitalCoding.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/EliceDigitalCoding/EliceDigitalCoding.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Elice Digital Coding';
    font-weight: 400;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/EliceDigitalCoding/EliceDigitalCoding-Regular.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/EliceDigitalCoding/EliceDigitalCoding-Regular.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/EliceDigitalCoding/EliceDigitalCoding-Regular.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/EliceDigitalCoding/EliceDigitalCoding-Regular.ttf') format('truetype');
}
@font-face {
    font-family: 'Elice Digital Coding';
    font-weight: 700;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/EliceDigitalCoding/EliceDigitalCoding-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/EliceDigitalCoding/EliceDigitalCoding-Bold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/EliceDigitalCoding/EliceDigitalCoding-Bold.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/EliceDigitalCoding/EliceDigitalCoding-Bold.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/EliceDigitalCoding/subsets/EliceDigitalCoding-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/EliceDigitalCoding/subsets/EliceDigitalCoding-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.



```css
font-family: "Elice Digital Coding", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
(주)엘리스에서 무료로 배포하는 '엘리스 디지털 배움체', '엘리스 디지털 코딩체'의 지식재산권은 (주)엘리스가 보유하고 있으며 SIL Open Font License를 따릅니다. 
 
모든 개인/기업/단체는 '엘리스 디지털 배움체', '엘리스 디지털 코딩체'의 사용, 연구 및 적용, 수정과 재배포가 가능합니다. 
 
본 라이선스 하에 배포해야 하며 다른 라이선스 하에서는 배포할 수 없습니다. 
더욱 자세한 내용은 OFL-FAQ를 참고하세요. 
 
- 폰트는 (주)엘리스의 자산입니다. 
- 폰트는 재사용할 수 있으며 모든 파생 작업은 본 라이선스를 따릅니다. 
- 모든 종류의 문서에 폰트를 포함할 수 있습니다. 
- 파생 · 수정한 폰트는 기존 폰트의 이름을 사용할 수 없습니다. 
- 폰트는 단독으로 판매할 수 없습니다. 
 
폰트 사용 및 기타 문의 contact@elice.io
```
