# Instruções de Utilização — Projeto_Completo


## 1. Executar o `Projeto_Completo.exe`

- Inicie o arquivo `Projeto_Completo.exe`
- Ele prepara os arquivos necessários para a aplicação;
- Gera automaticamente os seguintes executáveis:
  - `Projeto_GRPC.exe`
  - `Display.exe`


---

## 2. Executar o `Projeto_GRPC.exe`

- Depois que os executáveis forem gerados, execute `Projeto_Completo.exe`:
- Um terminal será aberto;
- Esse terminal representa o servidor da aplicação;
- Enquanto essa janela estiver aberta, o servidor estará funcionando corretamente.
- **Durante o uso do sistema, não feche essa janela**

---

## 3. Executar o `Display.exe`

- Com o servidor já em execução, execute `Display.exe`:
- A interface gráfica da aplicação será iniciada;
- O programa irá se conectar automaticamente ao servidor gRPC;
- Após a conexão, o sistema estará pronto para uso.

---

## Encerrando a Aplicação

Para finalizar o sistema corretamente:

1. Feche a janela do `Display.exe`;
2. Em seguida, feche a janela do `Projeto_GRPC.exe`.

Após isso, toda a execução do sistema será encerrada.

## Observação

Caso execute novamente `Projeto_Completo.exe`, irá aparecer uma tela de terminal perguntando se deseja substituir `Projeto_GRPC.exe` e `Display.exe`, basta digitar `Q` e apertar **ENTER**.  