# Tutorial-HTML

<!DOCTYPE html>

<!--head é a cabeça/configurações-->
<head>
        <!--TITULO PRA ABA-->
    <title>O titulo que vai aparecer la na aba.</title>
</head>

<!--style é a aparência css do site-->
<style>
body {
    /* mudar a fonte dos textos do corpo "body" */
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    
    /* TEXT-ALIGN MUDA A POSIÇÃO DO TEXTO */
    text-align: center;
}
div{
    /* centralizar todos os textos de todos os "div" */
    text-align: center;
}

footer{
    /* centralizar o footer */
    text-align: center;
    color: blueviolet;
}
    

</style>






<!--body é o corpo do site-->
<body>
        <!--PARÁGRAFO "p"-->
    <div>
        <p>No head fica as config do site.</p>
        <p>No body fica todo o corpo do site.</p>
    </div>

        <!--ÂNCORA "a href=" SEM TARGET-->
    <div>
        <p>o P significa "parágrafo"</p>
        <a href="https://www.instagram.com/obemo">âncora sem target.</a>
    </div>


        <!--ÂNCORA "a href=" COM TARGET PARA ABRIR LINK EM NOVA ABA-->
    <div>
        <a href="https://www.instagram.com/obemo" target="_blank">o A significa "âncora", ou seja, redirecionar para algum lugar com o link dentro do "href" </a>
        <p>O "target _blank" faz abrir o link em outra aba</p>
    </div>
    

        <!--TITULO "h1" e "h2" COM ÂNCORA-->
    <div>
        <h1> <a href="https://www.instagram.com/obemoprive"> O "h1" é TITULO, e pode ter âncora dentro </a>  </h1>
        <h2>o "h2" é o titulo menos importante</h2>
        <p>O "div" cria divisão para as tags não ficarem soltas.</p>
    </div>

        <!--IMAGENS "img src=   alt="-->
    <img src="../Área de Trabalho/Screenshot_1.png" alt="o src significa o caminho da imagem e o alt a legenda da imagem">

        <!--QUEBRA DE LINHA "hr"-->
    <hr />

        <!--LISTAR "ol"-->
    <nav>
        <ol>
            <li>"ol" é listas, e "li" deve ficar dentro da "ol" para listar</li>
            <li>"hr" é quebra de linha</li>
        </ol>
            <!--LISTAR SEM NUMERAR "ul"-->
        <ul>
            <li>"ul" é lista não ordenada, só com um *.</li>
            <li>também precisa do "li" dentro da ul.</li>
        </ul>
    </nav>
        <!--NAVEGAÇÃO "nav"-->
    <nav>
        <h2>Navegação</h2>
        <p>o "nav" é uma aba de navegação</p>
    </nav>

    <div>
        <button>
            <a href="https://www.google.com.br" target="_blank">Ir para Google</a>
        </button>
    </div>

        <!--RODAPÉ "footer"-->
    <footer>
        <p>o footer é o rodapé &copy;</p>
    </footer>
</body>
