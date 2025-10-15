### [COMPONENTE 06]. Memória RAM de 8 bits

* **Descrição (os pinos e a lógica) do componente e sua funcionalidade**
    * **Funcionalidade:** Armazena e permite leitura de múltiplos bits de dados (8 endereços × 1 bit).
    * **Pinos de Entrada:**
        * `ADDR[2..0]`: Seleciona um dos 8 endereços.
        * `D_in`: Dado de 1 bit a ser escrito.
        * `WE`: Habilita escrita (`1`) ou leitura (`0`).
        * `CLK`: Sincroniza a operação.
    * **Pino de Saída:** `D_out`: Dado lido do endereço selecionado.
    * **Lógica:**  
      - Se `WE=1`, na borda de subida de `CLK`, grava `D_in` em `ADDR`.  
      - Se `WE=0`, `D_out` reflete o conteúdo de `ADDR`.

* **Os testes do componente e descrição dos testes**
    * **Teste 1: Escrita**
        * **Entrada:** `ADDR = 101`, `D_in = 1`, `WE = 1`.
        * **Resultado:** Valor `1` armazenado no endereço 5.
    * **Teste 2: Leitura**
        * **Entrada:** `ADDR = 101`, `WE = 0`.
        * **Resultado:** `D_out = 1`
