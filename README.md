# Atividade_1
1. Relatório de Versionamento – Projeto Casa de Leilões
2.1 Acesso ao diretório do projeto
No Git Bash, foi acessada a pasta onde o projeto Java já estava iniciado:

cd caminho/da/pasta/do/projeto
2.2 Inicialização do repositório Git local
Foi inicializado o repositório local:

git init

📌 Resultado: criação da pasta oculta .git, tornando o diretório versionado.
2.3 Adição dos arquivos ao controle de versão
Todos os arquivos do projeto foram adicionados à área de stage:

git add .
2.4 Primeiro commit
Foi realizado o commit inicial com a mensagem solicitada:

git commit -m "Projeto inicial"

📌 Resultado: criação do histórico inicial do projeto no Git.
2.5 Criação do repositório remoto
No GitHub, foi criado um novo repositório chamado casa-leiloes (sem README inicial).
2.6 Associação do repositório remoto
No Git Bash, o repositório local foi vinculado ao repositório remoto:

git remote add origin https://github.com/seu-usuario/casa-leiloes.git
2.7 Envio dos arquivos ao GitHub
O código foi enviado para o repositório remoto:

git push -u origin main
(ou master, dependendo do nome do branch padrão do Git instalado)

📌 Resultado: os arquivos passaram a estar disponíveis no GitHub, permitindo o trabalho colaborativo e o controle de versões.
3. Conclusão
Com os procedimentos descritos, o projeto Java da casa de leilões foi devidamente versionado utilizando Git e integrado ao GitHub. A partir deste ponto, será possível:
- Manter histórico das alterações.
- Trabalhar em equipe de forma organizada.
- Garantir segurança e qualidade no desenvolvimento.

