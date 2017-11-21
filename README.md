![Bússola CSS3/HTML5 Logo](http://djalmatoledo.com.br/bussola-css3-html5/logo-bussola.png)

# Bússola com CSS3 e HTML5

[![Travis](https://img.shields.io/badge/CSS-3-lightgrey.svg?style=plastic)]()
[![Travis branch](https://img.shields.io/badge/HTML-5-blue.svg?style=plastic)]()

Neste projeto foi criado uma Bússola utilizando apenas CSS3 e HMTL5 para criar todo desenho e a animação do ponteiro.

Este é um projeto um pouco antigo que foi proposto pelo Bernard De Luna no site do iMasters, o desafio de criar uma bússola utilizando apenas CSS3 e HMTL5. Decidi então colocar meus conhecimentos a prova e tirei o dia pra desenvolver esse desafio.

Se você quiser ver como ficou, clique para ver na [página de demonstração](http://djalmatoledo.com.br/bussola-css3-html5/).

### Como desenhado com CSS? ###

A primeira coisa que fiz foi buscar uma série de imagens de bússola e ver o que era possível fazer com CSS. Percebi que não ia precisar usar nada além do que já usava no meu dia-a-dia no desenvolvimento aqui na contagia.

Decidi criar um elemento dentro do outro e apliquei border-radius (deixa a borda arredondada) e um tamanho diferente para cada elemento, para dar uma profundidade e criar os ponteiros dentro do último elemento com a borda redondada. Para criar o ponteiro decidi colocar um :after para cada ponteiro (span) e usei o conceito de criar setas utilizando Border, como mostrado neste artigo do Danilo e posicionei os ponteiros com position: absolute alterando o top e o left de cada ponteiro.

Para o ponteiro girar quando o mouse está sobre a bússola eu utilizei o CSS transition que muda o ângulo (transform:rotate(387deg)) no hover do elemento. Basicamente foi isso que usei de diferente para desenvolver a bússola o resto quem é desenvolvedor Front-End já está habituado a fazer. Acesse o link e veja a Bússola em funcionamento.


### Como contribuir? ###

Decidi reativar este projeto pois acredito ser possível fazer o ponteiro sempre apontar para o norte utilizando acelerômetro do celular ou notebooks.

Como ainda não trabalhei com acelerômetro e vou levar algum tempo para aprender. Proponho para os amigos desenvolvedores este desafio de faze-la funcionar.

Fiquem à vontade para contribuir!