# estudos-html
Aprendendo HTML 
<!DOCTYPE html>

<html lang = "pt-br">

<head>
    <meta charset="UTF-8"/>
    <link rel="shortcut icon" href="Elegantthemes-Beautiful-Flat-Dev.128 (1).ico" type="image/x-icon">
    <title>
        FRONTEND
    </title>
    
    <style> 
        h1{
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            color: black;
            font-size: 20pt;
        }
        h2{
            font-size: 10pt;
        }
       body{
            background-color: rosybrown; 
        }
        mark{
            background-color: rgb(191, 177, 23);
        }
    
    </style>
<!--Mudando a cor do site no parentes body{backgrounf-color}-->
</head>

<body>
<div id = "interface">
<h1>
    Estudos do front end
    <hr> <!--Insere uma linha embaixo da frase-->
</h1>
<p>
    <h1>
        Paragráfos
    </h1>
    Você coloca todos os
    paragráfos entre as tags p e /p
</p>
<p>
    <h1>
        Quebras de linha
    </h1>
    Para quebrar uma linha
    basta <br>colocar a tag br onde você 
    quiser  <!--COMENTÁRIOS EM HTML-->
</p>
<p>
    <h1>
        Símbolos especiais
    </h1>
    Adicionando símbolos especiais 
    <br> &reg; <!--Marca registrada-->
   <br> &copy; <!--Copyright-->
</p>

<p>
    <h1>
        Emojis
    </h1>
    Adicionando emojis 
   <br> &#x1F498 
   <br> &#x1F47E
</p>

<p>
    <h1>Adicionando uma imagem</h1>
    <br>
    <img src="logohtml.png" alt="logo HTML">
    <br> <img src="logocsspng.webp" alt="logo CSS"> 
</p>

<p>
    <br> Hieraquia de Títulos 
    <h1>
        A tag h1 serve para o título principal
    </h1>
    <h2>
        A tag h2 serve para o subtítulo "contido" no h1
        <p>
            Lorem ipsum dolor sit amet consectetur, adipisicing elit. Non sunt labore dolorum tempore rerum omnis unde veritatis ipsam vero, quam quibusdam possimus officia deleniti, a fugit! Doloribus earum nam illum?
        </p>
    </h2>
    <h3>
        A tag h3 é um subtítulo de h2
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem accusantium ullam id iusto atque velit, optio iste minus eum nesciunt fugiat necessitatibus. Ad odit quisquam ea aut voluptas iure ratione!
        </p>
    </h3>
    <h1>
        Dessa maneira os titulos e subtitulos 
    </h1>
    <h2>
        Vão sendo organizados 
    </h2>
    <h3>
        Dentro do site 
    </h3>
</p>

<p>
    <address>
        Com a função adress eu coloco uma determinada frase ou palavra em uma fonte ou estilo diferente, é importante ressaltar que o html é usado para a parte de semnântica do site
    </address>
</p>

<p>
    <h3>
        Para mudar a cor da página do site utiliza o style criando uma chave com body e alterando a cor usando "background-color"
    </h3>
</p>

<p>
    <br> <h1>
        FORMATAÇÕES 
    </h1>
    <h2> 
        NEGRITO OU DESTAQUE
    </h2>
        Agora utilizando a tag b <b> também é possível por em negrito de uma maneira não semântica</b>
    
       <address> Para colocar uma <strong> frase em "destaque" </strong> é utilizado a tag strong  </address>
    
</p>

<p>
    <h1>
        ITÁLICO OU ÊNFASE 
    </h1>
    Colocando uma <i>frase em itálico</i>: seleciona a palavra ou frase + control shift p + abb + i + enter (não semântica)
    <br> Usando a tag em <em> o itálico passa a ser semântico</em>
</p>
<p>
    <h1>
        Marca Texto HTML5
    </h1>
    Para marcar <mark> um texto utilizamos a tag mark</mark>

    <h1>
        Mudando a cor do marca texto
    </h1>
    Para mudar a cor <mark> de um marcador é necessário usar o parametro css style dentro do marcador</mark>

    <h1>
        Usando a mesma cor para todos os marcadores
    </h1>
    Na tag <mark>head</mark> utilizando o parametro <mark> style</mark>  cria uma chave com o mark e seleciona a cor escolhida através do background-color
</p>

<p>
    <h1>
        Texto Deletado
    </h1>
    É possível marcar <del>um texto como excluído</del> para que ele seja lido, mas não considerado


    <h1> 
        Texto Inserido
    </h1>
    É possível marcar <ins>um texto como inserido</ins> dar ênfase ou indicar que ele foi adicionado depois
</p>

<p>
    <h1>
        Texto Sobrescrito
        
    </h1>
    X<sup>20</sup>+3


    <h1>
        Texto Subescrito
        
    </h1>
    H<sub>2</sub>O
</p>

<p>
    <h1>
        Código-fonte
    </h1>
    A tag code auxilia na nivelação do ESpaçamento <code> das palavras de uma frase</code>
</p>

<h1> 
    Tabulação
</h1>
Através da tag pre é possível organizar a tabulação do código, exemplo:
<pre>
    <code>
printf("Olá mundo\n"); 
printf("Eu estou aprendendo frontend\n");
    </code>
