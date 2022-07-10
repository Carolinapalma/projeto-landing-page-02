# <h1 align="center">Projeto Landing Page 02</h1>

## Indice


* [Visão geral](#visão-geral)
   * [Sobre](#sobre)
   * [Captura de tela](#captura-de-tela)
- [Processo](#processo)
   * [Construído com](#construído-com)
   * [O que aprendi](#o-que-aprendi)
   * [Acesso a Página](#acesso-a-página)
   * [Autora](#autora)
---

## <p align="center">Visão geral</p>

### Sobre

Segundo projeto de página única a partir do curso Dev em Dobro, que consiste em desafio utilizando HTML, CSS e JS afim de aprimorar conhecimentos adquiridos e através de boas metodologias atualmente usadas no mercado de trabalho.


---

## Captura de tela

<img src="src/imagens/Landing-page-02.gif" alt="gif tela inicial do projeto agência xpto">
<br>

 <p align="center">
    <img align="center" src="src/imagens/Landing-page-02-responsivo.gif" alt="gif tela inicial responsivo do projeto agência xpto">
    
---

## <p align="center">Processo</p>

### Construído com

  * HTML semântica;
  * FlexBox;
  * Menu Navegação;
  * Efeito Carrossel de imagens;
  * Função das setas no Painel;
  * Responsividade para dispositivos móveis.
  
---

### O que aprendi

* Efeito carrossel:
```css
.conteudo-principal .paineis {
	display: flex;
	justify-content: center;
	align-items: center;
	height: 700px;
	position: relative; }

.conteudo-principal .paineis .imagem-painel{
	background-repeat: no-repeat;
	background-size: cover;
	background-position: center;
	min-width: 100%;
	height: 100%;
	position: absolute;
	z-index: -1;
	filter: brightness(70%);
	opacity: 0;
	transition: 0.3s ease-in-out; }
```

* <i>Function</i> nas setas:
```js
setaAvancar.addEventListener('click', function () {
	const totalDeImagens = imagensPainel.length - 1;
	if(imagemAtual === totalDeImagens){
		console.log('não pode avançar mais');
		return;
	}	
	imagemAtual++;
	esconderImagens();
	mostrarImagem(); });
```
---

### Acesso a Página

- [GitHub Page](https://carolinapalma.github.io/projeto-landing-page-02/)

---

## <p align="center">Autora</p>

### Carolina Palma

 * [LinkedIn](https://www.linkedin.com/in/carolina-palma-medeiros/) 
  
 * [GitHub](https://github.com/Carolinapalma)
