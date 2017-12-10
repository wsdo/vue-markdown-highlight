# vue-markdown-highlight
[![license](https://img.shields.io/github/license/gluons/vue-markdown-highlight.svg?style=flat-square)](https://github.com/gluons/vue-markdown-highlight/blob/master/LICENSE)
[![vue 2](https://img.shields.io/badge/vue-2-42b983.svg?style=flat-square)](https://vuejs.org)
[![npm](https://img.shields.io/npm/v/vue-markdown-highlight.svg?style=flat-square)](https://www.npmjs.com/package/vue-markdown-highlight)
[![npm](https://img.shields.io/npm/dt/vue-markdown-highlight.svg?style=flat-square)](https://www.npmjs.com/package/vue-markdown-highlight)
[![Travis](https://img.shields.io/travis/gluons/vue-markdown-highlight.svg?style=flat-square)](https://travis-ci.org/gluons/vue-markdown-highlight)
[![Codacy grade](https://img.shields.io/codacy/grade/3d15a7c11bfe47c69a2aed93cc67cc29.svg?style=flat-square)](https://www.codacy.com/app/gluons/vue-markdown-highlight)
[![Gemnasium](https://img.shields.io/gemnasium/gluons/vue-markdown-highlight.svg?style=flat-square)](https://gemnasium.com/github.com/gluons/vue-markdown-highlight)
[![ESLint Gluons](https://img.shields.io/badge/code%20style-gluons-9C27B0.svg?style=flat-square)](https://github.com/gluons/eslint-config-gluons)

📜 [Highlight.js](https://github.com/isagalaev/highlight.js) syntax highlighter component for [Vue](https://vuejs.org).

https://github.com/wsdo/vue-markdown-highlight.git
## ⚙️ Installation

**Via [NPM](https://www.npmjs.com):**

[![NPM](https://nodei.co/npm/vue-markdown-highlight.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/vue-markdown-highlight)


1. Install [**highlight.js**](https://github.com/isagalaev/highlight.js):

   ```bash
   npm i highlight.js
   ```

2. Install **vue-markdown-highlight**:

   ```bash
   npm i vue-markdown-highlight -D
   ```

**Or [Yarn](https://yarnpkg.com):**

1. Install [**highlight.js**](https://github.com/isagalaev/highlight.js):

   ```bash
   yarn add highlight.js
   ```

2. Install **Vue Highlight.js**:

   ```bash
   yarn add vue-markdown-highlight
   ```


## 🛂 Usage

**Main file:**

```javascript

import 'highlight.js/styles/default.css';
import Highlight from 'vue-markdown-highlight'
Vue.use(Highlight)

```

**Vue file:**

```vue
<template>
	<div id="app">
      <div v-html="content" v-highlight></div>
	</div>
</template>

<script>
// JavaScript...
</script>

<style>
/* StyleSheet... */
</style>
```
