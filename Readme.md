# Planejamento do Projeto

## 1. Planejamento do Projeto
- **Objetivo:** Criar um site de Catálogo de Livros
- **Funcionalidades:**
  - Listar livros disponíveis.
  - Adicionar, editar e deletar livros.
  - Visualizar detalhes de um livro específico.
- **Tecnologias a serem usadas:**
  - **Frontend:** HTML, CSS, JavaScript.
  - **Backend:** Python (usando Flask, FastAPI ou Django).
  - **Banco de Dados:** MySQL
  - **Hospedagem:** AWS (EC2 para a aplicação e o banco de dados, e S3 para armazenar imagens ou arquivos).
  - **Servidor Web:** Nginx em um servidor Linux.
  - **Controle de Versão do Código:** Git e GitHub.

## 2. Configuração do Repositório Git
- **Passo 1: Entender o que é Git e Github**
  - Entender o que é Git
  - Entender o que é GitHub
  - Entender os principais comandos do Git
- **Passo 2: Configurar Git no ambiente de desenvolvimento**
  - Instalar Git no sistema (caso ainda não esteja instalado).
  - Configurar as informações de usuário:
    ```bash
    git config --global user.name "Nome"
    git config --global user.email "email@example.com"
    ```
  - Entender os principais comandos do Git.
- **Passo 3: Criar um novo repositório no GitHub**
  - Criar um repositório no GitHub para o projeto.
  - Entender a diferença entre repositório local e remoto.
- **Passo 4: Inicializar o repositório Git localmente**
  - Navegar até o diretório do projeto e inicializar o Git:
    ```bash
    git init
    ```
  - Conectar o repositório local ao repositório remoto no GitHub:
    ```bash
    git remote add origin <URL_do_repositorio>
    ```
- **Passo 5: Fazer o primeiro commit e push**
  - Adicionar os arquivos ao repositório:
    ```bash
    git add .
    ```
  - Fazer o primeiro commit:
    ```bash
    git commit -m "Initial commit"
    ```
  - Enviar o commit para o GitHub:
    ```bash
    git push -u origin main
    ```

### Exercício Prático:
- Crie um documento `README.md` no diretório raiz do seu projeto com:
  - Descrição do projeto.
  - Lista detalhada das funcionalidades.
  - Tecnologias escolhidas e justificativas.
  - Diagrama básico de arquitetura (pode ser uma imagem simples ou um diagrama de blocos).

## 3. Introdução à AWS e Criação de Conta
- **Passo 1: Entender o que é AWS**
  - AWS (Amazon Web Services) é uma plataforma de serviços de computação em nuvem que oferece uma ampla gama de serviços, incluindo computação, armazenamento, banco de dados, análise, e mais.
  - Pesquise sobre os principais serviços que a AWS oferece, como eles funcionam, e suas principais características. Entre eles: EC2, RDS, S3, Route53, Lambda.
