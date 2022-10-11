# Especificações do Projeto

Os problemas que iremos tratar com o presente projeto são de constatações pessoais de membros do grupo, que passaram pelas situações abordadas, e também em apurações feitas com pessoas que estão à procura de um meio de acesso ao ensino superior gratuito, são elas pessoas próximas ou conhecidas via rede social ou sites relacionados ao assunto do projeto. Os pontos específicos que serão levantados serão apresentados na forma de personas e histórias de usuários.

## Personas
`GUSTAVO`

Idade: 17 anos.

Profissão: Estudante.

Formação: Concluindo o ensino médio.

Escola pública: Sim.

Perfil: Gosta de tecnologia, games e afins. Deseja entrar no mercado de trabalho para poder ingressar em um curso superior de seu interesse, com preferência para cursos EAD, devido a flexibilidade de horários. 

Motivações:Achar meios para conseguir fazer uma graduação.

Dificuldades:Renda para custear estudos e demais necessidades e Distância das faculdades mais próximas.

Expectativa:Conhecer as formas de acesso ao ensino superior de forma gratuita ou financiada e conseguir informações que ajudem em sua decisão.


`MARIA`

Idade: 32 anos

Profissão: Empregada doméstica

Formação: Concluiu o ensino médio pelo EJA

Escola pública: Sim

Perfil: Mãe de dois filhos, casada e trabalha para compor a renda familiar. Terminou o ensino médio tardiamente, e só então soube que é possível fazer uma graduação de forma gratuita. Sonha em trabalhar na área da saúde.

Motivações: Fazer uma graduação,dar um futuro melhor para os filhos, trabalhar em algo que gosta.

Dificuldades: Informações claras a respeito dos programas federais de acesso ao ensino superior gratuito, conciliar trabalho, estudo e família.

Expectativa: Ingressar em uma faculdade. Conseguir informações mais detalhadas e concisas sobre os programas. 

## Histórias de Usuários

Com base nas informações coletadas com as personas do projeto, as seguintes histórias de usuários foram identificadas e expostas a seguir.

|EU COMO...          | QUERO/PRECISO ...                  |PARA ...                                |
|--------------------|------------------------------------|----------------------------------------|
|Estudante de escola pública.|Informações sobre os programas federais de acesso ao ensino superior gratuito.|Escolher qual a melhor opção dentre os programas e cursos oferecidos.              |
|Estudante de escola particular.|Conhecer o SISU de forma detalhada e as Universidades públicas que aderem a ele.|Para avaliar minhas chances para o curso que desejo, fazendo uma comparação com os vestibulares tradicionais.| 
|Professor.|Conhecer com detalhes os programas SISU e ProUni bem como o ENEM.|Orientar os alunos do ensino médio sobre tais programas e direcionar os estudos para que eles consigam bom desempenho no ENEM.|                   
|Pai de aluno.|Entender os programas e o grau de dificuldade de cada um.|Ajudar o filho a conseguir o acesso a uma faculdade de forma gratuita.|
|Estudante de escola pública, elegível as cotas PPI.|Analisar quais são as cotas, onde se aplicam e questões relativas notas de corte.|Para fazer uma escolha mais vantajosa, e poder ingressar em uma Universidade mais conceituada.|                   
|Egresso da escola pública formado a 10 anos.|Entender melhor os programas, e se pessoas em sua condição podem participar.|Ingressar em uma graduação para poder melhorar a condição de vida.|
|Cidadão que deseja concluir o ensino médio e ingressar em uma faculdade.|Conhecer o EJA, ENEM.|Concluir o ensino médio e posteriormente uma graduação. |           

## Requisitos

Os requisitos do projeto e suas funcionalidades são de caráter funcional e não funcional. Sendo os requisitos funcionais os meios de interação com o usuário, que poderá enviar dúvidas, dar sugestões e compartilhar conhecimento. Já os não funcionais são relativos aos aspectos gerais da página e sua principal função, que é a de informar.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-01 | O site deve ter a opção de filtros e pesquisa para que o usuário consiga achar mais facilmente o conteúdo desejado.| ALTA | 
|RF-02 | O site deve ter o serviço de envio de dúvidas e sugestões sobre os conteúdos.| MÉDIA |
|RF-03 | O site deve conter links que direcionem o usuário para a fonte da informação quando for necessário.|	Baixa |
|RF-04 | O site deve permitir que os usuários comentem sobre os conteúdos.	Baixa
|RF-05 |	O site deve possuir o campo de cadastro de usuário para que o mesmo possa interagir e receber avisos de atualizações.|	Média |
|RF-06 |	O site deve conter informações de contato do mantenedor. 	
|RF-07 |	O site deve permitir a visualização dos comentários feitos por outros usuários.|	Média |
|RF-08 |	O site deve ter um sistema que, mediante informações fornecidas pelo usuário, indique quais as suas melhores opções e chances em relação ao programas em questão.	
|RF-09 |	O site deve permitir o compartilhamento em redes sociais.|	Baixa |



### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 
|||

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
