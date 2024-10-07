# 소요단풍체

[배포처 바로가기](https://www.ddc.go.kr/ddc/contents.do?key=2052)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `SOYO Maple`입니다.

### HTML

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/fonts-archive/SOYOMaple/SOYOMaple.css"
  type="text/css"
/>
```

### CSS `@Import`

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/SOYOMaple/SOYOMaple.css");
```

### CSS `@font-face`

```css
@font-face {
  font-family: "SOYO Maple";
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/fonts-archive/SOYOMaple/SOYOMaple-Regular.woff2")
      format("woff2"), url("https://cdn.jsdelivr.net/gh/fonts-archive/SOYOMaple/SOYOMaple-Regular.woff")
      format("woff"),
    url("https://cdn.jsdelivr.net/gh/fonts-archive/SOYOMaple/SOYOMaple-Regular.otf")
      format("opentype"), url("https://cdn.jsdelivr.net/gh/fonts-archive/SOYOMaple/SOYOMaple-Regular.ttf")
      format("truetype");
}
@font-face {
  font-family: "SOYO Maple";
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url("https://cdn.jsdelivr.net/gh/fonts-archive/SOYOMaple/SOYOMaple-Bold.woff2")
      format("woff2"), url("https://cdn.jsdelivr.net/gh/fonts-archive/SOYOMaple/SOYOMaple-Bold.woff")
      format("woff"),
    url("https://cdn.jsdelivr.net/gh/fonts-archive/SOYOMaple/SOYOMaple-Bold.otf")
      format("opentype"), url("https://cdn.jsdelivr.net/gh/fonts-archive/SOYOMaple/SOYOMaple-Bold.ttf")
      format("truetype");
}
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "SOYO Maple", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
  Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
- 본 서체는 글꼴 자체를 유료로 판매하거나 왜곡 변형할 수 없습니다.
- 디자인물에 적용 시 권장 자간, 사이즈와 사용 지양 사례를 참고하여 적정 크기로 사용을 권장합니다.
- 개인 및 기업 사용자를 포함한 모든 사용자에게 무료로 제공되며, 자유롭게 사용할 수 있고 상업적 이용이 가능합니다.
- 소요단풍체의 지적 재산권은 동두천시청에 있습니다.
```
