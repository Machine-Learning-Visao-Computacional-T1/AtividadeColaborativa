# 🚀 Desafio Colaborativo:

Bem-vindos ao nosso primeiro desafio de integração contínua! 
Nesta atividade, a turma inteira vai trabalhar **no mesmo arquivo Python**. Nosso objetivo é transformar uma base de dados bruta em um painel analítico rico, juntando o código de todo mundo!

## 🎯 A Sua Missão
Cada aluno deve deixar a sua marca no arquivo `pipeline_turma.py`. Você tem duas tarefas obrigatórias:
1. **Engenharia de Dados:** Criar **UMA** nova coluna no DataFrame base usando o que aprendemos (ex: `np.where`, `np.select`, ou `.apply()`).
2. **Visualização:** Criar **UM** gráfico (Matplotlib ou Seaborn) que explique algum *insight* sobre os dados (pode ser histograma, barras, dispersão, etc.).

## 🛠️ Passo a Passo (Git Flow)
Siga a receita de bolo para não quebrar o código dos colegas:

1. Clone este repositório para a sua máquina:
   `git clone [URL_DO_REPOSITORIO]`
2. Crie a sua própria Branch (troque para o seu nome):
   `git checkout -b feature/nome-sobrenome`
3. Abra o arquivo `pipeline_turma.py` no VS Code.
4. Vá até o final do arquivo e adicione o seu código **exatamente abaixo** da indicação comentada.
5. Salve e envie para o GitHub:
   `git add .`
   `git commit -m "feat: adiciona analise do [Seu Nome]"`
   `git push origin feature/nome-sobrenome`
6. Vá no GitHub e abra o seu **Pull Request** para a `main`.

## 💥 ALERTA VERMELHO: O Conflito de Merge!
Como todos estão alterando o mesmo arquivo, o GitHub vai bloquear o PR de quase todo mundo acusando **Merge Conflict**! Não entre em pânico, isso é o dia a dia de um Dev.

**Como resolver se o seu PR ficar bloqueado:**
1. No seu terminal, puxe as atualizações mais recentes que o professor já aprovou:
   `git checkout main`
   `git pull origin main`
2. Volte para a sua branch:
   `git checkout feature/nome-sobrenome`
3. Tente fundir as novidades na sua branch:
   `git merge main`
4. Seu VS Code vai ficar vermelho! Localize o conflito e clique no botão mágico **"Accept Both Changes"** (Aceitar ambas as alterações) para que o seu gráfico e o do seu colega fiquem juntos.
5. Salve, faça um novo `commit` e dê `push`. O GitHub vai liberar seu PR automaticamente!