- **Passo 2: Criar uma conta na AWS**
  - Acessar o [site da AWS](https://aws.amazon.com/) e seguir o processo para criar uma conta.
  - Entender o conceito de Free Tier, que oferece uma camada gratuita de serviços por um ano, ideal para aprendizado e pequenos projetos.
  - Configurar as informações de pagamento, entendendo que alguns serviços podem ter custos, mas dentro do Free Tier, a maioria dos serviços será gratuita.

### Exercício Prático:
- Crie um documento `AWS_Setup.md` detalhando:
  - Passos para criação da conta.
  - Serviços que planeja utilizar.
  - Limites do Free Tier.
- O arquivo deve estar no repositório do GitHub.

## 4. Introdução ao Linux e Conceitos Básicos de Sistemas Operacionais
- **Passo 1: Entender o que é Linux**
  - Linux é um sistema operacional de código aberto amplamente utilizado em servidores, dispositivos móveis, e computadores pessoais. Ele é conhecido por sua estabilidade, segurança e flexibilidade.
  - Entender a diferença entre Linux e outros sistemas operacionais como Windows e macOS.
  - Entender as diferenças entre distribuições Linux.
- **Passo 2: Entender a estrutura de diretórios no Linux**
  - Explicar o conceito de diretórios (pastas) e como eles organizam o sistema de arquivos.
  - **Diretórios Importantes:**
    - `/`: Diretório raiz, o ponto de partida de toda a árvore de diretórios.
    - `/home`: Contém os diretórios pessoais dos usuários.
    - `/etc`: Contém arquivos de configuração do sistema.
    - `/var`: Contém arquivos variáveis, como logs e dados temporários.
    - `/usr`: Contém programas e bibliotecas compartilhadas.
    - `/bin`, `/sbin`: Contêm executáveis essenciais do sistema.
- **Passo 3: Comandos básicos de Linux para gerenciar o sistema**
  - **Navegação:**
    - `ls`: Lista arquivos e diretórios.
    - `cd`: Muda o diretório atual.
    - `pwd`: Exibe o caminho do diretório atual.
  - **Manipulação de Arquivos e Diretórios:**
    - `cp`: Copia arquivos ou diretórios.
    - `mv`: Move ou renomeia arquivos ou diretórios.
    - `rm`: Remove arquivos ou diretórios.
    - `mkdir`: Cria um novo diretório.
    - `touch`: Cria um novo arquivo vazio.
  - **Gerenciamento de Permissões:**
    - `chmod`: Altera permissões de arquivos e diretórios.
    - `chown`: Altera o proprietário de arquivos e diretórios.
  - **Visualização e Edição de Arquivos:**
    - `cat`: Exibe o conteúdo de um arquivo.
    - `nano`, `vim`: Editores de texto para modificar arquivos.
  - **Comandos de Sistema:**
    - `sudo`: Executa comandos como superusuário (administrador).
    - `ps`: Exibe processos em execução.
    - `kill`: Encerra processos.
    - `df`, `du`: Mostra o uso de espaço em disco.
    - `top`: Monitora os processos em tempo real.
- **Passo 4: Praticar comandos no terminal**
  - Abrir o terminal e executar os comandos básicos para se familiarizar com a interface de linha de comando.
  - Praticar a navegação pelo sistema de arquivos, a criação e manipulação de arquivos e diretórios, e o uso de permissões.
- **Passo 5: Pesquisar por mais 20 comandos que não foram listados acima, entender como eles funcionam, e anotar.**

### Exercício Prático:
1. **Configuração Inicial do Ambiente Linux:**
   - Se estiver usando Windows, instale o WSL (Windows Subsystem for Linux) ou use uma máquina virtual.
   - Familiarize-se com a linha de comando executando comandos básicos (`ls`, `cd`, `mkdir`, etc.).
2. **Criar um Guia de Comandos:**
   - Crie um documento `Linux_Basics.md` listando os comandos aprendidos e exemplos de uso.
3. **Adicionar Comandos Avançados:**
   - Liste e explique 20 comandos adicionais pesquisados.
   - O arquivo deve estar no repositório do GitHub.

## 5. Configuração do Backend
- **Passo 6: Configurar o ambiente de desenvolvimento com Python**
  - Instalar o Python e configurar um ambiente virtual (`virtualenv`).
  - Entender como funciona o ambiente virtual em Python.
  - Escolher entre Flask, FastAPI ou Django para o desenvolvimento do Backend.
  - Fazer commits e pushes regulares para salvar o progresso no GitHub e não perder o código local.
- **Passo 7: Criar as rotas básicas para o CRUD de livros no Flask, FastAPI ou Django**
  - Rota para listar livros.
  - Rota para adicionar um livro.
  - Rota para editar um livro.
  - Rota para deletar um livro.
  - Fazer commits no GitHub com mensagens descritivas após a implementação de cada rota.

## 6. Configuração do Banco de Dados MySQL no EC2
- **Passo 8: Configurar uma nova instância EC2 para o MySQL**
  - Entender conceitos de Banco de Dados, Estrutura de Dados, Tabela, Índice.
  - Entender tipos de Bancos de Dados Relacionais existentes.
  - **Criação da instância EC2:**
    - Criar uma nova instância EC2 (Ubuntu ou outra distro Linux) para hospedar o banco de dados MySQL.
    - Acessar a instância via SSH.
  - **Instalação do MySQL:**
    - Atualizar pacotes do sistema:
      ```bash
      sudo apt update
      sudo apt upgrade
      ```
    - Instalar o MySQL Server:
      ```bash
      sudo apt install mysql-server
      ```
    - Entender o conceito de serviços e como o MySQL roda como um daemon.
  - **Configuração do MySQL:**
    - Acessar o MySQL:
      ```bash
      sudo mysql
      ```
    - Configurar o MySQL com um usuário e senha para a aplicação.
    - Criar um banco de dados para o projeto.
  - **Segurança do MySQL:**
    - Executar o comando para melhorar a segurança:
      ```bash
      sudo mysql_secure_installation
      ```
    - Configurar o MySQL para permitir conexões remotas (se necessário) e configurar o Security Group da AWS para permitir conexões na porta 3306.
- **Passo 9: Conectar o Backend ao Banco de Dados MySQL**
  - Instalar o conector MySQL em Python:
    ```bash
    pip install mysql-connector-python
    ```
  - Configurar a aplicação Python para se conectar ao banco de dados MySQL na EC2.
  - Fazer commits e pushes regulares com as configurações do banco de dados no GitHub.

### Exercício Prático:
- Documente o passo a passo para recriar o ambiente no GitHub em um arquivo chamado `MySQL_Setup.md`.

## 7. Desenvolvimento do Frontend
- **Passo 10: Criar as páginas HTML para as funcionalidades do CRUD**
  - Página para listar todos os livros.
  - Página para adicionar um novo livro.
  - Página para editar um livro existente.
  - Página para visualizar os detalhes de um livro.
  - Fazer commits com mensagens descritivas após a criação de cada página.
  - **Crie as páginas HTML necessárias:**
    - `index.html` para listar livros.
    - `add_book.html` para adicionar um novo livro.
    - `edit_book.html` para editar um livro existente.
    - `book_details.html` para visualizar detalhes de um livro.
- **Passo 11: Aplicar estilos com CSS**
  - Tornar o site visualmente atraente e responsivo.
  - Fazer commits e pushes regulares conforme os estilos forem adicionados.
  - Assegure-se de que o site seja responsivo.
- **Passo 12: Adicionar funcionalidades interativas com JavaScript**
  - Validar formulários no Frontend.
  - Fazer chamadas assíncronas para o Backend usando Fetch API ou Axios.
  - Continuar fazendo commits com mensagens claras após cada alteração.

## 8. Configuração de Servidor Linux e Web Server
- **Passo 13: Configurar uma instância EC2 na AWS para hospedar a aplicação**
  - **Criação da instância EC2:**
    - Entender o conceito de SSH (Secure Shell) e como ele é usado para acessar servidores remotamente.
    - Criar uma instância EC2 com Linux (Ubuntu) dentro do Free Tier.
    - Acessar a instância EC2 via SSH usando um terminal.
  - **Configuração básica do Linux:**
    - Entender o conceito de usuários e permissões no Linux.
    - Atualizar pacotes do sistema:
      ```bash
      sudo apt update
      sudo apt upgrade
      ```
    - Entender o que é um daemon e como serviços rodam em background.
- **Passo 14: Instalar e configurar o servidor Web (Nginx ou Apache)**
  - Instalar Nginx ou Apache na instância EC2.
    ```bash
    sudo apt install nginx
    ```
    ou
    ```bash
    sudo apt install apache2
    ```
  - Entender o conceito de servidor web e como ele serve arquivos estáticos e dinâmicos.
  - Configurar o servidor para servir o Frontend e o Backend.
  - Configurar o firewall do Linux (usando `ufw` ou configurando regras de segurança na AWS) para permitir o tráfego nas portas 80 (HTTP) e 443 (HTTPS).
    ```bash
    sudo ufw allow 'Nginx Full'
    ```
    ou para Apache:
    ```bash
    sudo ufw allow 'Apache Full'
    ```
  - Entender o conceito de arquivos de configuração (como `nginx.conf` ou `apache2.conf`).
- **Passo 15: Testar a aplicação em produção**
  - Acessar a aplicação via o IP público da EC2.
  - Garantir que todas as funcionalidades estejam funcionando.
  - Fazer o deploy do código mais recente a partir do repositório GitHub:
    ```bash
    git pull origin main
    ```
  - Documente as configurações realizadas em um arquivo `Server_Setup.md`.
  - Adicione e faça o commit deste arquivo.

## 9. Deploy e Monitoramento
- **Passo 16:**
  - Entender conceitos de deploy e suas derivações.
  - Entender conceitos de monitoramento e observabilidade.
  - Configurar S3 para armazenar arquivos estáticos (se necessário).
    - Criar um bucket no S3.
    - Configurar permissões e armazenamento de imagens ou outros arquivos.
    - Fazer commits e pushes após configurar o armazenamento de arquivos.
- **Passo 17: Monitorar o uso de recursos na AWS para evitar custos extras**
  - Utilizar o AWS CloudWatch para monitoramento básico.
  - Verificar o consumo do Free Tier.

## 10. Entrega e Revisão

### Subetapas:
1. **Revisar o projeto completo.**
2. **Garantir que todas as funcionalidades estejam implementadas e funcionando.**
3. **Revisão final e documentação completa.**

### Exercício Prático:
1. **Testes Finais:**
   - Realize testes completos de todas as funcionalidades do site.
   - Verifique a integração entre frontend, backend e banco de dados.
   - Assegure-se de que a aplicação está estável e segura.
2. **Documentação Final:**
   - Atualize o `README.md` com instruções de instalação, configuração e uso.
   - Adicione diagramas de arquitetura, se necessário.
   - Prepare uma apresentação final resumindo o projeto, desafios enfrentados e soluções implementadas.
3. **Preparação para a Entrega:**
   - Revise todo o código para garantir a qualidade e aderência às boas práticas.
   - Assegure-se de que o repositório no GitHub está organizado e documentado.
4. **Commit Final:**
   - Adicione todas as atualizações de documentação e ajustes finais no código.
   - Faça um commit com uma mensagem descritiva.
