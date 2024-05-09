# Análise Exploratória de Dados com Planilhas

Dados usados: [Student Performance](https://archive.ics.uci.edu/dataset/320/student+performance)

### Descrição

Estes dados abordam o desempenho dos alunos no ensino secundário de duas escolas portuguesas. Os atributos dos dados incluem notas dos alunos, características demográficas, sociais e relacionadas com a escola e foram recolhidos através de relatórios escolares e questionários. São fornecidos dois conjuntos de dados relativos ao desempenho em duas disciplinas distintas: Matemática (mat) e Língua Portuguesa (por). 

### Variáveis

# Atributos para os conjuntos de dados student-mat.csv (curso de matemática) e student-por.csv (curso de língua portuguesa):
1. **school** - escola do aluno (binário: 'GP' - Gabriel Pereira ou 'MS' - Mousinho da Silveira)
2. **sex** - sexo do aluno (binário: 'F' - feminino ou 'M' - masculino)
3. **age** - idade do aluno (numérico: de 15 a 22)
4. **address** – tipo de endereço residencial do aluno (binário: ‘U’ – urbano ou ‘R’ – rural)
5. **famsize** - tamanho da família (binário: 'LE3' - menor ou igual a 3 ou 'GT3' - maior que 3)
6. **Pstatus** - situação de coabitação dos pais (binário: 'T' - morando juntos ou 'A' - separados)
7. **Medu** - escolaridade da mãe (numérico: 0 - nenhuma, 1 - ensino fundamental (4º ano), 2 - 5º ao 9º ano, 3 - ensino médio ou 4 - ensino superior)
8. **Fedu** - escolaridade do pai (numérico: 0 - nenhuma, 1 - ensino fundamental (4º ano), 2 - 5º ao 9º ano, 3 - ensino médio ou 4 - ensino superior)
9. **Mjob** - trabalho da mãe (nominal: 'professor', 'cuidados de saúde', 'serviços' civis (por exemplo, administrativo ou policial), 'em_casa' ou 'outros')
10. **Fjob** - trabalho do pai (nominal: 'professor', 'cuidados de saúde', 'serviços' civis (por exemplo, administrativo ou policial), 'em_casa' ou 'outros')
11. **reason** - motivo para escolher esta escola (nominal: perto de ‘casa’, ‘reputação’ da escola, preferência de ‘curso’ ou ‘outro’)
12. **guardian** - tutor do aluno (nominal: 'mãe', 'pai' ou 'outro')
13. **traveltime** - tempo de viagem da casa até a escola (numérico: 1 - <15 min., 2 - 15 a 30 min., 3 - 30 min. a 1 hora, ou 4 - >1 hora)
14. **studytime** - tempo de estudo semanal (numérico: 1 - <2 horas, 2 - 2 a 5 horas, 3 - 5 a 10 horas ou 4 - >10 horas)
15. **failures** - número de falhas de classe anteriores (numérico: n se 1<=n<3, caso contrário 4)
16. **schoolup** - apoio educativo extra (binário: sim ou não)
17. **famsup** – apoio educacional familiar (binário: sim ou não)
18. **paid** - aulas extras pagas dentro da disciplina do curso (Matemática ou Português) (binário: sim ou não)
19. **activities** - atividades extracurriculares (binário: sim ou não)
20. **nursery** - frequentou a creche (binário: sim ou não)
21. **higher** - quer cursar ensino superior (binário: sim ou não)
22. **internet** - Acesso à internet em casa (binário: sim ou não)
23. **romantic** - com relacionamento amoroso (binário: sim ou não)
24. **famrel** - qualidade das relações familiares (numérico: de 1 - péssimo a 5 - excelente)
25. **freetime** - tempo livre depois da escola (numérico: de 1 - muito baixo a 5 - muito alto)
26. **goout** - sair com amigos (numérico: de 1 - muito baixo a 5 - muito alto)
27. **Dalc** - consumo de álcool durante a jornada de trabalho (numérico: de 1 - muito baixo a 5 - muito alto)
28. **Walc** - consumo de álcool no final de semana (numérico: de 1 - muito baixo a 5 - muito alto)
29. **health** – estado de saúde atual (numérico: de 1 – muito ruim a 5 – muito bom)
30. **absences** - número de faltas escolares (numérico: de 0 a 93)
# essas notas estão relacionadas com a disciplina do curso, Matemática ou Português:
31. **G1** - nota do primeiro período (numérico: de 0 a 20)
32. **G2** - nota do segundo período (numérico: de 0 a 20)
33. **G3** - nota final (numérico: de 0 a 20, meta de saída)
