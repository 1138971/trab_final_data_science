# **trab_final_data_science**

Nome: Júlio Vinicius Tasca Mendes     =================    RA: 1138971

O dataset escolhido foi: **Escolha do curso de CC - 2025.1**

A coluna escolhida para ser tratada foi: **Por quais motivos você escolheu cursar CC?**

 
Motivos pela escolha da coluna:

   - é uma coluna aberta, com resposta livre, sendo assim, surgiram respostas inconsistentes, com variações de escrita, sinônimos, entre outros problemas;
   - como a pergunta é ampla, é necessário transformar respostas livres em categorias analisáveis, como: Interesse pessoal, Influência familiar/amigos, Mercado de trabalho;
   - textos livres contêm erros de escrita(ruídos);

  
 Além do tratamento da coluna escolhida, foi criada uma nova coluna chamada "chance_desistencia", e essa nova coluna:
   - analisa a coluna "Por quais motivos você escolheu cursar CC?";
   - verifica se existe um(a) aluno(a) que teve influência familiar na hora da decisão de escolher o curso;
   - pressão familiar PODE SER um dos fatores que leva o(a) aluno(a) à desistência;
     
  
 
