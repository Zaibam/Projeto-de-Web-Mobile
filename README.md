<!DOCTYPE html>
<html lang="br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>POC 1 - Flexbox</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- 1 ITEM -->
    <h1>display: flex</h1>
    <h2>display: flex</h2>
    <p>Define um contêiner como um contêiner flexível e habilita as propriedades Flexbox nos seus filhos.</p> 
    <div class="cont1">
    ![displayflex](https://github.com/user-attachments/assets/74d9b0e0-0710-4c56-97d7-138c34a205f6)
    </div>
    <!-- 2 ITEM -->
    <h1>flex-direction</h1>
    <p>Define a direção do eixo principal ao longo do qual os itens flexíveis são alinhados.</p> 
    <h2>column:</h2>
    <p>Alinha os itens de cima para baixo.</p> 
    <div class="cont1">
        <div class="column"> 
            <img src="LogoDeMackenzie.png" alt="Logo Mack" >
            <img src="LogoDeMackenzie.png" alt="Logo Mack" >
            <img src="LogoDeMackenzie.png" alt="Logo Mack" >
        </div>
    </div>
    <h2>row-reverse:</h2>
    <p>Alinha os itens da direita para a esquerda.</p> 
    <div class="cont2">
        <div class="row-reverse">  
            <img src="LogoDeMackenzie.png" alt="Logo Mack">
            <img src="LogoDeMackenzie.png" alt="Logo Mack">
            <img src="LogoDeMackenzie.png" alt="Logo Mack">
        </div>
    </div>
    <!-- 3 ITEM -->
    <h1>justify-content</h1>
    <p>Controla como os itens flexíveis são distribuídos ao longo do eixo principal.</p>
    <h2>center:</h2>
    <p> Alinha os itens ao centro do contêiner.</p> 
    <div class="cont30">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
    </div>  
    <h2>flex-start:</h2>
    <p>Alinha os itens ao início do contêiner</p> 
    <div class="cont31">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
    </div>
    <h2>flex-end: </h2>
    <p>Alinha os itens ao final do contêiner.</p> 
    <div class="cont32">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
    </div>
    <h2>space-around:</h2>
    <p> Distribui os itens com espaçamento igual ao redor de cada item.</p> 
    <div class="cont33">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
    </div>
    <h2>space-between: </h2>
    <p>Distribui os itens com espaçamento igual entre eles.</p> 
    <div class="cont34">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
    </div>
    <!-- 4 ITEM-->
    <h1>Align-Items</h1>
    <p>Controla como os itens são alinhados ao longo do eixo transversal (perpendicular ao eixo principal).</p><br>
    <h2>flex-start:</h2>
    <p>Alinha os itens ao início do contêiner.</p> 
    <div class="cont40">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
    </div>
    <h2>center:</h2>
    <p>O valor central alinha os itens flexíveis no meio do contêiner</p> 
    <div class="cont41">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
    </div>
    <h2>flex-end:</h2>
    <p>Alinha os itens ao final do contêiner.</p>
    <div class="cont42">    
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
    </div>
    <h2>baseline:</h2>
    <p>Alinha os itens ao longo da linha de base do contêiner.</p>
    <div class="cont44">
        <img src="LogoDeMackenzie.png" alt="Logo Mack" class="imagconte44">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack" class="imagconte444">
    </div><br>
    <h2>stretch:</h2>
    <p>Estatica os items para prencher o contêiner (padrão).</p>
    <div class="cont45">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
    </div><br>
    <!-- 5 ITEM -->
    <h1>Aling-Content</h1>
    <p>Controla a distriuição das linhas no contêiner quando há múltiplas inhas de itens.</p><br><br>
    <h2>space-between:</h2>
    <p>Distribui as linhas com espaçamento igual entre elas.</p>
    <div class="cont50">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
    </div><br>
    <h2>space-around:</h2>
    <p>Distribui as linhas com espaçamento igual ao redor de cada linha.</p>
    <div class="cont51">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
    </div><br>
    <h2>stretch:</h2>
    <p>Estatica as linhas para prencher o contêiner (padrão).</p>
    <div class="cont52">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
    </div><br>
    <h2>center:</h2>
    <p>Alinha os as linhas ao centro do contêiner.</p>
    <div class="cont53">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
    </div><br>
    <h2>flex-start:</h2>
    <p>Alinha as linhas ao início do contêiner.</p>
    <div class="cont54">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
    </div><br>
    <h2>flex-end:</h2>
    <p>Alinha as linhas ao final do contêiner.</p>
    <div class="cont55">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
    </div><br>
    <!-- 6 ITEM -->
    <h1>flex-wrap</h1>
    <p>Define se os itens devem ou não quebrar para uma nova linha.</p>
    <h2>wrap:</h2>
    <p>Permite a quebra de linha.</p>
    <div class="cont60">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
    </div><br>
    <h2>nowrap:</h2>
    <p>Não permite a quebra de linha (padrão).</p>
    <div class="cont61">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
    </div><br>
    <h2>wrap-reverse:</h2>
    <p>O "flex-wrap: wrap-reverse;" especifica que os itens flexíveis serão agrupados se necessário, na ordem inversa</p>
    <div class="cont62">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
        <img src="LogoDeMackenzie.png" alt="Logo Mack">
    </div>
</body>
</html>


