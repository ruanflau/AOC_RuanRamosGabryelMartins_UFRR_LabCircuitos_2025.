## [COMPONENTE 10] ULA de 8 bits (AND, OR, NOT, NOR, NAND, XOR, SHIFT, Soma, Subtração)

### Relatório

#### (i) Descrição
- **Entradas:** `A[7..0]`, `B[7..0]`, `OP[3..0]`  
- **Saída:** `Y[7..0]`  
- **Lógica:** Multiplexador seleciona a operação conforme `OP`.

#### (iii) e (iv) Testes
- **OR:** `A=11001100`, `B=10101010` → `Y=11101110`  
- **Subtração:** `A=15`, `B=9` → `Y=6`
