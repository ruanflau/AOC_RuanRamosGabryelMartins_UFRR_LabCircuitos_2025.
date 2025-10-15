<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Laboratório de Circuitos - AOC</title>
    <style>
        body {
            font-family: sans-serif;
            line-height: 1.6;
            margin: 2em;
        }
        h1, h2 {
            border-bottom: 1px solid #ccc;
            padding-bottom: 5px;
        }
        code {
            background-color: #f4f4f4;
            padding: 2px 4px;
            border-radius: 3px;
        }
        ul {
            padding-left: 20px;
        }
    </style>
</head>
<body>

    [cite_start]<h1>Laboratório de Circuitos - Arquitetura e Organização de Computadores (2025) [cite: 2, 5]</h1>
    <p>
        [cite_start]Este repositório contém as soluções para o trabalho de laboratório da disciplina de Arquitetura e Organização de Computadores [cite: 2][cite_start], do Departamento de Ciência da Computação (DCC) [cite: 2, 3] [cite_start]da Universidade Federal de Roraima (UFRR)[cite: 1, 2].
    </p>

    <h2>Objetivo</h2>
    <p>
        [cite_start]O objetivo deste trabalho é implementar e simular diversos componentes de circuitos digitais utilizando o Logisim[cite: 8]. [cite_start]Cada componente deve ser acompanhado de um relatório técnico que descreva a solução com o máximo de detalhes possível[cite: 6].
    </p>

    <h2>Estrutura do Relatório</h2>
    <p>
        [cite_start]Para cada componente desenvolvido, a documentação deve apresentar[cite: 8]:
    </p>
    <ul>
        [cite_start]<li><strong>Descrição do Componente</strong>: Detalhamento dos pinos, da lógica interna e da funcionalidade geral do circuito[cite: 8].</li>
        [cite_start]<li><strong>Imagem do Circuito</strong>: Captura de tela da implementação dos componentes do circuito integrado[cite: 9].</li>
        [cite_start]<li><strong>Testes do Componente</strong>: Evidências dos testes realizados, como análises de tabela-verdade ou testes de unidade[cite: 6, 9].</li>
        [cite_start]<li><strong>Descrição dos Testes</strong>: Explicação detalhada dos testes, apresentando os pinos de entrada, as conexões ativas e os resultados obtidos nos pinos de saída[cite: 10].</li>
    </ul>

    <h2>Componentes a Serem Implementados</h2>
    <p>
        A lista de componentes a serem implementados é a seguinte:
    </p>
    <ul>
        [cite_start]<li><strong>Registrador Flip-Flop</strong>: Tipos D e JK[cite: 11].</li>
        [cite_start]<li><strong>Multiplexador</strong>: Com quatro opções de entrada[cite: 12].</li>
        [cite_start]<li><strong>Porta Lógica XOR</strong>: Implementada utilizando apenas os componentes AND, NOT e OR[cite: 13].</li>
        [cite_start]<li><strong>Somador de 8 bits (Valor Fixo)</strong>: Recebe um valor inteiro e o soma com a constante 4[cite: 14].</li>
        [cite_start]<li><strong>Memória ROM</strong>: Com capacidade de 8 bits[cite: 15].</li>
        [cite_start]<li><strong>Memória RAM</strong>: Com capacidade de 8 bits[cite: 16].</li>
        [cite_start]<li><strong>Banco de Registradores</strong>: Com capacidade para 8 bits[cite: 17].</li>
        [cite_start]<li><strong>Somador</strong>: Com capacidade para 8 bits[cite: 18].</li>
        [cite_start]<li><strong>Detector de Sequência</strong>: Para identificar a sequência binária "101" em um fluxo de entrada[cite: 19].</li>
        [cite_start]<li><strong>ULA (Unidade Lógica e Aritmética)</strong>: De 8 bits, com suporte às operações AND, OR, NOT, NOR, NAND, XOR, SHIFT de 2 bits à esquerda, SHIFT à direita, soma e subtração[cite: 20].</li>
        [cite_start]<li><strong>Extensor de Sinal</strong>: Converte uma entrada de 4 bits para uma saída de 8 bits[cite: 21].</li>
        [cite_start]<li><strong>Máquina de Estados</strong>: Implementada com portas lógicas[cite: 22].</li>
        [cite_start]<li><strong>Contador Síncrono</strong>[cite: 23].</li>
        [cite_start]<li><strong>Detector de Paridade Ímpar</strong>: Utilizando portas AND, OR e NOT para identificar entradas com um número ímpar de bits '1'[cite: 24].</li>
        [cite_start]<li><strong>Otimização Lógica</strong>: Resolução de um problema utilizando Mapas de Karnaugh e implementação do circuito otimizado[cite: 25].</li>
        [cite_start]<li><strong>Decodificador de 7 Segmentos</strong>: Converte um número binário de 4 bits para acionar um display de 7 segmentos no formato hexadecimal[cite: 26].</li>
        [cite_start]<li><strong>Detector de Número Primo</strong>: Circuito que detecta se uma entrada binária de 4 bits representa um número primo, simplificado com Mapas de Karnaugh[cite: 27, 28].</li>
    </ul>

    <h2>Instruções de Entrega</h2>
    <p>
        [cite_start]Todos os artefatos gerados (relatório, código-fonte, etc.) devem ser adicionados a um repositório no GitHub[cite: 7]. [cite_start]O nome do repositório deve seguir o formato: <code>AOC_Nome1Nome2_UFRR_LabCircuitos_2025</code>[cite: 7].
    </p>

</body>
</html>

## Instruções de Entrega

[cite_start]Todos os artefatos gerados (relatório, códigos-fonte, etc.) devem ser versionados em um repositório no GitHub. [cite: 7] [cite_start]O nome do repositório deve seguir o formato: `AOC_Nome1Nome2_UFRR_LabCircuitos_2025`. [cite: 7]
