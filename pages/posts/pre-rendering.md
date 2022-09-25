---
title: "두 가지 형태의 Pre-rendering(사전 렌더링)"
date: "2022-09-23"
---

Next.js에는 **Static Generation** 및 **Server-side Rendering**의 두 가지 사전 렌더링 형식이 있습니다. 차이점은 페이지의 HTML을 생성하는 **때**입니다.

- **Static Generation**은 **build time**에 HTML을 생성하는 사전 렌더링 방법입니다. 사전 렌더링된 HTML은 각 요청에서 *재사용*됩니다.
- **Server-side Rendering**은 **각 Request**에 대해 HTML을 생성하는 사전 렌더링 방법입니다.

중요한 것은 Next.js를 사용하면 각 페이지에 사용할 사전 렌더링 양식을 **선택**할 수 있다는 점입니다. 대부분의 페이지에는 정적 생성을 사용하고 다른 페이지에는 서버 측 렌더링을 사용하여 "하이브리드" Next.js 앱을 만들 수 있습니다.
