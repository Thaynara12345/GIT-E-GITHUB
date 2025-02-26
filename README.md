# GIT-E-GITHUB
Funções do Git

O Git é um sistema de controle de versão distribuído, que permite rastrear mudanças no código-fonte ao longo do tempo. As principais funções do Git incluem:

Controle de versão local: O Git permite que você tenha um repositório completo no seu computador (local), o que significa que você pode trabalhar e fazer commits sem precisar de uma conexão com a internet.

Commit: O comando git commit registra mudanças no repositório local. Ele permite que você salve versões específicas de seu código.

Branching (Ramos): Git permite criar ramificações (branches) do seu código, o que facilita o desenvolvimento de novas funcionalidades ou correção de bugs sem afetar a versão principal do projeto (normalmente chamada de main ou master).

Merge (Mesclagem): Depois de desenvolver uma nova funcionalidade ou corrigir um bug em um branch, o Git oferece a função de mesclar (merge) esse branch com o branch principal, incorporando as mudanças.

Clone: O comando git clone permite copiar um repositório inteiro para o seu computador, incluindo todos os arquivos e o histórico de commits.

Push e Pull: git push envia suas alterações locais para um repositório remoto (como o GitHub), enquanto git pull baixa e integra alterações feitas por outros colaboradores em um repositório remoto.

Staging Area: O Git permite que você controle quais alterações deseja incluir em um commit, usando a área de preparação (staging area) com o comando git add.

Revert e Reset: Git oferece ferramentas para reverter ou redefinir commits, permitindo que você desfaça ou modifique alterações de maneira controlada.

Comandos do Git

git init: Inicializa um novo repositório Git local.
git clone: Cria uma cópia local de um repositório remoto.
git status: Mostra o status atual do repositório, como arquivos modificados, prontos para commit ou não.
git add: Adiciona arquivos ou alterações ao "staging area" (área de preparação) para o próximo commit.
git commit: Registra as alterações adicionadas ao repositório local com uma mensagem de descrição.
git pull: Baixa as alterações de um repositório remoto e as mescla com o repositório local.
git push: Envia suas alterações locais para um repositório remoto.
git branch: Lista, cria ou exclui branches.
git checkout: Altera para um branch específico ou reverte alterações em arquivos.
git merge: Mescla as mudanças de um branch no branch atual.
git log: Exibe o histórico de commits do repositório.
git diff: Mostra as diferenças entre arquivos ou commits.
git reset: Remove um commit ou desfaz alterações locais.
git stash: Armazena temporariamente alterações não commitadas.

Funções do GitHub

O GitHub é uma plataforma de hospedagem de código-fonte baseada em Git. Além de servir como repositório remoto para o código, ele tem funcionalidades que facilitam a colaboração entre desenvolvedores. Algumas das principais funções do GitHub incluem:

Repositórios remotos: O GitHub armazena seus repositórios Git na nuvem, permitindo que você acesse seu código de qualquer lugar e compartilhe facilmente com outros.

Colaboração e Pull Requests: O GitHub facilita a colaboração por meio de pull requests. Quando você faz alterações em um repositório e deseja que outras pessoas revisem e integrem suas mudanças, você cria um pull request. Outros colaboradores podem revisar, comentar, e até sugerir alterações antes de aceitar o merge.

Issues (Problemas): O GitHub permite gerenciar issues, que são usadas para relatar bugs, sugerir melhorias ou pedir ajuda. É uma forma de organizar e priorizar o trabalho dentro de um projeto.

Ações e CI/CD (Integração Contínua/Entrega Contínua): GitHub Actions permite automatizar tarefas como testes de código, construção de software e deploy em servidores. Essa funcionalidade integra pipelines de CI/CD diretamente na plataforma.

Wiki e Documentação: O GitHub oferece um sistema de Wiki integrado para criar e manter documentação do projeto. Isso facilita a comunicação sobre como o código funciona ou como contribuições devem ser feitas.

GitHub Pages: Permite que você hospede sites estáticos diretamente a partir de um repositório GitHub. Isso é útil para documentações, blogs, ou sites de projetos open-source.

Segurança e Análise de Código: GitHub oferece ferramentas para revisar a segurança do código, como alertas para vulnerabilidades conhecidas e sugestões para melhorar a segurança do software.

Controle de versões e histórico: A plataforma oferece uma interface visual para examinar o histórico de commits, comparando diferentes versões de arquivos e revisões no código.

Comandos do GITHUB

gh auth login: Autentica você na sua conta do GitHub.
gh repo create: Cria um novo repositório no GitHub.
gh pr create: Cria um novo pull request.
gh pr checkout: Faz checkout de um pull request para revisão.
gh issue list: Lista as issues abertas no repositório.

PASSOS PARA POSTAR O SEU PROJETO NO GIT e GITHUB ONLINE:

nicializar o repositório Git: git init
Adicionar arquivos ao repositório: git add .
Fazer o commit das alterações: git commit -m "Mensagem do commit"
Criar um repositório no GitHub: Acesse GitHub, crie um repositório.
Adicionar o repositório remoto: git remote add origin https://github.com/usuario/repositorio.git
Enviar (push) os arquivos para o GitHub: git push -u origin master (ou main)
Verificar no GitHub: Acesse seu repositório para ver os arquivos online.





