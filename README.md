<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RPA Consultas ANVISA</title>
</head>

<body>

    <h1>RPA Consultas ANVISA</h1>

    <h2>O que fazemos?</h2>
    <p>O projeto RPA de consultas ANVISA foi desenvolvido para automatizar tarefas no site da ANVISA (<a href="https://consultas.anvisa.gov.br/#/genericos/" target="_blank">https://consultas.anvisa.gov.br/#/genericos/</a>). Consiste no preenchimento do número de registro de cada produto e, em seguida, armazena dados específicos (nome técnico, registro, situação, processo, fabricante legal, classificação de risco, vencimento do registro) em uma planilha Excel.</p>

    <h2>Por que esse projeto é útil?</h2>
    <p>Este projeto foi criado para automatizar tarefas, proporcionando economia de tempo e redução de atividades repetitivas. O responsável por essa tarefa economizará tempo, podendo se concentrar em outras atividades enquanto a automação roda em segundo plano.</p>

    <h2>Como os usuários podem começar a usar o projeto?</h2>
    <p>Para obter acesso ao projeto, o usuário deve ter o Google Chrome instalado em sua máquina. Em seguida, o download dos arquivos disponibilizados neste projeto deve ser feito, e todos eles devem ser armazenados na mesma pasta.</p>
    
    <ul>
        <li><strong>Registro:</strong> Neste arquivo Excel, o usuário deve fornecer os números de registro a serem consultados pelo programa, colocando um registro em cada linha. A primeira linha (preenchida com "Registro") não deve ser alterada, começando pela segunda linha.</li>
        <li><strong>Dados:</strong> Neste arquivo, inicialmente vazio, o usuário receberá o retorno da consulta em uma planilha Excel com os dados específicos.</li>
        <li><strong>Automação ANVISA:</strong> Este arquivo deve ser executado após o preenchimento dos números de registro no arquivo "Registros". Ao ser iniciado, o programa realizará a tarefa em primeiro ou segundo plano. Após o tempo necessário, os dados de cada produto estarão disponíveis na planilha Excel "Dados" (que não deve estar aberta durante a execução do programa).</li>
    </ul>

    <h2>Quem mantém e contribui com o projeto?</h2>
    <p>O projeto é mantido e desenvolvido por Matheus Canel e Vinicius Rocha, estagiários de STI no Real Hospital Português. Utilizamos a linguagem de programação Python, e as principais tecnologias empregadas incluem o framework de automação web Selenium e o chromedriver para integração com o navegador Google Chrome.</p>

</body>

</html>
