# Sombras-CSS---FrontEnd
Conteúdo Curso Programador Web - Praticas FrontEnd 

Efeitos de Sombra CSS
Noruega
Sombras

Com CSS você pode criar efeitos de sombra!

Passe o mouse sobre mim!
Efeitos de Sombra CSS
Com CSS você pode adicionar sombra ao texto e aos elementos.

Nestes capítulos você aprenderá sobre as seguintes propriedades:

text-shadow
box-shadow
Sombra de Texto CSS
A propriedade CSS text-shadowaplica sombra ao texto.

Em seu uso mais simples, você especifica apenas a sombra horizontal (2px) e a sombra vertical (2px):

Efeito de sombra de texto!
Exemplo
h1 {
  text-shadow: 2px 2px;
}
Em seguida, adicione uma cor à sombra:

Efeito de sombra de texto!
Exemplo
h1 {
  text-shadow: 2px 2px red;
}
Em seguida, adicione um efeito de desfoque à sombra:

Efeito de sombra de texto!
Exemplo
h1 {
  text-shadow: 2px 2px 5px red;
}
O exemplo a seguir mostra um texto branco com sombra preta:

Efeito de sombra de texto!
Exemplo
h1 {
  color: white;
  text-shadow: 2px 2px 4px #000000;
}
O exemplo a seguir mostra uma sombra de brilho neon vermelho:

Efeito de sombra de texto!
Exemplo
h1 {
  text-shadow: 0 0 3px #FF0000;
}


Múltiplas Sombras
Para adicionar mais de uma sombra ao texto, você pode adicionar uma lista de sombras separadas por vírgulas.

O exemplo a seguir mostra uma sombra de brilho neon vermelho e azul:

Efeito de sombra de texto!
Exemplo
h1 {
  text-shadow: 0 0 3px #FF0000, 0 0 5px #0000FF;
}
O exemplo a seguir mostra um texto branco com sombra preta, azul e azul escuro:

Efeito de sombra de texto!
Exemplo
h1 {
  color: white;
  text-shadow: 1px 1px 2px black, 0 0 25px blue, 0 0 5px darkblue;
}
Você também pode usar a propriedade text-shadow para criar uma borda simples ao redor de algum texto (sem sombras):

Borda ao redor do texto!
Exemplo
h1 {
  color: coral;
  text-shadow: -1px 0 black, 0 1px black, 1px 0 black, 0 -1px black;


Sombra da Caixa CSS
Propriedade box-shadow do CSS
A propriedade CSS box-shadowé usada para aplicar uma ou mais sombras a um elemento.

Especifique uma sombra horizontal e vertical
Em seu uso mais simples, você especifica apenas uma sombra horizontal e vertical. A cor padrão da sombra é a cor do texto atual.

Um elemento <div> com uma box-shadow
Exemplo
Especifique uma sombra horizontal e vertical:

div {
  box-shadow: 10px 10px;
}
Especifique uma cor para a sombra
O colorparâmetro define a cor da sombra.

Um elemento <div> com uma box-shadow azul claro
Exemplo
Especifique uma cor para a sombra:

div {
  box-shadow: 10px 10px lightblue;
}
Adicione um efeito de desfoque à sombra
O blurparâmetro define o raio do desfoque. Quanto maior o número, mais desfocada a sombra ficará.

Um elemento <div> com uma caixa-sombra azul claro desfocada de 5px
Exemplo
Adicione um efeito de desfoque à sombra:

div {
  box-shadow: 10px 10px 5px lightblue;
}
Defina o raio de propagação da sombra
O spreadparâmetro define o raio de propagação. Um valor positivo aumenta o tamanho da sombra, um valor negativo diminui o tamanho da sombra.

Um elemento <div> com uma caixa-sombra em azul claro desfocada, com um raio de propagação de 12px
Exemplo
Defina o raio de propagação da sombra:

div {
  box-shadow: 10px 10px 5px 12px lightblue;
}


Definir o parâmetro de inserção
O insetparâmetro altera a sombra de uma sombra externa (início) para uma sombra interna.

Um elemento <div> com uma caixa de sombra desfocada, azul clara e inserida
Exemplo
Adicione o parâmetro de inserção:

div {
  box-shadow: 10px 10px 5px lightblue inset;
}
Adicionar várias sombras
Um elemento também pode ter várias sombras:

Exemplo
div {
  box-shadow: 5px 5px blue, 10px 10px red, 15px 15px green;
}
cartões
Você também pode usar a box-shadowpropriedade para criar cartões semelhantes a papel:

1
1º de janeiro de 2021

Noruega
Hardanger, Noruega

Exemplo
div.card {
  width: 250px;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);
  text-align: center;
}
 
