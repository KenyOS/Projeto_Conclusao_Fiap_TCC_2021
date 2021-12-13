
Brave Blue

Arthur Gebara RM79150
Mateus Toledo RM78833
Keny Oshiro RM79975
Yan Alexandre RM77740








Projeto de Startup apresentado à disciplina Análise de Negócios e Inteligência Empresarial.
     








Faculdade de Informática e Administração Paulista - FIAP
São Paulo
Novembro - 2021


 
SUMÁRIO



1.	INTRODUÇÃO AO PROBLEMA	3
2.	JUSTIFICATIVA PARA SOLUÇÃO	4
3.	EQUIPE	5
4.	VALIDAÇÃO DO PROBLEMA	6
5.	MERCADO ALVO	13
6.	MODELO DE NEGÓCIO	15
7.	ANÁLISE DO MERCADO	17
8.	ANÁLISE FINANCEIRA E PROJEÇÃO DE CRESCIMENTO	19
9.	MVP - FUNCIONALIDADES ESSENCIAIS	20
10.   PROTÓTIPO FUNCIONAL.	21
11.   PLANO DE MARKETING	26
12.   TECH FOR GOOD	29
13.   REFERÊNCIAS	30
14.   APÊNDICE	31








 
1.	INTRODUÇÃO AO PROBLEMA
A tecnologia se faz mais presente a cada dia em nosso cotidiano, seja via nosso aparelho celular, relógios inteligentes e até eletrodomésticos interligados em nossas casas, visando cada vez mais automação e também uma busca por padrões para facilitar em nosso dia a dia, o que nos leva ao primeiro pilar de nosso problema, que seria a escalabilidade, já que com este aumento no número de sensores para coleta de informações, como sensores de vazão de gás, água, óleo, eletricidade, entre outros. Principalmente no setor industrial, os dados coletados por meio destes sensores são processados por meio de gráficos, com o objetivo de tomada de decisão, o que pode gerar problemas devido à alta complexidade nos dados coletados.
O segundo pilar seria a parte de integração, já que, cada tipo de sensor se utiliza de protocolos de comunicação diferentes, que poderá dificultar de maneira significativa a coleta de dados e também seu monitoramento em tempo real pelos profissionais. 
O terceiro ponto são os custos. Atualmente, diversas indústrias ainda mantém uma infraestrutura física para captação e coleta destes dados, gerando custos para manter a mesma em operação. 






 
2.	JUSTIFICATIVA PARA SOLUÇÃO

Com a solução “Brave Blue” e através de um editor intuitivo baseado em nós e módulos, a plataforma é capaz de coletar informações de diversos sensores, tendo o auxílio de um Edge Gateway, um sistema que coleta diretamente os dados e os envia para nuvem, onde são armazenados no banco de dados da preferência do usuário/empresa, assim, possibilitando um melhor controle de todo o processo de forma digital e em nuvem, como também a geração de seus respectivos gráficos com maior facilidade para uma tomada de decisão, identificação de falhas no processo e até de problemas físicos, como por exemplo, um vazamento de água em uma tubulação interna de um prédio ou de uma indústria, que pode acarretar em uma maior despesa com custos fixos. 
A nossa proposta de valor é oferecer uma tecnologia moderna utilizando ferramentas OpenSource, fazendo com que o custo final seja mais baixo. Ofereceremos planos mensais com faturamento anual, fazendo com que o ganho no curto prazo seja ainda maior. Como concorrentes e inspiração, podemos citar a The Things Network e The Things IO, plataformas internacionais e de grande porte no ramo de iOT. Vale destacar que esse é um mercado crescente com os anos, do qual ainda tem um grande potencial de crescimento e inovação.
 
3.	EQUIPE
A equipe é composta basicamente por 4 integrantes:
- Arthur Gebara – responsável pelo marketing, publicidade e analytics, utilizando métricas de engajamento e campanhas individuais de publicações em redes sociais visando aumento de vendas da Startup.
- Keny Oshiro – desenvolvedor da plataforma, responsável pelo desenvolvimento, manutenção e atualizações de features da plataforma, visando sempre aumento de performance e compatibilidade com os diversos sensores disponíveis no mercado.
- Matheus Toledo – responsável pelo gerenciamento do projeto da Startup e também do setor financeiro, atuando em projeções financeiras futuras, análise comercial de mercado e também gestão das demandas de redução de custos. 
- Yan Alexandre – desenvolvedor front-end, responsável pelo desenvolvimento, manutenção e atualizações de toda a parte visual da plataforma, visando também um layout mais fluído e intuitivo para os usuários finais. 
 
