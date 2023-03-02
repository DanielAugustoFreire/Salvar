<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>Questionário sobre CSS (<span>Folhas de Estilo em Cascata</span>)</h1>
    <h3>O que signigica CSS?</h3>
    <p>CSS é a sigla para Cascading Style Sheets, ou seja, Folhas de Estilo em Cascatas.        </p>
    <h3>Cite 2 características importantes quando se usa CSS?</h3>
    <p>A seleção e seus modos de incorporacao no html</p>
    <h3>Quais as possíveis formas de vincular o CSS em um documento HTML? Cite e exemplifique.</h3>
    <p style="text-align: left  ;">Estilo Incorporado, Estilo importado e Estilo inline.</p>
    <p style="color: aqua;">Incorporado: Uma definição deste tipo deve ser usada quando não
        existe um padrão comum aos vários documentos de um
        site - ou então o site é composto de um único documento.<br><br>Importado: A definição é feita num arquivo separado e importado
        na página.<br><br>Inline: A definição da CSS é feita diretamente na
        tag HTML com o uso do atributo style.</p>
    <h3>Na definição do CSS o que representa a criação de uma regra no seletor?</h3>
    <p>A regra é composta por seletor e propriedades dentro de chaves {}. Quando aplicada, todas as propriedades são aplicadas aos elementos selecionados.</p>
    <h3>Como se comenta uma linha na definição do arquivo CSS?</h3>
    <p>Com a seguinte formulação: /* texto comentado */</p>
    <h3></h3>
    <p></p>
    <h3>Quando o ; será utilizado?</h3>
    <p>Quando mais de uma propriedade for definida na regra, deve-se usar ponto-e-vírgula para separá-las.
        O ponto-e-vírgula é facultativo no caso de propriedade única e também após a declaração da última propriedade no caso de mais de uma.</p>
    <h3></h3>
    <p></p>
</body>
</html>
    
body{
    background-color: rgb(23, 23, 23);
}
h1{
    color: rgb(255, 0, 0);
    background-color: white;
    text-align: center;
}
h3{
    color: rgb(74, 255, 83);
}
p{
    color: white;
    text-align: justify;
}
