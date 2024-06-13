![Imagem](coders_santander.png)
###### Repositório criado para os projetos realizados através do programa sem fins lucrativos do [Santander Coders](https://ada.tech/sou-aluno/programas/santander-coders-2024) na trilha de Front-end :)
### Conteúdo didático disponibilizado:
- [x] Front-end Estático — HTML e CSS
- [x] Lógica de Programação — JavaScript
- [x] Programação Orientada a Objetos — JavaScript
- [x] Front-end Dinâmico — JavaScript DOM
- [x] Angular I
- [x] Angular II

`HTML` `CSS` `JavaScript`

## // ANOTAÇÕES E LEMBRETES

## Versionamento
    - Registro de mudanças em arquivos
    - Recuperação e acesso a versões anteriores
    - Desenvolvimento de código em equipe

## Git
    - Sistema de versionamento de código
    - Armazena registros de versões como snapshots
    - Faz referência e caminho para os snapshots
    - A maioria das operações são locais

## Git Diff
    - Compara diferenças entre arquivos ou commits
    - Mostra alterações linha por linha
    - Útil para revisar mudanças antes de fazer um commit

## Git Commit
    - Salva as alterações no repositório
    - Cria um snapshot do estado atual do projeto
    - Inclui uma mensagem descritiva sobre as mudanças

## Configuração Inicial
```git config --global user.name "Seu Nome"``` — Configura o nome de usuário para *commits*<br>
```git config --global user.email "seuemail@example.com"``` — Configura o e-mail para *commits*

## Criar Repositório
```git init``` — Inicializa um novo repositório Git no diretório atual

## Clonar Repositório
```git clone <url_do_repositório>``` — Clona um repositório remoto para o seu computador

## Trabalhando com Mudanças
```git status``` — Verifica o estado das alterações<br>
```git add <arquivo>``` — Adiciona arquivos ao índice para serem incluídos no próximo *commit*<br>
```git add .```<br>
```git commit -m "mensagem do commit"``` — Registra as mudanças no repositório, com uma mensagem descritiva

## Ramificação e Fusão
```git branch``` — Lista todas as ramificações<br>
```git branch <nome_da_ramificação>``` — Cria uma nova ramificação<br>
```git checkout <nome_da_ramificação>``` — Muda para a ramificação especificada<br>
```git merge <nome_da_ramificação>``` — Funde a ramificação especificada na ramificação atual<br>

## Sincronização com Repositório Remoto
```git remote add origin <url_do_repositório_remoto>``` — Adiciona um repositório remoto chamado '*origin*'<br>
```git push -u origin <nome_da_ramificação>``` — Envia os *commits* locais para o repositório remoto<br>
```git pull origin <nome_da_ramificação>``` — Atualiza seu repositório local com as alterações do repositório remoto

## Histórico
```git log``` — Mostra o histórico de *commits*<br>
```git diff``` — Mostra as diferenças entre o que está no diretório de trabalho e o índice
