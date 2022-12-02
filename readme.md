# Vue 3 with options API
- import 
```<script src="https://unpkg.com/vue@3"></script>```
- reactivity 
```<h1>{{header}}</h1>
<input v-model="header">
```

- ability to edit from console 
```const taskList = Vue.createApp({```

we can use JS expression inside 

- in case of list and looping - we need use key in `v-for`
The purpose of this key attribute is to give "a hint for Vue's virtual DOM algorithm to identify VNodes when diffing the new list of nodes against the old lis

clever way with destructing :
```<li v-for="{id, label} in items" :key="id"> {{label}}</li>```

```  <input 
        v-on:keyup.enter=
```        
could be replaced iwth
`@keyup.enter`