</pre>
<p>
    <h1>
        Citação simples
    </h1>
    <q> Com a tag q a frase ou palavra fica no formato de citação</q>

    <h1> 
        Citação Completa
    </h1>

    No livro Daisy Jones and the six: 
<blockquote cite="https://dlivros.com/livro/daisy-jones-and-the-six-historia-amor-musica-taylor-jenkins-reid">
    Meu coração disparou enquanto o telefone chamava.
    Coloquei o dedo no pescoço, e dava para sentir as veias
    pulsarem. Mas, quando Camila atendeu, foi como se eu
    estivesse deitando na cama depois de um longo dia. Só
    de ouvir a voz dela já me senti melhor. Eu falei: “Estou
    morrendo de saudade. Não consigo viver sem você”.
    Ela respondeu: “Eu também estou com saudade”.
    Eu continuei: “Por que a gente está fazendo isso? Meu
    lugar é com você”.
    Ela respondeu: “É, eu sei”.
    Ficamos em silêncio por um tempo, aí perguntei: “Se
    eu fechasse um contrato com uma gravadora, você
    casaria comigo?”.
    Ela disse: “Quê?”.
</blockquote>
</p>

<p>
    <h1>
        Abreviações
    </h1>
    Eu estudo na<abbr title="Universidade Federal do Tocantins" > UFT </abbr> 
</p>

<p>
    <h1>
        Invertendo
    </h1>
    Estou aprendendo a <bdo dir="rtl"> inverter </bdo> em HTML
</p>

<p>
    <h1>
        Listas Ordenadas - a ordem faz diferença na lista, exemplo: uma receita de bolo
    </h1>
    Usamos a tag ol para criar a lista e a delimitar e a tag li para identificar cada item da lista

    <ol type="a" start="2">
        <li>
            Tomar banho
        </li>
        <li>
            Escovar os dentes 
        </li>
        <li>
            Arrumar as roupas
        </li>

    </ol>
</p>
<p>
    <h1> 
        Listas não ordenadas
    </h1>
    
    São aquelas que a ordem das coisas não influencia o resultado final, para criar a lista usamos a tag ul e a tag li para identificar os itens
   
    <ul type = "square">
        <li> Carros </li>
        <li> Filmes </li>
        <li> Taylor Swift </li>
        <li> Sarah </li>

   </ul> 
</p>
<p>
    <h1>
        Juntando Listas
    </h1>
    Minhas linguagens preferidas
    <ol>
        <li>
            Antigas
        </li>
            <ol>
                <li>
                    C
                </li>
                <li>
                    Assembly
                </li>
            </ol>
        <li>
            Novas
        </li>
            <ol>
                <li> 
                    Python
                </li>
                <li>
                    JavaScript
                </li>
            </ol>
    </ol>
</p>

<p>
    <h1>
        Exercício de Listas ol e ul misturadas
    </h1>
    Meus filmes preferidos baseados no gênero
    <ol>
        <li>
            Terror
        </li> 
            <ol>
                <li>
                    Pânico
                </li>
                <li>
                    Jogos Mortais
                </li>
                <li>
                    Correndo contra o tempo
                </li>
            </ol>
        <li>
            Romance
        </li>
            <ul>
                <li>
                    Crush
                </li>
                <li> 
                    Uma linda mulher
                </li>
            </ul>
    </ol>
</p>
<p> 
    <h1>
        Listas de definição, para elas usamos as tags dl, dt (o que vai ser definido) e dd(descrição)
    </h1>

    <dl>
        <dt>O que vai ser definido</dt>
        <dd> Aqui fica a definação do termo ou explicação do que se trata</dd>
    </dl>
</p>

<p>
    <h1> Criação de Links Externos</h1>

    Para criar links, utilizamos a tag a (para criar as âncoras) e o atributo href para referenciar o hipertexto

    <a href="https://www.instagram.com/annalauracss/" hreflang="pt-br" target="_blank" rel="external"> Acesse meu perfil no instagram em uma nova janela </a>
</p>
<p>
    <h1>
        Link interno
    </h1>
    Esses links são caracterizados por fazer o usuário continuar na mesma aba

    <a href="pag22.html" hreflang="pt-br" rel="next"> Acesse um link do site
    </a>
</p>

<p>
    <h1> 
        Links para baixar
    </h1>
    <ul>
        <li>
            <a href="arquivos/ComprovanteMatricula.pdf" download="ComprovanteMatricula.pdf" type="application/pdf">Baixar o livro em PDF</a>
        </li>
        <li>
            <a href="Daisy Jones and The Six_ uma Historia de Amor e Musica - Taylor Jenkins Reid.zip" download="Daisy Jones and The Six_ uma Historia de Amor e Musica - Taylor Jenkins Reid.zip" type="application\zip">Baixar livro compactado</a>
        </li>
    </ul>

</p>
<p> 
    <h1>
        Imagens Dinâmicas 
    </h1>
    Utilizando a tag picture <mark> picture </mark> é possível pegar imagens com vários src diferentes
    <picture>
        <source media="(max-width: 750px)" srcset="foto-p.png" type="image/png">
        <source media="(max-width: 1050px)" srcset="foto-m.png" type="image/png">
        <img src="foto-g.png" alt="Imagem flexível">
    </picture>

</p>


</body>
