
# 🌤 Consulta Clima - Previsão do Tempo para São Paulo

Este é um script em Python que coleta a previsão do tempo para a cidade de São Paulo usando o Google e salva os dados em um arquivo Excel para histórico.

🚀 Funcionalidades

✅ Consulta a temperatura e umidade do ar de São Paulo
✅ Classifica a umidade do ar em diferentes alertas (baixa, média, alta)
✅ Armazena os dados em um arquivo Excel (historico_temperatura.xlsx)
✅ Interface gráfica simples para atualização manual dos dados

 📞 Pré-requisitos

Python 3.x

Google Chrome instalado

Bibliotecas necessárias (instale com pip):

pip install selenium openpyxl

 🛠 Como Usar

Clone o repositório

git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio

Execute o script

python consulta-clima.py

Interaja com a interface gráfica

Clique no botão "Buscar previsão" para coletar e armazenar os dados.

📝 Estrutura do Projeto

📂 projeto
│─ consulta-clima.py  # Script principal
│─ historico_temperatura.xlsx  # Arquivo Excel (criado automaticamente)
│─ README.md  # Documentação

⚠️ Observações

O script usa o Selenium para buscar informações no Google. Certifique-se de ter o ChromeDriver compatível com a sua versão do Chrome.

A primeira execução pode ser um pouco mais lenta devido ao carregamento do navegador.

🐟 Licença

Este projeto está sob a licença MIT.

