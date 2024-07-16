<div align="center">

[![PauloMedinabr01 - lab-aula-git-github](https://img.shields.io/static/v1?label=PauloMedinabr01&message=lab-aula-git-github&color=blue&logo=github)](https://github.com/PauloMedinabr01/lab-aula-git-github "Go to GitHub repo")
[![stars - lab-aula-git-github](https://img.shields.io/github/stars/PauloMedinabr01/lab-aula-git-github?style=social)](https://github.com/PauloMedinabr01/lab-aula-git-github)
[![forks - lab-aula-git-github](https://img.shields.io/github/forks/PauloMedinabr01/lab-aula-git-github?style=social)](https://github.com/PauloMedinabr01/lab-aula-git-github)

</div>

# Lab Aula Git e GitHub

<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"><img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"><img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white">
<img src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white"><img src="https://img.shields.io/badge/Visual_Studio_Code-0078D6?style=for-the-badge&logo=visual-studio-code&logoColor=white">
<img src="https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white">

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

## Referências

- [GitSCM](https://git-scm.com/)
- [Git Documentation](https://git-scm.com/doc)
- [GitHub Cheat Sheet](https://training.github.com/)
- [Visual Git Cheat Sheet](https://ndpsoftware.com/git-cheatsheet.html#loc=index;)
- [GitHub](https://github.com/)
- [Visual Studio Code](https://code.visualstudio.com/)

## Autor: Paulo Coelho

### Contato:

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:paulomedinabr01@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/paulohcoelho/)

## Outras ferramentas para praticar Git.

[Visualizing Git](https://git-school.github.io/visualizing-git/)

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.

