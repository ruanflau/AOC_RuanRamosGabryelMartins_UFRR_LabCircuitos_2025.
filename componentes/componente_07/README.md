## [COMPONENTE 07] Banco de Registradores de 8 bits

### Relatório

#### (i) Descrição
- **Funcionalidade:** Conjunto de registradores de acesso rápido.  
- **Entradas:** `Write Data[7..0]`, `Write Address`, `Read Address`, `Write Enable`, `CLK`  
- **Saída:** `Read Data[7..0]`

#### (iii) e (iv) Testes
- **Escrita:** `Write Data=10101010`, `Addr=2`, `WE=1`  
- **Leitura:** `Read Addr=2`, `WE=0` → `Read Data=10101010`