4.	VALIDAÇÃO DO PROBLEMA 
Para validação do problema, foi efetuada uma pesquisa de campo. A pesquisa do grupo Flow Team tem por objetivo demonstrar com as respostas dos usuários o conhecimento em geral de um sistema de controle de medidores, quais os medidores e sistemas mais conhecidos e também identificar as necessidades mais citadas pelos usuários, com o objetivo de desenvolver uma plataforma de gerenciamento de medidores de vazão, para auxiliar na análise de oportunidades de negócios, redução de custos, público alvo, entre outros, com base nas informações que serão fornecidas pelos respectivos equipamentos.

Análise dos dados e resultados

- 71% dos usuários relatam não ter conhecimento de sistemas de controle de fluxo, o que nos trás duas hipóteses de análise. A primeira é de que a pergunta não foi clara o suficiente para entendimento do público em geral, o que dificultou na resposta desta questão. A segunda seria de que realmente sistemas de controle de fluxo não são conhecidos pelo público como um todo, o que pode ser justificado pelos 29% de afirmação nas respostas.


- Novamente 71% dos usuários não reconhecem nenhuma marca de medidores no geral, demonstrando que o assunto retratado seria mais específico para profissionais de ramo industrial, como empresas de óleo diesel, companhias elétricas, companhias de água ou quaisquer outros profissionais que se utilizam de medidores em seu dia a dia, tais profissionais são representados nos 29% das respostas “Sim”.


- A questão demonstra que apenas 36% dos usuários tiveram contato com sistemas de controle de fluxo de dados, o que demonstra que o público alvo é específico, não sendo de conhecimento popular de muitos profissionais. 


- Dos usuários que se utilizam de controle de fluxo de dados, 43% demonstram satisfação mediana com suas ferramentas, o que nos leva a conclusão de que a plataforma que será desenvolvida pelo grupo deve contar com funcionalidades atualizadas e que facilitem cada vez mais a rotina de trabalho do usuário, visando uma maior satisfação com a ferramenta e seus respectivos monitoramentos dos dados.


- Em nosso MVP, foi citado a personalização de gráficos e indicadores de acordo com a necessidade do usuário e empresa, o que pôde ser comprovado como uma necessidade pela pesquisa, com 86% de respostas para “sim” para que ter o controle total de fluxo, alertas e indicadores podem trazer vantagens positivas, ou seja, quanto mais informações puderem ser transmitidas para os usuários, melhor será a satisfação com relação a mesma.
- Em vista do controle total dos alertas, indicadores e fluxo, os usuários também demonstram a necessidade de um controle de acesso ligado a privilégios, seja de administrador, usuário comum ou até cliente, devido à grande gama de aplicações da plataforma, com 86% de respostas positivas. 


- A geração de dados em tempo real não demonstra extrema necessidade pelos usuários, com 57% das respostas “Talvez”, o que demonstra que, mesmo com a possibilidade de ser um diferencial da plataforma, o que realmente interessará em sua utilização serão os controles e possibilidades de personalização da mesma, podendo viabilizar uma maior satisfação em sua utilização no dia a dia.


