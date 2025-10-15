### [COMPONENTE 14]. Detector de paridade ímpar

* **Descrição (os pinos e a lógica) do componente e sua funcionalidade**
    * **Funcionalidade:** Detecta se o número de bits ‘1’ em uma entrada é ímpar (4 bits de entrada).
    * **Pinos de Entrada:** `A, B, C, D`.
    * **Pino de Saída:** `P`.
    * **Lógica:** `P = A XOR B XOR C XOR D`, implementado com portas AND, OR e NOT.

* **Os testes do componente e descrição dos testes**
    * **Teste 1: Paridade ímpar**
        * **Entrada:** `A=1, B=0, C=0, D=0`.
        * **Resultado:** `P=1`.
    * **Teste 2: Paridade par**
        * **Entrada:** `A=1, B=0, C=1, D=0`.
        * **Resultado:** `P=0`.

