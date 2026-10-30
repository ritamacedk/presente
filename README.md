
# Trabalho 1 — Changelog e Release com GitHub Actions

## Integrantes
- Emily Mamedi Gonçalves RA:250358
- Nayara Rita Macedo Amador RA:250357

## Descricao do projeto
Este projeto demonstra o uso do GitHub Actions para automatizar
a documentacao das alteracoes e a publicacao de versoes do projeto.

## Action de Changelog
O Action Changelog atualiza automaticamente as alterações no arquivo README, ele consulta e formata de um jeito pretty(bonitinho) os 10 ultimos commits por data, autor e comentario, ele tira os commits que apenas atualizam o changelog e salva em um arquivo temporario, depois procura o marcador indicando o inicio e fim, adiciona o conteudo e salva.

<!-- CHANGELOG:START -->
- 2026-10-28 | ritar | Update README.md
- 2026-10-28 | ritar | Update and rename changelogtete.yml to changelog.yml
- 2026-10-21 | ritar | Create ReleasePackage.yml
- 2026-10-15 | ritar | Create changelogtete.yml
- 2026-10-15 | ritar | Create amengas2.yml
- 2026-10-15 | ritar | Create ameingas.yml
- 2026-10-15 | ritar | Initial commit
<!-- CHANGELOG:END -->

## Action de Release
Ele automatiza a criação de versoes do projeto no GitHub.
Ele baixa o código utilizando as actions, criando um arquivo .ZIP com o conteúdo que esta dentro do repositório, cria uma publicação da versão na parte de releases do github, dai é só anexar o arquivo zipado para as pessoas poderem baixar o nosso projeto.
