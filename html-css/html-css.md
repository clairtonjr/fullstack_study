# HTML - CSS

## HTML
Introdução
	HTML é uma linguagem de marcação utilizada para estruturar páginas web. O HTML usa tags para marcar conteúdo do site. Um elemento HTML constitui de tag de abertura, conteúdo e tag de fechamento . Conteúdo é o que marcamos para posteriormente podermos modificá-los com CSS ou JavaScript.
	No HTML existem dois tipos de elementos, os inline e bloco. Elementos em bloco formam um “bloco” visível na pagina, geralmente são elementos estruturais como menus de navegações, parágrafos, listas, etc.  Elementos inline são aqueles que estão contidos dentro de elementos bloco, como links (<a>), ênfase (<em>) ou (<strong>).

Anatomia de um documento HTML
	<!doctype HTML> → Outrora essa tag era usada para informar a página a versão do HTML que seria exibida e tinha um nome maior, atualmente informa que utilizaremos a versão mais recente do HTML.
	<html> </html> → Envolve o conteúdo da página inteira, é o elemento raiz.
	<head> </head> → É onde guardamos as informações que não é visível aos visitantes do site. No geral é onde colocamos metas dados sobre a página, links externos, título da página, etc.
	<meta charset =”utf-8”> → Elemento que define o tipo de codificação de caracteres que o documento deve usar. Possui um vasto acervo de caracteres e torna mais fácil a visualização textual. 
	<title> </title> → Define o título do página. 
	<body> </body> → Contém  todo o conteúdo que será exibido na página para o usuário como textos, imagens, vídeos, etc.
   


## CSS

O que é?
	É uma linguagem usada para estilizar documentos HTML, sua sigla significa Cascading Style Sheet (Folha de estilo em cascada).
    É uma linguagem para especificar como documentos serão apresentados ao usuário.

O CSS é uma linguagem baseada em regras.

Com CSS podemos alterar a aparência da página de diversas formas como fontes, cores, formatos, tamanhos, imagens, alinhamentos e etc;

Para modificar um elemento primeiro é preciso selecionar esse elemento, o CSS utiliza diversas formas de seletores como seletores de elemento, seletores de classe e seletor de id, seletor combinador descendente, etc.

No nível mais básico, CSS possui dois blocos de construção: propriedades (font-size, width, color) e Valores ( cada propriedade recebe um valor que indica o que deseja alterar )

O CSS muda o comportamento padrão dos elementos, estiliza baseado na sua locação no documento e baseado 
no estado.