- É possível concluir que mesmo com diversas cláusulas de segurança dentro de suas empresas, 36% dos usuários se sentem parcialmente seguros, receosos com o vazamento de seus dados via sistemas/softwares empresariais, o que demonstra, acima de tudo, a importância no investimento de proteções nos dados dos usuários. 
Ao serem questionados da importância do fator personalização para que o sistema fique funcional, deixamos as respostas mais relevantes abaixo:
“É muito importante a personalização dos sistemas de gestão, principalmente nas questões envolvendo permissões especiais para administradores de fluxos variados de produtos e gestores das áreas de segurança e qualidade.”
“Filtragem de dados e fornecimento de ferramentas comparativas.”
“Acredito ser importante pois cada usuário tem sua própria filosofia de controle e de gerenciamento, essa flexibilidade na personalização atende uma gama maior de usuários.”
Conclusão
Com a pesquisa de campo, pudemos concluir que o desenvolvimento da plataforma para o controle de fluxo de dados e medidores é válida, porém com uma maior necessidade de divulgações específicas com leadings qualificados de empresas que se utilizam destes sistemas. 
Foi possível visualizar que a quantidade de profissionais que possuem conhecimento referente ao tema são poucos, demonstrando uma necessidade de que a plataforma a ser desenvolvida possa ser funcional com diversos equipamentos e medidores diferentes, com o objetivo de popularizar e abranger um número maior de setores industriais ou do dia a dia de clientes, como concessionarias de água, energia, condomínios, etc. 


 




 
5.	MERCADO ALVO 
O mercado de IoT (Internet of Things) é um dos principais pilares tecnológicos para a transformação digital do mundo em que vivemos e tem como principal objetivo de mudar a maneira como as empresas atuam e também a forma como vivemos, trazendo um grande impacto na economia na realidade de muitos modelos de negócio e já é considerado indispensável para grande parte das organizações ao redor do globo. Como exemplo, podemos citar o Agronegócio e a Construção Civil. 
Como citado anteriormente, o IoT está presente em todos os lugares, principalmente no nosso dia a dia, hoje, basicamente se você possui um smartphone e acesso à internet, com certeza utiliza pelo menos um processo ou dispositivo de IoT. 
Segundo um estudo da CI&T e da Opinion Box, realizado com 1241 executivos brasileiros, os mesmos apontaram que 44,8% dos profissionais já veem a tecnologia IoT como indispensável para o crescimento das empresas. A pesquisa mostra também que 22% dos líderes empresariais adotaram ações em 2020 para digitalizar os negócios. Ainda segundo uma projeção feita pela Mckinsey, o Brasil pode ganhar 27 bilhões de dólares em potencial econômico até 2025, frutos colhidos da IoT, com a grande economia com gestão pública, transporte, segurança e energia. Além disso, o investimento em solo brasileiro cresce a cada ano, com estimativas de 17,5%, segundo o International Data Corporation (IDC), que efetuou o estudo no ano de 2019. 
As estimativas para o mercado IoT são promissoras, porém ainda falta estímulo, monitoramento, inovação e uma menor regulamentação para que este mercado siga avançando no país, e visando isso, que foi criado o Plano Nacional de Internet das Coisas (Decreto n°9854), com o foco de fomentar este tipo de tecnologia no Brasil, melhorar a qualidade de vida da população e também aumentar a eficiência na prestação deste tipo de serviço, basicamente, dar mais espaço à IoT em território nacional.
Como segmento de entrada, o Brave Blue tem como foco as indústrias, sejam elas agropecuárias ou de qualquer setor que esteja engajado em implementar soluções IoT, atuando com licenças para utilização, além de um projeto personalizado para cada cliente, visando uma maior customização e atendimento das necessidades específicas de cada um. A plataforma também poderá ser utilizada para condomínios inteligentes por exemplo, atuando no controle de consumos de insumos como água, gás e eletricidade, possibilitando não só um estudo de quais moradores utilizam mais estes recursos, como também a possibilidade de cobrança individual por unidade, fazendo a cobrança de maneira mais coerente. 

Referências.
“Mercado de IoT movimentará mais de 30 bilhões de dólares na América Latina até 2023” Portal Terra.
Disponível em: <https://www.terra.com.br/noticias/dino/mercado-de-iot-movimentara-mais-de-30-bilhoes-de-dolares-na-america-latina-ate-2023,8be0917d3e48fedd08180dae6859cd396i1iizxg.html>
Acesso em: 15.11.2021

“Previsões para o Mercado de IoT” ABINC (Associação Brasileira de Internet das Coisas).
Disponível em: <https://abinc.org.br/previsoes-para-o-mercado-de-iot/>
Acesso em: 15.11.2021

“O Que Falta Para Impulsionar O Mercado De IoT No Brasil?”, ConnectData.
Disponível em: <https://www.connectdata.net/post/o-que-falta-para-impulsionar-o-mercado-de-iot-no-brasil>
Acesso em: 15.11.2021



 
6.	MODELO DE NEGÓCIO 
CANVAS:





