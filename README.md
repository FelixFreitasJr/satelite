# Projeto Satélite

Este é um projeto que criei para praticar meus conhecimentos em CSS. O projeto foi inspirado por um vídeo que vi no TikTok e decidi replicá-lo até conseguir fazer sozinho. O resultado é uma representação de um satélite orbitando um planeta.

## Sobre o Projeto

O projeto "Satélite" é um site simples que fiz para praticar minhas habilidades em CSS. Ele apresenta um design limpo e moderno, com animações suaves e responsivas que representam um satélite orbitando um planeta.

## Tecnologias Utilizadas

- HTML
- CSS

## Como Usar

Para usar este projeto, você pode clonar o repositório e abrir o arquivo `index.html` no seu navegador.

## Código

O projeto é composto principalmente de CSS, com um pouco de HTML para a estrutura básica. O CSS é usado para criar a animação do satélite orbitando o planeta.

Aqui está um trecho do código CSS:

```css
.planet{
	width:30em;
	height:30em;
	background:white;
	border-radius: 50%;
	box-shadow:0 0 5em 0 #fed84c80, 0 0 20em 4em #e8a55233, 0 0 55em 8em #ff4ff1a;
	position:relative;
}

.satellite, .satellite::after{
	content:"";
	position:absolute;
	width:5em;
	height:5em;
	border-radius:50%;
}
```

## Visualizar Projeto

Você pode visualizar o projeto ao vivo aqui.

https://felixfreitasjr.github.io/satelite/

## Contato

Se você tiver alguma dúvida ou sugestão sobre este projeto, sinta-se à vontade para me enviar uma mensagem.
