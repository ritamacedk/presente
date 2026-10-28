
# Trabalho 1 — Changelog e Release com GitHub Actions

## Integrantes
- Emily Mamedi Gonçalves RA:250358
- Nayara Rita Macedo Amador RA:250357

## Descricao do projeto
Este projeto demonstra o uso do GitHub Actions para automatizar
a documentacao das alteracoes e a publicacao de versoes do projeto.

## Action de Changelog
A Action consulta as mensagens dos commits e registra as ultimas
alteracoes diretamente nesta secao do README.md.

<!-- CHANGELOG:START -->
Ainda nao ha alteracoes registradas.
<!-- CHANGELOG:END -->

## Action de Release
A Action de Release e executada manualmente pela aba Actions,
utilizando o botao Run workflow. O usuario informa a versao,
e o workflow cria um pacote ZIP do projeto e publica uma Release
na secao Releases do GitHub, anexando o arquivo para download.
