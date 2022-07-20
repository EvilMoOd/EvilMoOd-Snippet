# EvilMoOd Snippet

一个包搞定各种snippet，补充vscode内置没有的代码片段，做到刚刚好够用！！！😁
vue借鉴Vue Vscode Snippet，react借鉴react Snippet。
全面拥抱Vue3和react函数组件，不适用vue2和react类组件

## Common for JavaScript and TypeScript

### Base

| Snippet      | Purpose            |
| -----------  | -------------------|
|`cl`          | console.log        |
|`c`           | const              |
|`cf`          | const name = ()=>{}|
|`l`           | let                |
|`ei`          | else if            |
|`el`          | else               |
|`a`           | ()=>               |
|`ar`          | ()=>{}             |

### Array

| Snippet      | Purpose                     |
| -----------  | ----------------------------|
|`map`         | map function                |
|`forEach`     | forEach function            |
|`reduce`      | reduce function             |
|`filter`      | filter function             |
|`find`        | find function               |
|`findIndex`   | findIndex function          |

### Promise

| Snippet      | Purpose                     |
| -----------  | ----------------------------|
|`then`        | then function               |
|`catch`       | catch function              |

### node

| Snippet            | Purpose                     |
| -----------------  | ----------------------------|
|`require`           | require a package           |
|`exports`           | exports a package           |
|`module exports`    | exports default a package   |

### module

| Snippet            | Purpose                     |
| -------------------| ----------------------------|
|`imf`               | import a package            |
|`im`                | import a file url           |
|`ex`                | export  a package           |
|`exd`               | export default a package    |

### code block

| Snippet            | Purpose                     |
| -------------------| ----------------------------|
|`block`             | a code block 可折叠代码块     |

### TS （大部分代码片段都内置在vscode中，所以只补充没有的）

| Snippet          | Purpose                     |
| -----------------| ----------------------------|
|`type`              | type =                      |
|`interface`         | interface name {}           |
|`setinterval`       | 定时器                       |

## Vue

### base

| Snippet          | Purpose                     |
| -----------------| ----------------------------|
|`vue`               | Vue Base Template TS SCSS   |

### Vue Composition API

| Snippet           | Purpose                                               |
| ------------------| ----------------------------------------------------- |
| `ref`             | Vue Ref                                               |
| `reactive`        | Vue Composition API - reactive                        |
| `computed`        | Vue Composition API - computed                        |
| `watch`           | Vue Composition API - watcher single source           |
| `watch-array`     | Vue Composition API - watch as array                  |
| `watcheffect`     | Vue Composition API - watchEffect                     |
| `onmounted`       | Lifecycle hook - onMounted                            |
| `onbeforemount`   | Lifecycle hook - onBeforeMount                        |
| `onbeforeupdate`  | Lifecycle hook - onBeforeUpdate                       |
| `onupdated`       | Lifecycle hook - onUpdated                            |
| `onerrorcaptured` | Lifecycle hook - onErrorCaptured                      |
| `onunmounted`     | Lifecycle hook - (destroyed) onUnmounted              |
| `onbeforeunmount` | Lifecycle hook - (beforeDestroy) onBeforeUnmount      |

### Vue Router

| Snippet              | Purpose                                       |
| -------------------- | --------------------------------------------- |
| `vroute`             | Vue Route base                               |
| `vrouter`            | Vue Router base                               |
| `vscrollbehavior`    | Vue Router scrollBehavior                     |
| `vbeforeeach`        | Vue Router global guards beforeEach           |
| `vbeforeresolve`     | Vue Router global guards beforeResolve        |
| `vaftereach`         | Vue Router global guards afterEach            |
| `vbeforeenter`       | Vue Router per-route guard beforeEnter        |
| `vbeforerouteenter`  | Vue Router component guards beforeRouteEnter  |
| `vbeforerouteupdate` | Vue Router component guards beforeRouteUpdate |
| `vbeforerouteleave`  | Vue Router component guards beforeRouteLeave  |

### Pinia

| Snippet  | Purpose   |
| ---------| ----------|
| `pinia`  | PiniaBase |

### Template

| Snippet           | Purpose                             |
| ----------------- | ----------------------------------- |
| `vfor`            | v-for directive                     |
| `vmodel`          | Semantic v-model directive          |
| `vmodel-num`      | Semantic v-model number directive   |
| `von`             | v-on click handler with arguments   |
| `vslot-named`     | Named slot                          |
| `vel-props`       | Component element with props        |
| `vsrc`            | Image src binding                   |
| `vstyle`          | Inline style binding                |
| `vstyle-obj`      | Inline style binding with objects   |
| `vclass`          | Class binding                       |
| `vclass-obj`      | Class binding with objects          |
| `vclass-obj-mult` | Multiple conditional class bindings |
| `vanim`           | Transition component with JS hooks  |
| `vnuxtl`          | Nuxt Routing Link                   |
| `vroutename`      | router-link Named Routing           |
| `vroutenameparam` | router-link Named with Parameters   |
| `vroutepath`      | router-link Path Routing Link       |

## React

### base

| Snippet               | Purpose                             |
| --------------------- | ----------------------------------- |
| `rfc`                 | React Function Template             |
| `memo`                | React memo Function Template        |

### Hook

| Snippet               | Purpose                             |
| --------------------- | ----------------------------------- |
| `useState`            | useState Hook                       |
| `useContext`          | useContext Hook                     |
| `useEffect`           | useEffect Hook                      |
| `useLayoutEffect`     | useLayoutEffect Hook                |
| `useMemo`             | useMemo Hook                        |
| `useCallback`         | useCallback Hook                    |
| `useRef`              | useRef Hook                         |

### Template

| Snippet               | Purpose                             |
| --------------------- | ----------------------------------- |
| `className`           | scss module classname               |
| `onClick`             | onClick and arrow function          |
