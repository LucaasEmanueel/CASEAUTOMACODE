# CASEAUTOMACODE
Lucas Emanuel Santos da Silva – Quality Assurance
Telefone: (83) 991206898
E-mail: lucas.emanuel@dcx.ufpb.br
LinkedIn: https://www.linkedin.com/in/lucas-emanuel/


Case construída com a finalidade de organizar com qualidade todo o processo organizacional e de desenvolvimento do software. 
Com isso, tendo em vista as adversidades e os problemas consistentes que a empresa (fictícia) vive, temos algumas soluções a serem aplicadas desde o princípio da sua cultura até a construção e entrega do produto final. No qual, o processo em conjunto com os bons hábitos deverá ser feito para a qualidade no momento de entrega ao cliente. 

1. PROBLEMAS QUE ESTÃO CAUSANDO IMPACTO NA QUALIDADE DO PRODUTO

o	Impasses com a metodologia de trabalho; 
o	Número de BUG’s aumentando de forma brusca; 
o	Problemas com retestes; 
o	Não tem geração de massa de dados; 
o	Retrabalho devido as alterações de pacotes; 
o	Não tem pessoas qualificadas para automatizar testes; 
o	Informações estão descentralizadas; 
o	Conflito entre QA’s e DEV’s; 
o	Baixa cobertura de testes; 
o	Entrega lentas. 

2. POSSIVEIS SOLUÇÕES PARA A EMPRESA

2.1 Metodologia Ágil 
  
Nessa etapa precisamos de uma mudança de cultura gradativa, pois sabemos que não é fácil mudar todo uma metodologia de trabalho radicalmente, levando em consideração que os trabalhos da empresa não podem parar. Com esses aspectos, resolvemos implantar o SCRUM. 
  
Problema: Falta de uma metodologia que gerencia melhor as etapas de desenvolvimento até a entrega do produto final.  
Solução: Implantar a metodologia SCRUM para receber feedback rápido do cliente evitando possíveis problemas no entendimento do negócio e consequentemente economizando financeiramente no produto final. Essa métrica ajuda a mostrar ao time resultados semanais ao longo de cada fim da script, deixando claro a todos a evolução e o progresso. Tem como principais característica entregar pequenas partes do projeto e aumentar a produtividade e o trabalho em equipe. 
  
Como fazer/implantar? 
Implantar de maneira gradativa começando com dois passos característicos dessa metodologia: 

1.	Lista priorizada: codificar/desenvolver o sistema com uma lista de funcionalidades com prioridades; 
2.	Entregas requentes: Acostumar os times a desenvolver com um prazo de entrega mais curto com pequenas funcionalidades a serem desenvolvidas. 
  
A partir de então podemos fazer reuniões de formação e juntar equipes no qual cada time será composto por dev’s e qa’s e começar a trabalhar em conjunto, estreitando a relação deixando desenvolvedores e pessoas da qualidade mais próximas. E para finalizar a Squad, se faz necessário um Líder no qual busca deixar claro que a responsabilidade da qualidade é de todos, tratando alguns pontos interpessoais e assunto “humano” de comportamento, e um dono do negócio (PO) que faz a ligação cliente e empresa. 
  
Benefícios pós implantação: Ambiente colaborativo, entregas rápidas, qualidade na entrega, comunicação entre negócios e desenvolvimento. 

2.2 Divisões de ambientes

Problema: Ambientes Indisponíveis. 
Solução: Dividir em ambiente de desenvolvimento, integrado e Produção. Em apenas três, pois quanto menos ambiente teremos, menos problemas para lidar relacionados a ambientes. Aumentando consequentemente o risco de ter um bug em produção, mas forçando o desenvolvimento a ter uma excelente cobertura de testes nas diferentes camadas. 
  
Como fazer/implantar? 
Devemos ter uma infraestrutura que deixe esses ambientes prontos e conscientizar cada processo da aplicação no seu devido ambiente, separando sistematicamente cada etapa de atualização do software. 
  
Benefícios pós implantação: Organização no ciclo de desenvolvimento, ambientes separados contendo cada etapa em seu devido lugar. 

2.3 Testes automatizados

