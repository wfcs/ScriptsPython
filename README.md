# SpeedTest com Streamlit

Este projeto é uma aplicação simples desenvolvida em Python, utilizando a biblioteca **Streamlit**, para testar a velocidade de internet de maneira interativa. A aplicação mede a velocidade de download, upload e o ping, exibindo os resultados na interface do usuário.

## 📋 Funcionalidades

- Teste a **velocidade de download** da sua internet.
- Teste a **velocidade de upload** da sua internet.
- Verifique o **ping** em milissegundos (ms).
- Visualize os resultados de forma intuitiva com barras de progresso.

## 🛠️ Requisitos

- **Python 3.7 ou superior**
- Bibliotecas necessárias:
  - `streamlit`
  - `speedtest-cli`

## 🚀 Como usar

1. **Clone ou baixe este repositório**:
 ```bash
 git clone https://github.com/seu-usuario/speedtest-streamlit.git
 cd speedtest-streamlit
  ```
2. **Instale as dependências**:

  ```bash

pip install streamlit speedtest-cli
  ```
3. **Execute a aplicação**:

  ```bash

streamlit run app.py
  ```
4. **Abra no navegador**:

> O Streamlit fornecerá um link (geralmente http://localhost:8501) para acessar a aplicação.

5. **Inicie o teste de velocidade**:
 
> Clique no botão "Iniciar" para executar o teste.

## 📝 Estrutura do Código
- Interface:
  - `st.header()`: Exibe o título da aplicação.
  - `st.button()`: Inicia o teste de velocidade ao ser clicado.
  - `st.progress()`: Exibe uma barra de progresso para download e upload.
- Lógica do SpeedTest:
  - Utiliza a biblioteca `speedtest` para medir a velocidade de download e upload, além do ping.
  - Os resultados são calculados em Mbps e apresentados de forma clara.
  - 
## 🎯 Exemplos de Resultados
  - Velocidade de Download: 50.25 Mbps
  - Velocidade de Upload: 20.15 Mbps
  - Ping: 12 ms
    
## 🤔 Observações
  - O limite da barra de progresso está configurado como 100 Mbps. Se necessário, ajuste o valor da variável `max_speed` no código para velocidades maiores.
## 📄 Licença
  - Este projeto está licenciado sob a MIT License. Você pode utilizá-lo e modificá-lo conforme necessário.
    
