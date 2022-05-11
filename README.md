# Livewire - Programação Reativa ⚛️
Este repositório consiste em anotações úteis para quem está inciando com o Livewire.

## O que é Livewire? 🤔
O Livewire é um framework baseado no Laravel para criar interfaces dinamicas. 

### Pontos importantes do seu funcionamento

- Quando ocorre uma interação, o Livewire faz uma solicitação AJAX ao servidor com os dados atualizados.
- O servidor renderiza novamente o componente e responde com o novo HTML.
- O Livewire então muda o DOM de forma inteligente de acordo com as coisas que mudaram.


## Instalação

```bash 
composer require livewire/livewire
``` 

> Incluindo os estilos e scripts do Livewire no template do projeto

```html
...

    @livewireStyles

</head>

<body>

    ...

    @livewireScripts

</body>

</html>
```

> Criando um  componente

```bash
php artisan make:livewire nome_componente
```