MAPA DE EMPATIA:




 
7.	ANÁLISE DO MERCADO 
5 forças de Porter:

Análise SWOT da solução:

Quadro comparativo de concorrentes:

















8.	ANÁLISE FINANCEIRA E PROJEÇÃO DE CRESCIMENTO
Por se tratar de uma startup e também de uma nova empresa que surge, com isso, um novo CNPJ, custos de abertura e homologação da empresa, compra de equipamentos, assinatura de tecnologias são necessários, e com isso, um investimento inicial. A equipe Flow Team estima como custo para iniciação na casa dos 26 mil reais, considerando todos os custos citados acima e também custos com o desenvolvimento do site e desenvolvimento do sistema Brave Blue em si. 
Como dito ao longo deste documento, o Brave Blue atuará com 3 planos padrão (Standard, Premium e Suporte Especializado), além da opção de customização total da plataforma em si para os clientes, que possui seu próprio custo, já que depende de mais horas de desenvolvimento, briefing e alinhamentos com o cliente. 
Para estimativa de custo das licenças, foi utilizado um cálculo envolvendo todos os custos mensais com tecnologia, salários da equipe e depreciação dos equipamentos eletrônicos. Além disso, efetuamos por meio de alinhamentos junto à equipe de desenvolvimento, uma porcentagem de horas mensais necessárias para atualizações e possíveis manutenções em cada licença, de acordo com o tipo de plano selecionado, considerando o Suporte Especializado com a necessidade de 88 horas mensais, Premium com 52,8 horas mensais e Standard 35,2 horas mensais (176 horas mensais utilizadas nesta base de cálculo). Com os resultados apresentados, multiplicados pelo valor hora mensal da operação, chegamos aos custos necessários de cada operação para as licenças e, estimando a venda de 50 licenças por plano, os valores mensais foram definidos, com R$33,68 no Plano Standard, R$50,52 no Plano Premium e R$84,20 para o Plano Suporte Especializado.
Para estimativa de custo para o serviço de customização, a equipe de desenvolvimento estima aproximadamente 50 horas para efetuar o serviço, que, multiplicado ao valor hora da operação, resultou no valor de R$2.392,05 por customização.
Definidos os custos de licença, chegou a hora do cálculo para conclusão do break-even. A margem de contribuição utilizada para cálculo foi de 30%, retornando um valor de R$26.955,26 para que seja possível arcar com as custas operacionais de todas as licenças, e manter a StartUp positiva em seu faturamento mensal.




9.	MVP - FUNCIONALIDADES ESSENCIAIS
Como MVP, as seguintes funcionalidades foram especificadas:
1 - Receber uma entrada de um dispositivo.
2 - Compatibilidade de dados via protocolo ModBus.
3 - Configurar ao menos um tipo de modificador (receber a entrada e tratar ela, como um cálculo ou algo assim).
4 - Configurar ao menos uma saída (Gráfico, Excel, CSV ou arquivo de integração em outro sistema).























10.	PROTÓTIPO FUNCIONAL
O protótipo é baseado em módulos e nós em uma página Single View (Uma página única), onde é possível realizar todas as operações, e uma página de Login.
Na página de Login implementamos o Login pelo Google, sem necessidade da criação de uma conta na plataforma para utilização, dessa forma acreditamos que será mais fácil para o usuário acessar com seu e-mail corporativo.























	

A plataforma exibirá qual o usuário conectado.

A tela inicial tem um menu lateral com Entrada, Modificador e Saída onde será possível definir os parâmetros utilizados de acordo com a necessidade do cliente. Para atender ao esperado no MVP, foram criados dois parâmetros de entrada, um modificador e uma saída.

Para um primeiro exemplo, será incluido uma entrada de LeitorCSV e a saída em gráfico, sem modificador. O arquivo CSV usado no exemplo simula uma extração de dados de uma base e formato de acordo com a plataforma. Após anexar o arquivo, a caixa do leitor de saída deverá ser ligada à saída em gráfico, fazendo com que os dados sejam mostrados de forma automática.


