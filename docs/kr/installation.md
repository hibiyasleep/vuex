# 설치

### 직접 다운로드 / CDN

[https://unpkg.com/vuex](https://unpkg.com/vuex)

<!--email_off-->
[Unpkg.com](https://unpkg.com)은 NPM 기반의 CDN 링크를 제공합니다. 위의 링크는 항상 NPM에 올라온 최신 릴리스를 가리키며, `https://unpkg.com/vuex@2.0.0` 같은 URL을 이용해 특정 버전이나 태그를 사용할 수도 있습니다.
<!--/email_off-->

Vue 뒤에 `vuex`를 추가하면 자동으로 설치됩니다:

``` html
<script src="/path/to/vue.js"></script>
<script src="/path/to/vuex.js"></script>
```

### NPM

``` bash
npm install vuex --save
```

### Yarn

``` bash
yarn add vuex
```

모듈 시스템과 함께 사용한다면, `Vue.use()`로 Vuex를 명시적으로 등록해야 합니다:

``` js
import Vue from 'vue'
import Vuex from 'vuex'

Vue.use(Vuex)
```

간단한 스크립트 태그를 사용한다면 필요 없는 작업입니다.

### 개발용 빌드

최신 dev 빌드를 사용하려면 직접 GitHub에서 `vuex`를 클론해서 빌드해야 합니다.

``` bash
git clone https://github.com/vuejs/vuex.git node_modules/vuex
cd node_modules/vuex
npm install
npm run build
```
