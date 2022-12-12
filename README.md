# EvilMoOd Snippet

一个包搞定各种snippet，补充vscode内置没有的代码片段，做到刚刚好够用！！！😁
vue借鉴Vue Vscode Snippet，react借鉴react Snippet。
全面拥抱Vue3和react函数组件，不适用vue2和react类组件

## Common for JavaScript and TypeScript

### Base

| Snippet      | Purpose            |
| -----------  | -------------------|
|`cl`          | console.log        |
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
|`sort`        | sort function               |

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
| `defineProps`     | Vue Composition API - defineProps                     |
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

| Snippet                | Purpose                             |
| -----------------      | ----------------------------------- |
| `v-for`                | v-for directive                     |
| `v-for-element`        | v-for directive                     |
| `v-input`              | Input with modelValue               |
| `v-component`          | Named component                     |
| `v-slot`               | Named slot                          |
| `v-img`                | Image src binding                   |
| `v-style`              | Inline style binding                |
| `v-class`              | Class binding                       |
| `v-transition`         | Transition component with JS hooks  |
| `v-transition-group`   | Transition component with JS hooks  |
| `v-router-view`        | router-view Named Routing           |
| `v-router-link`        | router-link Named Routing           |
| `v-router-link-params` | router-link Named with Parameters   |
| `v-router-path`        | router-link Path Routing Link       |

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
| `useTransition`       | useTransition Hook                  |
| `useDeferredValue`    | useDeferredValue Hook               |
| `useContext`          | useContext Hook                     |
| `useReducer`          | useReducer Hook                     |
| `useSyncExternalStore`| useSyncExternalStore Hook           |
| `useMemo`             | useMemo Hook                        |
| `useCallback`         | useCallback Hook                    |
| `useEffect`           | useEffect Hook                      |
| `useLayoutEffect`     | useLayoutEffect Hook                |
| `useInsertionEffect`  | useInsertionEffect Hook             |
| `useRef`              | useRef Hook                         |
| `useImperativeHandle` | useImperativeHandle Hook            |

### Template

| Snippet               | Purpose                             |
| --------------------- | ----------------------------------- |
| `className`           | scss module classname               |
| `onClick`             | onClick and arrow function          |
