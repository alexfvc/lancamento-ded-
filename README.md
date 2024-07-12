Lançamento ded+
Repositório para lançamento automático de dados de aulas lecionadas no diário escolar digital do estado de Minas Gerais.

https://dedmais.educacao.mg.gov.br/

Diário escolar usado por professores para lançamento de aulas lecionadas e notas de alunos da rede estadual de ensino de Minas Gerais, aulas e conteúdos pela Secretaria de Estado de Educação do Estado de Minas Gerais.

O bot transforma o diário escolar digital, que atualmente é formado por vários formulários, um para cada dia de aula, em uma planilha de Excel. É extremamente mais fácil lançar os dados necessários em uma planilha do que em um formulário.

A parte feita inicialmente foi o lançamento de aulas. FEITO

Nas próximas etapas do projeto, a automação lançará as notas e, em seguida, tentarei automatizar o lançamento de faltas dos alunos.
Etapa 1: lançamento de aulas.
Etapa 2: lançamento de atividades avaliativas.
Etapa 3: lançamento de faltas.

Com a conclusão da Etapa 1, o professor já terá em mãos o diário com todas as aulas lançadas.

Atualizar a planilha planejamento.xlsx:
A planilha deve ter os dados na mesma forma que é esperada pelo diário.
 
  Exemplo: 

    ____________________________________________________________________________________________________________________________________
    |EtapadaMatrícula   | Turma              | Disciplina  | turno    | escola     | Bimestre     | Data          | Conteúdo Lecionado |
    |2°ano              | 2° EM REG (2024)   | FÍSICA      | Manhã    | esoola X   | 2º BIMESTRE  | 25/05/2024    | física térmica     |
    |3°ano              | 2° EM REG (2024)   | FÍSICA      | Noite    | escola Y   | 2º BIMESTRE  | 26/06/2024    | física elétrica    |
     ___________________________________________________________________________________________________________________________________


No exemplo acima, seria lançada uma aula no segundo bimestre, dia 25/05/2024, para a turma 2º REG 1, com conteúdo de física térmica e tambem
seria lançada uma aula no segundo bimestre, dia 26/06/2024, para a turma 3º REG 4, com conteúdo de física elétrica.

Rodar o código:
Ao rodar o código, abrirá uma página do navegador no site do diário.
Você deve colocar seu login, senha e captcha.
Não clique em entrar, volte ao código e responda à pergunta com apenas um "s".
O bot escreverá a seguinte frase:
"Digite 's' ao terminar: "

lembre-se que serão usadas as informações que foram colocadas na planilha "planejamento.xlsx" na aba preencher.


Ao final, aparecerá a mensagem: FEITO!!!
                                                                                     
feito apenas a etapa 1

                                               Alex Furtado Vilela Costa
    
    
    