Teste-se com exercícios
Exercício:
Defina uma sombra de texto "2px" horizontal e "2px" vertical para o elemento <h1>.

<estilo>
h1 {
  
: 2px 2px;
}
</estilo>

<corpo>
  <h1>Este é um cabeçalho</h1>
  <p>Isto é um parágrafo</p>
  <p>Isto é um parágrafo</p>
</body>

Propriedades da Sombra CSS
A tabela a seguir lista as propriedades de sombra CSS:

Property	Description
box-shadow	Adds one or more shadows to an element
text-shadow	Adds one or more shadows to a text


Propriedade box-shadow do CSS

Exemplo
Adicione sombras a diferentes elementos <div>:

#example1 {
  box-shadow: 5px 10px;
}

#example2 {
  box-shadow: 5px 10px #888888;
}
Mais exemplos de "Experimente você mesmo" abaixo.

Definição e Uso
A box-shadowpropriedade anexa uma ou mais sombras a um elemento.


Valor padrão:	nenhum
Herdado:	não
Animatável:	sim. Leia sobre animável
Versão:	CSS3
Sintaxe JavaScript:	objeto .style.boxShadow="10px 20px 30px azul"
Suporte do navegador
Os números na tabela especificam a primeira versão do navegador que suporta totalmente a propriedade.

Números seguidos por -webkit- ou -moz- especificam a primeira versão que funcionou com um prefixo.

Property					
box-shadow	10.0
4.0 -webkit-	9.0	4.0
3.5 -moz-	5.1
3.1 -webkit-	10.5
ANÚNCIO

ANÚNCIO

Sintaxe CSS
box-shadow: none|h-offset v-offset blur spread color |inset|initial|inherit;
Observação: para anexar mais de uma sombra a um elemento, adicione uma lista de sombras separadas por vírgulas (consulte o exemplo "Experimente você mesmo" abaixo).
Valores de propriedade
Value	Description	Demo
none	Default value. No shadow is displayed	
h-offset	Required. The horizontal offset of the shadow. A positive value puts the shadow on the right side of the box, a negative value puts the shadow on the left side of the box	
v-offset	Required. The vertical offset of the shadow. A positive value puts the shadow below the box, a negative value puts the shadow above the box	
blur	Optional. The blur radius. The higher the number, the more blurred the shadow will be	
spread	Optional. The spread radius. A positive value increases the size of the shadow, a negative value decreases the size of the shadow	
color	Optional. The color of the shadow. The default value is the text color. Look at CSS Color Values for a complete list of possible color values.

Note: In Safari (on PC) the color parameter is required. If you do not specify the color, the shadow is not displayed at all.	
inset	Optional. Changes the shadow from an outer shadow (outset) to an inner shadow	
initial	Sets this property to its default value. Read about initial	
inherit	Inherits this property from its parent element. Read about inherit	
Dica: Leia mais sobre valores permitidos (unidades de comprimento CSS)

Mais exemplos
Exemplo
Adicione um efeito de desfoque à sombra:

#example1 {
  box-shadow: 10px 10px 8px #888888;
}
Exemplo
Defina o raio de propagação da sombra:

#example1 {
  box-shadow: 10px 10px 8px 10px #888888;
}
Exemplo
Defina várias sombras:

#example1 {
  box-shadow: 5px 5px blue, 10px 10px red, 15px 15px green;
}
Exemplo
Adicione a palavra-chave inserida:

#example1 {
  box-shadow: 5px 10px inset;
}
Exemplo
Imagens jogadas sobre a mesa. Este exemplo demonstra como criar imagens "polaroid" e girar as imagens:

div.polaroid {
  width: 284px;
  padding: 10px 10px 20px 10px;
  border: 1px solid #BFBFBF;
  background-color: white;
  box-shadow: 10px 10px 5px #aaaaaa;
}


Propriedade de sombra de texto CSS

Exemplo
Sombra de texto básica:

h1 {
  text-shadow: 2px 2px #ff0000;
}
Mais exemplos de "Experimente você mesmo" abaixo.

Definição e Uso
A text-shadowpropriedade adiciona sombra ao texto.

Esta propriedade aceita uma lista de sombras separadas por vírgulas a serem aplicadas ao texto.


Valor padrão:	nenhum
Herdado:	sim
Animatável:	sim. Leia sobre animável
Versão:	CSS3
Sintaxe JavaScript:	objeto .style.textShadow="2px 5px 5px vermelho"
Suporte do navegador
Os números na tabela especificam a primeira versão do navegador que suporta totalmente a propriedade.