Para o próximo exemplo, utilizaremos a entrada de uma API, ainda sem o modificador. Com os dados adicionados o cálculo é feito em Litros.








Na mesma tela, ao adicionar e ligar o conversor de L para M³ o gráfico é atualizado com os novos dados.

Se desligarmos então o conversor, o gráfico volta com a contagem em litros.






















11.	PLANO DE MARKETING
Informação sobre o negócio:
Nossa missão é oferecer uma plataforma de IoT focada na resolução 3 de problemas de usuário em relação a sensores e medidores, sendo eles:
1- Escalabilidade
2 - Integração
3 - Custo
Acreditamos que levando em conta essas 3 bases, conseguiremos solucionar o problema e atrair clientes para que escolham nossa plataforma.

Nosso time de Marketing é liderado por Arthur Gebara, do qual será o responsável pela escolha das estratégias, aplicação e acompanhamento de métricas e KPIs
Yan Alexandre será o responsável pelas áreas de SEO e UX, do qual se conecta diretamente ao time de Marketing, fazendo com que as metas sejam mais fáceis de serem atingidas. 


Introdução / metas
Seguindo a linha da nossa proposta de valor, além de diminuir o preço para o cliente final, o desenho da solução também reduz o investimento inicial da nossa Start Up. Com o uso de softwares Open Source não será necessário a aquisição de programas de desenvolvimento.
Temos como previsão de investimento inicial 26 mil reais, para que as máquinas de usuários sejam compradas e a empresa licenciada. No nosso modelo de negócio os 4 funcionários trabalharão Home Office, fazendo o corte em gastos de escritório, rede, energia e manutenção de ambiente.
Calculamos um custo mensal de operação em torno de 8,5 mil reais.
Com base nesse número nossa meta é a empresa comece a ficar positiva em aproximadamente 1 ano e meio, tendo em vista as estratégias de Marketing e alcance de novos clientes
Faremos também um levantamento de leads, do qual já traremos antes do início da operação uma vasta lista de possíveis clientes, que serão usados também como base na implementação de outros no futuro.

Análise competitiva e situacional
O mercado de iOT cresce a todo ano em um nível imenso. De acordo com o levantamento de 2020 da consultoria de análise de dados GlobalData, o mercado de IoT deve movimentar mais de 30 bilhões de dólares na América Latina até 2023.
O Brasil ainda é iniciante no mercado e o investimento em 2019 foi de aproximadamente 6,1 milhões de dólares, ainda sim 45% maior que o ano anterior.
Tendo em vista esse cenário, estamos entrando em um mercado novo, onde não temos empresas referências no Brasil. No ramo de IoT existe a LinkSolutions e fora daqui temos The Things IO e The Things Internet, referências no setor.
A ideia é que a plataforma Brave Blue se situe primeiramente como a opção mais acessível ao cliente e por ser uma empresa menor, teremos um atendimento especializado e focado na operação do cliente.

Mercado alvo
Indústrias interessadas em aplicar IOT para monitorar, escalar e integrar seus equipamentos/sensores através de dados que, com a nossa aplicação, tornam-se métricas aplicáveis ao desenvolvimento da empresa.

Proposição de valor (Unique Selling Proposition)
Por utilizarmos tecnologias Open Source em nossa solução conseguimos fornecer ao cliente taxas de serviços abaixo do mercado, entretanto, iremos manter a qualidade e disponibilidade do produto. Além das taxas menores, outro fator importante de diferenciação é o fornecimento das informações/métricas em real-time, algo que a maioria das soluções presentes no segmento não disponibiliza.

Marca
A ideia é que a marca Brave Blue se torne um nome em status de ascensão nos próximos 4 anos.
Utilizaremos o nome da marca também para futuras soluções, assim herdando o histórico construído ao longo dos anos.

Website
Teremos um Website bem desenvolvido e otimizado, com vídeos explicativos sobre soluções, planos e cases de sucesso.
O site será bem desenvolvido, seguindo regras de SEO e SEM, utilizando foco em conteúdo, palavras chave, títulos e meta descrição, URL descritivas e alt text, além da necessidade de ser uma página leve e mobile friendly.

