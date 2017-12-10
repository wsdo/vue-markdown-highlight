# vue-markdown-highlight


📜 [Highlight.js](https://github.com/isagalaev/highlight.js) syntax highlighter component for [Vue](https://vuejs.org).

## ⚙️ Installation



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

