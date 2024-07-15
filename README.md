# Lab Aula Git e GitHub

Este é um projeto exemplo utilizado para demonstrar o uso básico do Git e GitHub.

## Descrição

Este projeto consiste em uma página web simples que lista alunos, onde cada aluno possui um ID, nome e email. A página
foi criada para ser utilizada em aulas práticas de Git e GitHub.

## Funcionalidades

Exibe uma lista de alunos em uma tabela. Cada aluno é representado por um ID, nome e email.

## Instale o VS Code:

Se você ainda não tem o Visual Studio Code instalado, siga as instruções em https://code.visualstudio.com/download para
instalar na sua máquina.

## Instale a extensão Live Server:

Instalar a extensão Live Server no Visual Studio Code para visualizar a página web.

## Instale o Git:

Se você ainda não tem o Git instalado, siga as instruções em https://git-scm.com/downloads para instalar o Git na sua
máquina.

## Abra o terminal do Visual Studio Code:

Abra o terminal do Visual Studio Code para executar os comandos do Git.

## Configure o Git:

Configure informações de usuário para todos os repositórios locais

```bash
git config --global user.name "[nome]"
```

Configura o nome que você quer ligado as suas transações de
commit

```bash
git config --global user.email "[endereco-de-email]"
```

Configura o email que você quer ligado as suas transações de commit

```bash
git config --global color.ui auto
```  

## Gere uma chave SSH:

Se você ainda não tem uma chave SSH configurada, siga as instruções
em https://docs.github.com/pt/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent?platform=windows
para gerar uma chave SSH e adicioná-la à sua conta do GitHub.

```bash
ssh-keygen -t ed25519 -C "your_email@example.com"
```

## Crie uma conta no GitHub:

Se você ainda não tem uma conta no GitHub, acesse https://github.com e crie uma conta.

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
```

## Entre no diretório do projeto:

```bash
cd nome-do-repositorio
```

## Git pull para atualizar o repositório:

```bash
git pull
```

## Git Fetch para trazer as branches do repositório remoto:

```bash
git fetch
```

## Abra o arquivo index.html em um navegador:

Abra o arquivo index.html em qualquer navegador web para visualizar a lista de alunos.

## Simulando Alterações no Projeto

Clone o repositório para sua máquina local.
Crie uma nova branch para suas alterações:

```bash
git checkout -b minha-feature
```

## Faça as alterações desejadas e adicione ao stage

Altere o arquivo index.html para adicionar um novo aluno à lista.

```bash
git add .
```

## Verifique o status das alterações

Verifique se as alterações foram adicionadas ao stage:

```bash
git status
```

Faça o commit das suas alterações
Adicione uma mensagem descritiva para o commit:

```bash
git commit -m "Adicionando nova feature"
```

## Faça o push para sua branch:

Envie suas alterações para o repositório remoto:

```bash
git push origin minha-feature
```

## Crie um Pull Request no GitHub:

Abra um Pull Request para revisão das alterações e posterior merge.

## Autor

Contato: seu-email@example.com
Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.