Canais de marketing
Nossa principal fonte de Marketing será o LinkedIn, onde iremos ter uma página forte de conteúdo semanal sobre o mercado e a empresa em si. O objetivo é atingir as empresas e interessados no assunto, fazendo com que a procura da nossa solução seja direta.

Medições
Medir resultados constantemente é uma das principais atividades para o marketing. Definiremos a periodicidade das medições de acordo com data, tamanho e investimento em cada uma das campanhas de marketing para que não seja desperdiçado dinheiro em algo que não traga retorno suficiente. 

Estratégia e Tática
Pretendemos utilizar algumas estratégias para realização do marketing, sendo elas:
- Criação de conteúdo frequente
- Redes sociais interativas e auxiliares para atendimento ao cliente inicial
- E-mail Marketing



12.	TECH FOR GOOD
A Tech for Good trata de oportunidades que compartilham uma visão positiva do futuro, utilizando a tecnologia para obter um impacto positivo nas pessoas, comunidades e no planeta. Pensando nos 17 objetivos de desenvolvimento sustentável, a equipe Flow Team e sua plataforma Brave Blue atendem aos objetivos, principalmente os ligados à sustentabilidade, crescimento econômico, indústria, inovação e infraestrutura, além de todos os outros objetivos que envolvam a coleta e processamento de dados para análise e desenvolvimento de uma solução efetiva. 
De acordo com a equipe, o Brave Blue é adaptável, podendo ser utilizados não só com sensores de vazão, mas também com quaisquer dados e informações que possam ser captados por meio de APIs e bancos de dados também. De maneira geral, a plataforma com a utilização do IoT, facilita na análise, geração de gráficos e por fim, em todo o processo para a construção de soluções sustentáveis, inovadoras e tecnológicas.
Como exemplo, podemos citar a captação de informações referente aos emissores de poluentes nas indústrias, que retornarão as quantidades de gases poluentes emitidos pelas mesmas durante o período solicitado, gerando gráficos de análise que podem apontar as regiões industriais mais prejudiciais ao planeta, além de qual poluente específico está sendo o mais degradante. Com estes dados em mãos, as equipes responsáveis poderão pensar em soluções mais assertivas e conclusivas de como os processos de fabricação, logística e operação das indústrias podem ser menos prejudiciais ao planeta, buscando meios de energia mais limpa e sustentável e utilizando as regiões agravantes como testes para homologação de suas ideias junto à ONU.











13.	REFERÊNCIAS
“Mercado de IoT movimentará mais de 30 bilhões de dólares na América Latina até 2023” Portal Terra.
Disponível em: <https://www.terra.com.br/noticias/dino/mercado-de-iot-movimentara-mais-de-30-bilhoes-de-dolares-na-america-latina-ate-2023,8be0917d3e48fedd08180dae6859cd396i1iizxg.html>
Acesso em: 15.11.2021

“Previsões para o Mercado de IoT” ABINC (Associação Brasileira de Internet das Coisas).
Disponível em: <https://abinc.org.br/previsoes-para-o-mercado-de-iot/>
Acesso em: 15.11.2021

“O Que Falta Para Impulsionar O Mercado De IoT No Brasil?”, ConnectData.
Disponível em: <https://www.connectdata.net/post/o-que-falta-para-impulsionar-o-mercado-de-iot-no-brasil>
Acesso em: 15.11.2021

“HTTP, WS & MQTT for IoT”, Techbeast.org.
Disponível em: < https://www.youtube.com/watch?v=f4JmhGBsRkQ>
Acesso em: 05.2021

“IOT CONNECTIONS TO REACH 83 BILLION BY 2024, DRIVEN BY MATURING INDUSTRIAL USE CASES”, Juniper Research.
Disponível em: < https://www.juniperresearch.com/press/iot-connections-to-reach-83-bn-by-2024>
Acesso em: 05.2021





14.	APÊNDICE
Apêndice A – Planilha Financeira 
Link de acesso: < https://docs.google.com/spreadsheets/d/1yzBkQYuv2UtQMIhOMGU6e-Wu3wr0YKscrGD5WWcM0_k/edit?usp=sharing>

APÊNDICE C – 
Diagrama de Entidade-Relacionamento (Utilizado NextAuth.js):
 
Casos de Uso:
