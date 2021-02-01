# Advanced Front-End Frameworks


**1.** Describe the two ways to bind Data in Vue?
<!-- enter you answer in the space below -->
```
The first form is interpolation, using {{thing}}, and it will be updated whenever the object of "thing" changes. There are also directives, which used the v- prefix as binding expressions.
```

**2.** The `SPA` acronym stands for what?
<!-- enter you answer in the space below -->
```
SPA stands for Single Page Application.
```
**3.** What are some of the advantages/uses of a `SPA` over a traditional one?
<!-- enter you answer in the space below -->
```
Single Page Applications can be faster to load. They are also easier to debug.
```
**4.** What does the `onMounted` method in Vue do?
<!-- enter you answer in the space below -->
```
onMounted is a lifecycle hook in Vue. It is called when the component is mounted.
```
**5.** What is the `v-model` attribute in Vue for, and when might you use it?
<!-- enter you answer in the space below -->
```
v-model is used for data binding on form elements.
```
**6.** The `v:on` (`@`) directive can be used for what?
<!-- enter you answer in the space below -->
```
v:on and @ are used to listen to event triggers.
```
**7.** Which Vue attributes(directives) could you use to conditionally render elements on a page?
<!-- enter you answer in the space below -->
```
v-if is the most common one I use. v-show could be used as well.
```
**8.** What is the purpose of the `key` attribute when using `v-for` on an element?
<!-- enter you answer in the space below -->
```
The key should by a unique id in the v-for, so Vue has something to use to easily find and update specific elements.
```
**9.** What is the `<slot>` element and what is it used for?
<!-- enter you answer in the space below -->
```
The slot element can contain any template code, and is replaced by whatever you insert into the same spot when creating the component.
```