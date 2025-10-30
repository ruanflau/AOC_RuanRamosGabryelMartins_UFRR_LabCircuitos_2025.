## [COMPONENTE 04] Somador de 8 bits (A + 4)

### Relatório

#### (i) Descrição
- **Funcionalidade:** Soma uma entrada de 8 bits com o valor constante `4`.  
- **Entradas:** `A[7..0]`  
- **Saídas:** `S[7..0]`, `Cout`  
- **Lógica:** `S = A + 00000100`

#### (iii) e (iv) Testes
- **Teste 1:** `A=00010000` (16) → `S=00010100` (20), `Cout=0`  
- **Teste 2:** `A=11111100` (252) → `S=00000000`, `Cout=1`
