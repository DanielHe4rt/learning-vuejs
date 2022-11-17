# Estudo VueJS

### Diferenças do Vue2 pro Vue3

* Como ele é criado (scaffold)
* Multiplos componentes raiz no mesmo arquivo
* Fragments (Estados) -> estudar mais 
* Nova possibilidade de fugir do Options API (n gostei)
* Beleza já entendi que vo te q aprender esse tal de Composition API
* Novo jeito de acessar os ciclos de vida de um hook `onMounted()`
* Propriedades Computadas são legais obrigado vue3.
* Você pode passar as props diretamente no setup, isolar contexto e evitar de chamar o `this` em tudo que é lado.
* Portal ?????????????????????

Sumário
* Vue3 é mais rapido, menor e mais fácil de manter que o Vue2
* Vue3 é marromeno a mesma coisa que o Vue2 porém com mais features significativas
* A sintaxe não mudou muito, já que você pode usar a Option API do jeito que ela foi desenhada no Vue2.


### Como iniciar o Vue3

Você pode iniciar tanto usando o NPM/Yarn e baixar o Vue3 quanto pegar diretamente de um CDN como o `unpkg`. 

Uma coisa bem interessante na sua construção do método é que ele passa uma função `mount()` esperando um parâmetro de algum elemento dentro da sua pagina pra ser a referência. 

Por padrão, a comunidade chama de `#app`. 

```html

<div id="app">
    <!--Elementos a serem adicionados a sua aplicação VUE-->
</div>
<script>
    Vue.createApp({
        // suas funções do app Vue
    }).mount("#app")
    
</script>
```

### Diferenças entre Options API vs Composition API

Options API separa partes da sua aplicação de uma maneira não tão agradável, com alguns vários métodos e etapas.

Com Composition API você consegue carregar tudo no setup e criar um ambiente reativo usando hooks disponíveis. Além disso é possível compartilhar código com "Composables".

### Composition API


### Diretivas básicas do Vue3



### Criando um Hello World

