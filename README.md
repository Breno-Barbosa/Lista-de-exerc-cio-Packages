Este repositório contém o script SQL com pacotes desenvolvidos para uma base de dados acadêmica.  

## Descrição dos Pacotes

### PKG_ALUNO
- **Objetivo**: Gerenciar informações relacionadas aos alunos.
- **Principais funcionalidades**:
  - `excluir_aluno`: Exclui um aluno e suas matrículas.
  - `c_alunos_mais_18`: Cursor que lista alunos maiores de 18 anos.
  - `c_alunos_por_curso`: Cursor que lista alunos de um curso específico.

### PKG_DISCIPLINA
- **Objetivo**: Gerenciar informações de disciplinas.
- **Principais funcionalidades**:
  - `cadastrar_disciplina`: Adiciona uma nova disciplina à base de dados.
  - `c_total_alunos_disciplina`: Cursor que lista disciplinas com mais de 10 alunos.
  - `listar_alunos_disciplina`: Lista os alunos de uma disciplina específica.

### PKG_PROFESSOR
- **Objetivo**: Gerenciar informações dos professores.
- **Principais funcionalidades**:
  - `turmas_por_professor`: Retorna o total de turmas de um professor.
  - `professor_por_disciplina`: Retorna o nome do professor responsável por uma disciplina.

## Como Executar

1. Certifique-se de que você tem o Oracle SQL*Plus ou um cliente equivalente instalado.
2. Abra o terminal ou ferramenta de execução SQL.
3. Execute o script com o comando:
   ```sql
   @script.sql
