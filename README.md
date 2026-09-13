# Uso de repositório de artefatos em Gestão de Configuração

O GitHub é uma plataforma que apoia o processo de desenvolvimento do software, desde o planejamento do trabalho até a implantação e operação, onde podemos armazenar, versionar e compartilhar projetos.

A Gestão de Projetos durante o ciclo de vida do desenvolvimento de software permite acompanhar todas as etapas pelas quais um projeto de software passa, desde a primeira ideia até a execução de código em produção.

Através do sistema de controle de versão do Git podemos gerenciar, compartilhar e acompanhar as alterações no código.

Para esta aula prática vamos criar, configurar e compartilhar um repositório na página do GitHub.

## Criação do repositório

Começamos entrando no perfil do usuário, no caso **GitMariac**, e criando o repositório que nomeamos de **criando-repo**.

Deixamos sua visibilidade **Pública** para que outras pessoas tenham acesso ao repositório e, inicialmente, não adicionamos o `README.md`, pois iremos criá-lo no VSCode.

![Criação do repositório no GitHub](assets/1.png)

Ao clicarmos em **Create repository**, temos acesso ao link gerado do nosso repositório recém-criado, o qual copiamos para clonarmos no Git Bash.

![Link do repositório criado](assets/2.png)

## Clonando o repositório

Já no Bash, direcionamos a pasta na qual iremos trabalhar e clonamos nosso repositório com o comando git clone + shift Insert para colar o caminho copiado. Com isso o bash cria um git local oculto na pasta.  

![Terminal do Bash](assets/3.png)

Feito isso, abrimos o VScode já na pasta e criamos um README.md em seguida uma pasta assets para adicionarmos gravuras posteriormente.

![Terminal do VSCode](assets/4.png)