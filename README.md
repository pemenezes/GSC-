# GSC-
Este projeto tem como objetivo reduzir os impactos de falhas de energia em hospitais, garantindo que setores essenciais mantenham a comunicação e o monitoramento de equipamentos críticos funcionando mesmo em apagões.

Tecnologias Utilizadas
Linguagem: C# (.NET)

Banco de Dados: Oracle Database

IDE: Visual Studio 2022

Bibliotecas: Oracle Managed Data Access

📂 Estrutura do Projeto
📁 GS3ESPX
│── 📂 Models         # Estruturas de dados do sistema (EventLog, ChatMessage, etc.)
│── 📂 Controllers    # Lógica de cada funcionalidade (FailureLogController, CommunicationController)
│── 📂 Views         # Interface do usuário via console (EventLogView, CommunicationView, etc.)
│── 📂 Database      # Scripts e integração com o banco de dados
│── 📜 Program.cs    # Arquivo principal que inicializa o sistema
│── 📜 README.md     # Documento explicativo do projeto

🚀 Como Executar
1️⃣ Configurar o Banco de Dados
Antes de rodar o sistema, crie as tabelas necessárias no Oracle Database utilizando os scripts SQL disponíveis na pasta 📂 Database

2️⃣ Clonar o Repositório
Baixe o projeto no seu computador

3️⃣ Abrir no Visual Studio
Abra o Visual Studio 2022

Carregue o projeto GS3ESPX

Confirme que todas as dependências (.NET e Oracle Managed Data Access) estão instaladas.

4️⃣ Executar
Basta rodar o projeto no Visual Studio! Acesse o menu principal e utilize as funcionalidades do sistema conforme necessário.

📌 Funcionalidades
✔ Registro de falhas → Identifica e registra falhas de energia no banco de dados ✔ Geração de alertas → Monitora geradores e equipamentos hospitalares ✔ Logs de eventos → Registra ações críticas e auditoria do sistema ✔ Relatórios de status → Gera históricos sobre equipamentos e geradores ✔ Comunicação interna → Permite troca de mensagens entre setores
