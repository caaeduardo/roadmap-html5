<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cadu | Dev.</title>
    <link rel="shortcut icon" href="icon/cadu.dev.ico" type="image/x-icon">
    <style>
        body {
            background-color: rgb(247, 247, 247)
        }
        mark{
            background-color: blueviolet;
        }
    </style>
</head>
<body>
<center><h1>ROAD MAP of HTML5</h1></center>
//comentário em vermelho o códgio está obsoleto


<h2>Formatações de Texto</h2>
<h3>Negrito / Destaque</h3>
<p><strong>Cadu com utilização correta "strong" texto em Negrito.</strong></p>
<p><b>Cadu com utilização incorreta "b" texto em Negrito.</b></p>

<h3>Itálico / Ênfase</h3>
<p><i>Cadu com utilização incorreta "i"</i></p>
<em><p>Cadu com utilização correta "em"</p></em>

<h3>Texto Marcado/ Mark</h3>
<p><mark style="background-color: limegreen;">Cadu com o texto Marcado</mark></p>
<p><mark style="background-color: rgb(205, 50, 197);">Cadu com o texto Marcado</mark></p>
<p><mark>Cadu com o texto Marcado</mark>neste caso deteminado no corpo do código então esse é o que vem do principal no head do código</p>

<h3>Texto Grande e Pequeno</h3>
<p>estamos criando um <big>texto grande</big> e um <small>texto pequeno</small> neste paragrafo</p>

<h3>Texto Deletado</h3>
<p><del>Podemos marcar um texto excluido para indicar que ele deve ser lido, mas não considerado</del></p>

<h3>Texto Inserido</h3>
<p><ins>O texto de formato sublinhado para dar enfase</ins></p>

<h3>Texto Sobrescrito</h3>
<p>esse resultado é X<sup>20</sup>+30</p>

<h3>Texto Subscrito</h3>
<p>Ou esse H<sub>2</sub>O</p>

<h2>Outras Formatações</h2>
<h3>Código-fonte</h3>
<p>O comando <code>document.getElementByid('teste')</code> é escrito em linguagem Javascript.</p>
//estrutura de código caso precisar em HTML
<pre>
    <code>
        num = int(input('Digite um numero'))
        if num % 2 == 0:
            print(f'0 numero {num} é PAR')
        else:
            print(f'0 numero {num} é IMPAR')
        print('Fim do Programa')
    </code>
</pre>

<h3>Citações Simples</h3>
<p>Como diria o neymar: <q>Hoje tem gol do pai!</q></p>

<h3>Citações Simples</h3>
//citações de Livro
<p>Segundo Neymar Jr no Livro Vamos ser Campeões: <blockquote>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Vero nesciunt, quos laborum ut itaque non eum facere rem fugit eos cumque aspernatur atque? Ad, dolorem. Impedit aspernatur nam ex ab</blockquote></p>

<h3>Abreviações</h3>
<p>Estou usando <abbr title="Hyper Text Markup Language">HTML</abbr> e <abbr title="Cascading Style Sheets">CSS</abbr> e Javascript.</p>



<h3>Início</h3>
<p><font color="orange">Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis quas fugiat suscipit soluta laborum nam laudantium debitis ipsa sapiente ipsum maxime eos error sed hic saepe, <br> autem ratione atque?</font></p>

<h3>Atalhos</h3>
<p><strong>Ctrl + Shift + P</strong> = Emmet Abreviação dos códigos</p>
<p><strong>Ctrl + C</strong> = Automático a procura de imagem no img src</p>
<p><strong>Shift + tab</strong> = seleciona todo o erro de identação e arruma de forma conjunta</p>


<h3>Serviços</h3>

<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis quas fugiat suscipit soluta laborum nam laudantium debitis ipsa sapiente ipsum maxime eos error sed hic saepe, fugit autem ratione atque?</p>

<h3>Link Bio</h3>
<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis quas fugiat suscipit soluta laborum nam laudantium debitis ipsa sapiente ipsum maxime eos error sed hic saepe, fugit autem ratione atque?</p>

Eu moro na <address>Rua dos Neymá, 121 - Vila PSG, São Paulo</address>
//Endereço

</body>
</html>  
