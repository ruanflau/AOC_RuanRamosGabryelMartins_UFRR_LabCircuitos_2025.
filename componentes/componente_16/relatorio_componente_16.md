### [COMPONENTE 16]. Decodificador de 7 Segmentos

* **Descrição (os pinos e a lógica) do componente e sua funcionalidade**
    * **Funcionalidade:** Converte um número binário de 4 bits em sinais para um display de 7 segmentos (formato hexadecimal).
    * **Pinos de Entrada:** `D[3..0]`.
    * **Pinos de Saída:** `a, b, c, d, e, f, g`.
    * **Lógica:** Cada segmento é controlado por um circuito lógico combinacional baseado na tabela verdade das 16 combinações de entrada.

* **Os testes do componente e descrição dos testes**
    * **Teste 1: Exibição do dígito ‘8’**
        * **Entrada:** `D=1000`.
        * **Resultado:** Todos os segmentos (`a,b,c,d,e,f,g`) acesos (`1`).
    * **Teste 2: Exibição do caractere ‘C’**
        * **Entrada:** `D=1100`.
        * **Resultado:** Segmentos `a, d, e, f` acesos (`1`); `b, c, g` apagados (`0`).
