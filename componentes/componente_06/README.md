## [COMPONENTE 06] Memória RAM de 8 bits

### Relatório

#### (i) Descrição
- **Funcionalidade:** Leitura e escrita de 8 endereços de 1 bit.  
- **Entradas:** `ADDR[2..0]`, `D_in`, `WE`, `CLK`  
- **Saída:** `D_out`  
- **Lógica:**  
  - `WE=1`: escreve `D_in`  
  - `WE=0`: lê `ADDR`

#### (iii) e (iv) Testes
- **Teste 1:** Escrever `1` em `ADDR=101`  
- **Teste 2:** Ler `ADDR=101` → `D_out=1`
