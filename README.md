# Minicurso - Prática Dev on Real

Este é um projeto colaborativo onde cada integrante da equipe irá desenvolver um desafio específico,
identificado por um card

## Estrutura do Projeto

1. Cada integrante deve criar uma branch com seu próprio nome
2. As implementações devem ser feitas diretamente na sua branch pessoal
3. Após concluir o card designado, faça o commit e o push para sua branch
4. Por fim, faça um pull request (PR) para a branch `main` após completar todos os seus cards

## Passos para Contribuir

1. **Crie uma Branch com Seu Nome** (caso ainda não exista)

    - Renomeie a branch atual para o seu nome:
      ```bash
      git branch -M seu_nome
      git checkout seu_nome
      ```
    - **Ou crie uma branch órfã** (sem histórico) a partir da atual
      ```bash
      git checkout --orphan seu_nome
      ```

2. **Implemente o Card Designado e Faça o commit**
    - Resolva a tarefa conforme descrito no card
    - Teste seu código antes de fazer o commit

   ```bash
   git add .
   git commit -m "Descrição da implementação do card"
   ```

3. **Adicione o repositório como remote e faça o Push**
   ```bash
   git remote add origin https://github.com/Gustavo-Gadelha/Dev-on-Real.git
   git push -u origin seu_nome
   ```