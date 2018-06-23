## Repositories for Adaptive Curriculum Sequencing experiments

In this root directory you find:
- Folders represent Learning Objects Repositories where the name indicates the number of learning objects present in each repository.
- concepts.csv which represents all concepts covered by a course. For the purpose of the experiments only identifiers were used , separated by semicolons.
- learner.csv which represents all learners who must receive the adaptation from the Adaptive Curriculum Sequencing. The parameters used are respectively: 
Registration Code (ID);Lower Time expected(hour); Upper Time expected(hour); Active/Reflexive score of FSLSM; Sensorial/Intuitive score of FSLSM; Visual/Verbal score of FSLSM; Sequencial/Global score of FSLSM; All concepts learner needs to learn (learning goals) separated by semicolons
- learners_score.csv which represents all the learners' scores for each course concept. This is calculated by assessment tests. The file representation is:
Registration Code (ID);Concept identification;learner score [1..5]\n

Inside each folder there is another folder containing metadata files in IEEE-LOM Standard, only the important tags for the experiments were populated on these files. Also there is a learningResource-Concepts.csv file which represents
the link of learning objects and the concepts its cover. The file representation is:
Learning Object identificatio; concepts its cover separated by semicolons\n


## Repositórios para experimentos de Sequenciamento Curricular Adaptativo

Neste diretório raiz você encontra:
- As pastas representam Repositórios de Objetos de Aprendizagem, onde o nome indica o número de objetos de aprendizagem presentes em cada repositório.
- concepts.csv, que representa todos os conceitos cobertos por um curso. Para o propósito das experiências, apenas identificadores foram usados, separados por ponto e vírgula.
- learner.csv, que representa todos os alunos que devem receber a adaptação do Seqüenciamento Adaptativo Curricular. Os parâmetros utilizados são respectivamente:
Matrícula (ID); Tempo Inferior Esperado (hora); Tempo Superior esperado (hora); Pontuação para dimensão ativa/reflexiva do FSLSM;
Pontuação para dimensão sensorial/intuitiva de FSLSM; Pontuação para dimensão Visual/Verbal do FSLSM; Pontuação para dimensão Sequencial/Global do FSLSM;
Todos os conceitos que o aluno precisa aprender (objetivos de aprendizagem) separados por ponto e vírgula
- learners_score.csv, que representa todas as pontuações dos alunos para cada conceito de curso. Isso é calculado por testes de avaliação. A representação do arquivo é:
Matrícula (ID), identificador do conceito, pontuação do aluno [1..5] \n

Dentro de cada pasta há outra pasta contendo arquivos de metadados no padrão IEEE-LOM, apenas as tags importantes para as experiências foram preenchidas nesses arquivos. Também há um arquivo learningResource-Concepts.csv que representa
o elo de objetos de aprendizagem e os conceitos de sua capa. A representação do arquivo é:
Identificador do Objeto de Aprendizagem; conceitos sua capa separada por ponto e vírgula \n
