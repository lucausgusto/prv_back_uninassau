## Perguntas (Git e GitHub - básico)

1. Qual a diferença entre `git init` e `git clone`?

git init inicializa um repositório do zero na pasta atual. git clone copia um repositório já existente, remoto ou local, incluindo todo o histórico de commits.

2. O que faz o comando `git status`?

git status mostra o estado atual da área de trabalho: arquivos modificados, arquivos prontos para commit e arquivos não rastreados.

3. Para que serve o `git add` antes do `git commit`?

o git add coloca as alterações nessa área. Só o que está pronto para commit vai para o commit, isso permite escolher exatamente o que salvar.

4. Qual a diferença entre `git pull` e `git fetch`?

git fetch baixa as atualizações do remoto mas não altera seu branch local. git pull é equivalente a git fetch + git merge: baixa e já integra as mudanças.

5. O que é um branch e por que ele é usado?

um branch é uma ramificação do histórico de commits. Permite desenvolver funcionalidades, corrigir bugs ou fazer experimentos de forma isolada, sem interferir no branch principal até estar pronto.

6. O que é um Pull Request no GitHub?

pull request é uma solicitação de integrar mudanças de um branch em outro. 

7. Explique a diferença entre branch de origem e branch de destino em um PR.

o branch de origem contém as mudanças que você quer integrar. O branch de destino é o que vai receber o merge, geralmente main ou develop.

8. O que acontece se duas pessoas alterarem a mesma linha de um arquivo em branches diferentes?

ocorre um conflito de merge, o git sinaliza e é preciso ser resolvido manualmente.

9. Para que serve o arquivo `.gitignore`?

o .gitignore serve para especificar arquivos e pastas que o Git deve ignorar, como: node_modules, .env e arquivos de build.


10. Qual é a função do `README.md` em um projeto?

Documento principal do projeto: descreve o que é, como instalar, como usar e como contribuir.



