# ☁️ AWS EC2 & S3: Testes de Hospedagem e Infraestrutura

Este repositório contém os arquivos e testes práticos realizados para um trabalho focado em infraestrutura na **Amazon Web Services (AWS)**. 

O objetivo principal do projeto foi desenvolver páginas web simples (HTML/CSS) e realizar o deploy (hospedagem) dessas aplicações em diferentes ambientes e serviços da AWS, testando o provisionamento e o funcionamento de cada um.

## 🎯 Objetivo do Projeto
Validar o conhecimento prático na criação e configuração de serviços de computação e armazenamento na nuvem da AWS. Para tornar o teste mais visual e interessante, foram criadas interfaces HTML estilizadas que simulam "dashboards" de status para cada serviço que foi instanciado.

## 🚀 Serviços AWS Utilizados

Durante o trabalho, as páginas foram subidas nos seguintes ambientes:

*   **Amazon S3 (Simple Storage Service):** Hospedagem de site estático utilizando um *Bucket*.
*   **Amazon EC2 (Elastic Compute Cloud) - Linux:** Criação de uma instância virtual com sistema operacional Linux e configuração de um servidor web (como Apache ou Nginx) para hospedar a página.
*   **Amazon EC2 - Windows:** Criação de uma instância virtual com Windows Server, configurando o IIS (Internet Information Services) para colocar a aplicação no ar.

## 💻 Tecnologias Empregadas

*   **HTML5 & CSS3:** Criação de interfaces responsivas e modernas (utilizando Glassmorphism, animações CSS e SVG icons).
*   **AWS S3:** Armazenamento de objetos e hospedagem estática.
*   **AWS EC2:** Máquinas virtuais (Linux e Windows Server).
*   **Redes AWS:** Configuração de Security Groups para liberação de portas (HTTP/80 e HTTPS/443).

## 📁 Estrutura do Repositório

O projeto está dividido de acordo com os ambientes testados (branches/pastas):

- `balde/` (S3): Contém o HTML customizado indicando o provisionamento bem-sucedido do Bucket S3 (Private/Standard Storage).
- `Linux/`: Arquivos voltados para a instância EC2 rodando distribuição Linux.
- `Windows/`: Arquivos voltados para a instância EC2 rodando Windows Server.

## 🎨 Visualização

As páginas HTML desenvolvidas contam com um design clean e *dark mode*, incluindo:
- Feedback visual de status (LED verde pulsante indicando serviço ativo).
- Ícones representativos de cada serviço.
- Tipografia moderna (Google Fonts - Inter).

## 👨‍💻 Autor

Desenvolvido por **Luiz Souza** como parte de atividades práticas de infraestrutura em nuvem.

---
*Projeto criado para fins acadêmicos e testes práticos de Cloud Computing.*
