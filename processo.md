flowchart TD
  A[Aluno faz inscrição no ENEM] -->|Aprovado| B[Entrega documentos para matrícula]
  A -->|Reprovado| X[Eliminado do fluxo]
  
  B --> C[Documentos são analisados]
  C -->|Aprovados| D[Matrícula é realizada]
  C -->|Reprovados| X
  
  D --> E[Coordenador realiza matrícula em matérias do primeiro período]
  E --> F[Aluno inicia as aulas]
