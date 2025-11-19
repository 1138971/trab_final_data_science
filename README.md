# *-----------------trab_final_data_science--------------------*

Nome: **Júlio Vinicius Tasca Mendes** 
RA: **1138971**

O dataset escolhido foi: **Escolha do curso de CC - 2025.1**

A coluna escolhida para ser tratada foi: **Por quais motivos você escolheu cursar CC?**

 
**Motivos pela escolha da coluna:**

   - é uma coluna aberta, com resposta livre, sendo assim, surgiram respostas inconsistentes, com variações de escrita, sinônimos, entre outros problemas;
   - como a pergunta é ampla, é necessário transformar respostas livres em categorias analisáveis, como: Interesse pessoal, Influência familiar/amigos, Mercado de trabalho;
   - textos livres contêm erros de escrita(ruídos).

  
Além do tratamento da coluna escolhida, foi criada uma nova coluna chamada "chance_desistencia", e essa nova coluna:
   - analisa a coluna "Por quais motivos você escolheu cursar CC?";
   - verifica se existe um(a) aluno(a) que teve influência familiar na hora da decisão de escolher o curso;
   - pressão familiar PODE SER um dos fatores que leva o(a) aluno(a) à desistência.
     
  
**Lógica do dicionário substituições:**
   - realiza a tradução de textos;
   - ela lê uma coluna, identifica certos motivos escritos de várias maneiras e substitui cada um deles por uma categoria padronizada.
     
**Lógica da função verifica_influencia_familia:**
   - ela verifica se a palavra “familiares” aparece em cada resposta da coluna e, com base nisso, devolve True ou False.

**Lógica da função chance_desistencia:**
   - ela verifica se o valor recebido é **True** ou **False** e devolve se é "Mais provável" ou "Menos provável" o(a) aluno(a) desistir do curso, com base se a decisão do aluno, de igressar no curso, teve influência ou pressão familiar.

**Justificativa da transformação:**
   - padronizar os dados de uma coluna em um arquivo CSV é fundamental para garantir qualidade, consistência e confiabilidade em um projeto de pesquisa;
   - facilita a análise estatística e computacional;
   - reduz erros e ruído nos dados;
   - permite integração com outros conjuntos de dados.

**Impacto prático:**
   - comparar informações, quantos alunos que desistiram tinha a opção Influência de terceiros como True;
   - caso essa comparção tenha um resultado satisfatório, esse ponto se tornaria de interesse para a instuição;
   - à partir disso, um estudo seria feito e cima desses dados para reduzir esse número de desistentes.