Problema: Esforço excessivo em testes manuais 
Solução: Implantar testes automatizados nos pontos mais críticos que colocam em risco o sistema e dando mais segurança nos ambientes que já foram retestados, tendo como base a pirâmide de testes. 
  
Como fazer/implantar? 
Antes da formação de automação de software, e sabendo da importância da fundamentação da qualidade de software, devemos primeiro ensinar métricas e técnicas de testes de softwares nos diferentes contextos.  
Alguns métricas de testes baseadas em riscos, baseadas em requisitos, baseada em históricos de falhas e baseado em testes exploratórios. 
  
Exemplo de técnicas e métricas que devem ser abordados pelos QA’s: 
- Partição de Equivalência; 
- Analise valor limite; 
- Tabelas de decisão, 
- Heurísticas de testes exploratórios. 
  
Em seguida, após ter uma formação com essa base de como testar por meio de técnicas e métricas, devemos promover cursos de automação para os colaboradores (dev’s e QA’s) nas três camadas e deixar claro que testes automatizados é responsabilidade de todo. 
  
Outro ponto importante que deve ser frisado é a responsabilidade dos dev’s com testes unitários, 
tornando uma cultura na empresa. Cada desenvolvedor escreve um teste automatizado em pelo menos uma estória de usuário. 
Exemplo: Se tiver 5 dev’s, para essa estória de usuários vão ter 5 testes automatizados. E se tiver 3 estórias vai ter ao menos 15 testes automatizados por sprint’s. Com esse habito conseguimos dar mais segurando ao processo de desenvolvimento aumentando consequentemente a qualidade do software e a cobertura dos testes.  
Com essa implantação testes vão ficar mais seguros evitando mais bug’s e consequentemente dando mais segurança aplicação, diminuindo a possibilidade de retestes serem quebrados. 
  
  
Benefícios pós implantação: Scripts de testes automatizados, código mais seguro e menores riscos de BUG’s em produção. 
  
OBS: Automatização está sendo implantada para dar mais confiabilidade e segurança no desenvolvimento. 

2.4 Gerador de massa de dados

Motivo: Falta de massa para os testes 
Solução: Automatizar a criação de massa de dados por meio de técnicas e estratégias, gerando dados fictícios. Exemplo, utilizando o FAKER que é um modulo do node podemos criar uma grande massa de dados que parecem reais. 
  
Como fazer/implantar? 
Instalando o modulo “yarn add faker” os colaboradores conseguem utilizar e gerar massa por algoritmo conforme o contexto do seus testes. Um treinamento deve ser feito para os colabores aprender a usar esse método de geração de massa. 
  
Benefícios pós implantação: Consumir dados do mesmo local; padronizar os dados utilizados para uma finalidade, evitando erros; qualquer alteração na massa, um único local do código sofrerá alteração. 

2.5 DevOPS – Integração contínua

Motivo: Não tem um fluxo de deploy Continuo 
Solução: Implantar uma pipeline para dar confiabilidade no momento da alteração do desenvolvimento. Contratando um colaborador (DevOPS) que trabalhe e implante essa cultura de entregas continuas. 
  
Como fazer/implantar? 
- Começar identificando tarefas repetitivas no processo de desenvolvimento; 
- Quando esses pontos são identificados, começar a etapa de automatizar o processo; 
- Trabalhar com uma pipeline de deploy para entrega continua do processo; 
  
Outro ponto importante nesse processo é decidir uma ferramenta de gerenciamento de configuração e utilizar o GitLab como uma ferramenta para a esteira de devOP’s. 
Com isso, de maneira gradativa em processos ou produtos menores podemos começar a implantar essa cultura, para sentir o impacto dessa mudança e aos poucos ir abrangendo em partes maiores da empresa.  
  
Benefícios pós implantação: Segurança na alteração de alguma funcionalidade; automação de tarefas; redução de tempo; produções mais ágeis e ambiente colaborativo entre equipe. 

2.6 Ferramenta de gestão de caso de teste