Property					
text-shadow	4.0	10.0	3.5	4.0	9.6
ANÚNCIO

ANÚNCIO

Sintaxe CSS
text-shadow: h-shadow v-shadow blur-radius color|none|initial|inherit;
Nota: Para adicionar mais de uma sombra ao texto, adicione uma lista de sombras separadas por vírgula.

Valores de propriedade
Value	Description	Demo
h-shadow	Required. The position of the horizontal shadow. Negative values are allowed	
v-shadow	Required. The position of the vertical shadow. Negative values are allowed	
blur-radius	Optional. The blur radius. Default value is 0	
color	Optional. The color of the shadow. Look at CSS Color Values for a complete list of possible color values	
none	Default value. No shadow	
initial	Sets this property to its default value. Read about initial	
inherit	Inherits this property from its parent element. Read about inherit	
Dica: Leia mais sobre valores permitidos (unidades de comprimento CSS)

Mais exemplos
Exemplo
Sombra de texto com efeito de desfoque:

h1 {
  text-shadow: 2px 2px 8px #FF0000;
}
Exemplo
Sombra de texto em um texto branco:

h1 {
  color: white;
  text-shadow: 2px 2px 4px #000000;
}
Exemplo
Sombra de texto com um brilho neon vermelho:

h1 {
  text-shadow: 0 0 3px #FF0000;
}
Exemplo
Sombra de texto com um brilho neon vermelho e azul:

h1 {
  text-shadow: 0 0 3px #FF0000, 0 0 5px #0000FF;
}


Dica Extra:

Unidades CSS
Unidades CSS
CSS tem várias unidades diferentes para expressar um comprimento.

Muitas propriedades CSS aceitam valores de "comprimento", como width, margin, padding, font-size, etc.

Comprimento é um número seguido por uma unidade de comprimento, como 10px, 2em, etc.

Exemplo
Defina diferentes valores de comprimento, usando px (pixels):

h1 {
  font-size: 60px;
}

p {
  font-size: 25px;
  line-height: 50px;
}

Nota: Um espaço em branco não pode aparecer entre o número e a unidade. No entanto, se o valor for 0, a unidade pode ser omitida.

Para algumas propriedades CSS, comprimentos negativos são permitidos.

Existem dois tipos de unidades de comprimento: absoluto e relativo .

Comprimentos absolutos
As unidades de comprimento absoluto são fixas e um comprimento expresso em qualquer um deles aparecerá exatamente com esse tamanho.

Unidades de comprimento absoluto não são recomendadas para uso na tela, porque os tamanhos de tela variam muito. No entanto, eles podem ser usados ​​se a mídia de saída for conhecida, como para layout de impressão.

Unit	Description
cm	centimeters
mm	millimeters
in	inches (1in = 96px = 2.54cm)
px *	pixels (1px = 1/96th of 1in)
pt	points (1pt = 1/72 of 1in)
pc	picas (1pc = 12 pt)
* Pixels (px) são relativos ao dispositivo de visualização. Para dispositivos de baixo dpi, 1px é um pixel de dispositivo (ponto) da tela. Para impressoras e telas de alta resolução, 1px implica vários pixels de dispositivo.

Comprimentos Relativos
As unidades de comprimento relativo especificam um comprimento relativo a outra propriedade de comprimento. As unidades de comprimento relativo escalam melhor entre diferentes meios de renderização.

Unit	Description	
em	Relative to the font-size of the element (2em means 2 times the size of the current font)	
ex	Relative to the x-height of the current font (rarely used)	
ch	Relative to the width of the "0" (zero)	
rem	Relative to font-size of the root element	
vw	Relative to 1% of the width of the viewport*	
vh	Relative to 1% of the height of the viewport*	
vmin	Relative to 1% of viewport's* smaller dimension	
vmax	Relative to 1% of viewport's* larger dimension	
%	Relative to the parent element	
Dica: As unidades em e rem são práticas para criar um layout perfeitamente escalável!
* Viewport = o tamanho da janela do navegador. Se a janela de visualização tiver 50 cm de largura, 1vw = 0,5 cm.

Suporte do navegador
Os números na tabela especificam a primeira versão do navegador que suporta totalmente a unidade de comprimento.

Length Unit					
em, ex, %, px, cm, mm, in, pt, pc	1.0	3.0	1.0	1.0	3.5
ch	27.0	9.0	1.0	7.0	20.0
rem	4.0	9.0	3.6	4.1	11.6
vh, vw	20.0	9.0	19.0	6.0	20.0
vmin	20.0	12.0	19.0	6.0	20.0
vmax	26.0	16.0	19.0	7.0	20.0