Problema: Descentralização dos testes 
Solução: EasyQA. Ferramenta que cria planos e casos de testes, reporta resultados e rastreia bugs. 
Como fazer/implantar? 
Apresentar a ferramenta em uma reunião mostrando suas funcionalidades, expondo a importância de ter testes concentrados em uma plataforma para facilitar o histórico e relatório de todos os testes e inconsistências do processo ensinando a todos como utiliza-la. Os testes dessa forma ficam concentrados e ajuda nesse gerenciamento centralizado em uma única ferramenta. 
  
Benefícios pós implantação: Histórico de caso de testes e bug’s organizados, ganho de tempo e centralização dos casos de testes, podendo buscar ou gerar relatórios de forma mais prática. 

2.7 Cobertura de testes em diferentes camadas

Problema: Cobertura de testes em 15% 
Solução: Testes em diferentes camadas tais como: Testes unitários, testes de integração e testes de UI. 
  
Como fazer/implantar? 
Iniciamos cobrando dos desenvolvedores scripts de teste unitários (60%) que cubram todo seu desenvolvimento, passando assim a virar uma cultura de quem desenvolve na empresa, levando em consideração que esses testes são mais baratos e mais rápidos. 
Já os testes de integração devem ocupar a segunda maior parte (30%) dos testes a serem feitos no sistema/aplicação. Pois o mesmo tem um custo mais baixo e menos esforço que a camada Web (E2E).  
Com isso, deixando a camada mais alta da pirâmide (interface gráfica) com 10% dos seus testes já que ela é uma camada que tem um custo mais alto e um esforço maior. 
  
Benefícios pós implantação: Gera mais organização nos códigos, mais segurança e eficiência na qualidade do processo de entrega do software. 


2.8 Testes de Performance

Problema: Sistemas muitos lentos 
Solução: Utilizar uma ferramenta chamada Jmeter para medir o comportamento da aplicação e verificar quais as possíveis causas para só então fazer melhorias. 
  
Como fazer/implantar? 
               Antes de ver o conteúdo da ferramenta, devemos ter um planejamento do que deve ser analisado, tais como: 
               - Analisar em que momento tem o pico mais alto de acessos simultâneos ao sistema (Pega a informação e armazena), com essa informação sabemos com quantos usuários podemos projetar os testes; 
               - Quais são os fluxos que os usuários utilizam, para saber o que percorrer no momento dos testes; 
               - O que você quer descobrir? Saber se a infraestrutura suporta os usuários? Saber o número máximo de usuários que ela suporta? 
  
OBS: essas informações podem ser informadas pelo Google Analytics. 
                
A partir desses pontos utilizamos o Jmeter para simular essas situações a fim de saber se precisamos de mais maquinas ou mais redes e etc. 
  
Benefícios pós implantação: Gargalhar os pontos que tornam o sistema mais lento, aumentando consequentemente a possibilidade solução para melhoria da aplicação em geral. 


2.9 Ambientes Virtualizados

Problema: Sistemas lentos, gerando dores de cabeça para a diretoria. 
Solução: Maquinas virtuais são uma solução para esse ponto especifico do problema. 
  
Como fazer/implantar? 
Por meio de um curso de capacitação no qual deverá ser abordado os fundamentos, soluções e importância desses ambientes virtualizados. Mostrando o quanto esses ambientes são importantes para testes, economia de infraestrutura e gerenciamento centralizado. 
  
Benefícios pós implantação: Melhor desempenho e disponibilidade, redução de custos, flexibilidade, agilidade, escalabilidade, segurança, otimização do hardware 
  
  
Resumo das soluções que devem ser aplicadas no processo de qualidade da empresa: 
•	Metodologia Ágil 
•	Divisões de ambientes 
•	Testes automatizados 
•	Gerador de massa de dados 
•	DevOPS – Integração contínua 
•	Ferramenta de gestão de caso de teste 
•	Cobertura de testes em diferentes camadas 
•	Testes de Performance 
•	Ambientes Virtualizados 
  
Possíveis dificuldades: 
  
•	Cultura enraizada; 
•	Metodologias ultrapassadas; 
•	Diversidade de pessoas; 
•	Comunicação e diferentes entendimentos; 
•	Convencer as pessoas a acreditar nas novas métricas de qualidade; 
•	Aplicações em desenvolvimento. 
