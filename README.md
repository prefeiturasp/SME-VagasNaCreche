# Estratégia de Transformação Digital e Governo Aberto na SME  
  
Como um governo pode atuar para garantir o bem comum de todos? Na SME, acreditamos que um dos meios para isso seja garantir transparência e prestação de contas e constante relação entre governo e sociedade para o desenvolvimento e implementação de políticas públicas.  
  
A Portaria SME nº 8.008, de 12 de novembro de 2018 oficializou a estratégia da Secretaria Municipal de Educação de SP para que nossas ações sejam pautadas nos princípios de Governo Aberto e para usarmos os valores e benefícios do mundo digital para melhorarmos nossos processos e serviços para os cidadãos. Com isso, pretendemos:  
  
- aumentar os níveis de transparência ativa e de abertura de dados, garantindo a proteção de dados pessoais;  
- instituir metodologias ágeis e colaborativas como parte do processo de desenvolvimento e de evolução de sistemas administrativos e de serviços digitais;  
- fortalecer o controle das políticas educacionais e da aplicação de recursos por parte da gestão e da sociedade;  
- promover espaços e metodologias de colaboração entre governo, Academia, sociedade civil e setor privado.  
  
**O Ateliê do Software** ([http://forum.govit.prefeitura.sp.gov.br/uploads/default/original/1X/c88a4715eb3f9fc3ceb882c1f6afe9e308805a17.pdf](http://forum.govit.prefeitura.sp.gov.br/uploads/default/original/1X/c88a4715eb3f9fc3ceb882c1f6afe9e308805a17.pdf "http://forum.govit.prefeitura.sp.gov.br/uploads/default/original/1x/c88a4715eb3f9fc3ceb882c1f6afe9e308805a17.pdf")) é uma das ferramentas para operacionalização. Baseado em um modelo de contratação inspirado pelos movimentos ágil e de Software Craftsmanship, trabalhamos com equipes multidisciplinares para o desenvolvimento de produtos que beneficiam toda a comunidade escolar (técnicos da SME e DREs, gestores, professores, alunos e famílias) e concretizam os objetivos da Estratégia de Transformação Digital e Governo Aberto “Pátio Digital”.

# Plataforma Vaga na Creche

**Visão do Produto**

Para a qualquer cidadã(o) interessada(o) que queira saber como está a espera por atendimento nos Centros de Educação Infantil (CEIs) e as vagas disponíveis, o Vaga na Creche  é uma aplicação web responsiva que facilita essa consulta a partir de um dado endereço e da faixa etária informada. Ao contrário da sua versão beta, o Fila da Creche, o Vaga na Creche  informa a fila também por CEI (e não apenas o agregado de uma dada localidade) e permite a busca por vagas ociosas.

Conteúdo
1. [Sobre o Time](#sobre-o-time)  
2. [Sobre o Produto](#sobre-o-produto)  
3. [Como surgiu](#como-surgiu)  
4. [Links Úteis](#links-úteis)  
5. [Comunicação](#comunicação)  
6. [Como contribuir](#como-contribuir)  
7. [Repositórios](#repositórios)  
8. [Documentações Auxiliares](#documentações-auxiliares)  
9. [Instalação e Configuração](#instalação-e-configuração)


## [](#sobre-o-time)Sobre o Time

| Papel | Titular | Suplente  
|--|--|--|  
| Product Owner | Thaís Brianezi, Fátima Cristina Abrão, André Machado Sanches e Carolina Sciariotta Gomes dos Reis| Gabinete de SME, COGED, CIEDU e COTAC |  
| Agente de Governança | Filipe Carvalho | COTIC/SME |  
| Gerente de Projeto | Aline Freitas |AMCOM  |  
| Scrum Master | Marcos Nastri | AMCOM |  
| Design de Serviços | Fagner Silva | AMCOM |  
| Analista UX/UI | Jennifer Moreno |  AMCOM |  
| Analista Programador | Giuseppe de Oliveira Rosa | AMCOM |





## [](#sobre-o-produto)Sobre o Produto

**Objetivos de negócio**

Ser instrumento de transparência ativa, em linguagem simples e com acessibilidade digital, fornecendo informação detalhada que possa apoiar as famílias na decisão de solicitar ou não vaga em um Centro de Educação Infantil (CEI) e como (ou seja, quais endereços registrar no cadastro da criança).

**Personas**

Responsável pela criança de até 4 anos incompletos que ainda não solicitou vaga na creche municipal:  consultar a espera por atendimento nos Centros de Educação Infantil (CEIs), de acordo com o endereço fornecido e a faixa etária informada, para decidir se solicita ou não uma vaga e como (ou seja, quais endereços registrar no cadastro da criança).

Responsável pela criança de até 4 anos incompletos que aguarda vaga na creche municipal:  consultar a espera por atendimento nos Centros de Educação Infantil (CEIs), de acordo com o endereço fornecido e a faixa etária informada, para decidir se acrescenta um segundo endereço no cadastro da criança ou se alguma vaga ociosa atende sua necessidade mais urgente.

Responsável pela criança de até 4 anos incompletos que já está na creche municipal:  consultar a espera por atendimento nos Centros de Educação Infantil (CEIs), de acordo com o endereço fornecido e a faixa etária informada, caso tenha interesse em pedir transferência para outro Centro de Educação Infantil (CEI).

Cidadã(o) em geral: qualquer pessoa interessada em consultar a espera por atendimento nos Centros de Educação Infantil (CEIs), de acordo com o endereço fornecido e a faixa etária informada.

Servidores: buscam informações e dados gerenciais a respeito da espera por atendimento nos Centros de Educação Infantil em um dado território e da existência de vagas ociosas, para  subsidiar  seus  trabalhos  de  análise  e  planejamento  da  política  educacional.

Jornalistas e demais comunicadores: consomem informações e dados a respeito da espera por atendimento nos Centros de Educação Infantil e da existência de vagas ociosas, para levantar pautas e subsidiar suas matérias.

Pesquisadores:  consomem informações e dados a respeito da espera por atendimento nos Centros de Educação Infantil e da existência de vagas ociosas,  como subsídio para os estudos e análise da política educacional da Prefeitura de São Paulo, que contribuem com o seu constante aprimoramento.

**Funcionalidades**

-   Busca os Centros de Educação Infantil mais próximos de um dado endereço (logradouro e número) e informa a espera por atendimento para uma determinada faixa etária em cada Centro de um deles (além da fila agregada naquela localidade).
    

-   Consulta eventuais vagas livres nos Centros de Educação Infantil (CEIs), para uma determinada faixa etária e a partir de três filtros de busca (Distrito, Subprefeitura ou Diretoria Regional de Educação – DRE).
    
-   Apresenta os resultados em mapa interativo, com georreferenciamento e dados de contato (endereço e telefone) de cada Centro de Educação Infantil.
    
-   Apresenta informações em linguagem simples (inclusive em vídeos) sobre como funciona o processo de solicitação de vagas para os Centros de Educação Infantil e as regras de andamento da fila.
    

**Jornadas**

O(a) usuário(a) acessa a homepage do Vaga na Creche e seleciona o mês e ano de nascimento da criança para a qual gostaria de uma vaga e o endereço (logradouro e número) que deseja consultar. Ele(a) então terá acesso a uma página com os Centros de Educação Infantil (CEIs) mais  próximos que atendem aquela faixa etária, com o total de crianças aguardando vaga naquele grupamento em cada CEI e a fila agregada daquela área. Ele(a) também consegue nesta página consultar o nome completo, endereço exato e contato (telefone e e-mail) de cada CEI listado.

O(a) usuário(a) acessa a homepage do Vaga na Creche e seleciona no menu superior a opção “Consulte vagas remanescentes”. Ele(a) então seleciona o mês e ano de nascimento da criança e opta por uma das três categorias de busca (Distrito, Subprefeitura ou Diretoria Regional de Educação – DRE). Depois, escolhe a área específica na qual deseja realizar a consulta. Ele(a) terá acesso a uma página que informa (em lista e em mapa interativos) se há (e quantos e quais são) os Centros de Educação Infantil (CEIs) com vagas disponíveis para atendimento àquela faixa etária naquela região (e, em caso positivo, quantas vagas há em cada CEI em questão). A pessoa consegue nessa página consultar o nome completo, endereço exato e contato (telefone e e-mail) de cada CEI listado.

O(a) usuário(a) acessa a homepage do Vaga na Creche e assiste ao vídeo que explica como solicitar uma vaga em um Centro de Educação Infantil (CEI) e como funciona a fila. Ele também pode ler os itens “A criança já está cadastrada à espera de uma vaga?” ou “Quer saber mais sobre cada Centro de Educação Infantil?” e optar por ser direcionado, respectivamente, para a consulta logada sobre a posição da criança na fila (EOL gerenciamento) ou para a plataforma Escola Aberta. Por fim, se selecionar no menu superior a opção “Sobre o vaga na creche”, a pessoa terá acesso a conteúdos de texto e vídeo que explicam em detalhes o histórico da aplicação, suas regras de funcionamento e como realizar a consulta.

**RoadMap**

MVP1

- Consulta geográfica de disponibilidade de vagas
- Perguntar o endereço do trabalho e trazer a sugestão de endereços  
- Consultar EOL  
- Mostrar o resultado de quantas  crianças, data de atualização  
- Mostrar a lista de escolas  obedecendo  os  critérios de distância  
- No final da página mostrar links (O que posso fazer agora)
- Novo endereço do Vaga na Creche
- Criação do novo endereço
- Reconstruir novo site para suportar as novas  demandas
- Novo site com infra mais  robusta para seu novo uso que será  intensificado
- Consulta de Vagas Remanescentes
- Com base em  endereço  mostrar  uma  lista por escola e distância do endereço

MVP2

- Dados gerenciais da Demanda
- Ambiente  administrativo  logado  
- Relatórios  gerenciais dos endereços  mais  buscados  
- Mapas de calor

MVP3

- Cruzamentos de dados com imóveis  cadastrados  como  potenciais  locais para instalação de Centros de Educação  Infantil e com as solicitações online (pré-cadastro) por vagas  em Centros de Educação  Infantil
- Relatórios gerenciais e mapas de calor no Ambiente logado


## [](#como-surgiu)Como surgiu

A plataforma Vaga na Creche é resultado da evolução do sistema Fila da Creche, que foi lançado em abril de 2018, em versão beta (de teste), como um dos produtos da iniciativa de governo aberto da Secretaria Municipal de Educação (Pátio Digital).

Sobre o Pátio Digital: [http://patiodigital.prefeitura.sp.gov.br/o-que-e-o-patio-digital/](http://patiodigital.prefeitura.sp.gov.br/o-que-e-o-patio-digital/)

Sobre o Fila da Creche: [http://patiodigital.prefeitura.sp.gov.br/?s=fila+da+creche  
](http://patiodigital.prefeitura.sp.gov.br/?s=fila+da+creche)

Nos 20 meses de uso experimental do Fila da Creche, mais de 2,2 mil usuários preencheram o formulário de avaliação da ferramenta: `https://smeprefeituraspgov-my.sharepoint.com/:x:/g/personal/thais_ng_sme_prefeitura_sp_gov_br/EccKEaZuHUxMjEuiv-3itOUBXpqOOdP3EJj36zVXbv1YGA?e=NVtuGg`

Os elogios, críticas e sugestões apresentadas por eles, assim como as propostas colhidas na oficina presencial realizada no dia 29 de outubro de 2019 com mães e pais em idade de Berçário e Mini Grupo, contribuíram para o aprimoramento da ferramenta.

Materiais utilizados na referida oficina:


`https://smeprefeituraspgov-my.sharepoint.com/:b:/g/personal/thais_ng_sme_prefeitura_sp_gov_br/EVUpK3QkP6hLskE2uC2TVDUBjuNXD3ibP6OOPaBKq5u5XQ?e=7sF1bv`

`https://smeprefeituraspgov-my.sharepoint.com/:b:/g/personal/thais_ng_sme_prefeitura_sp_gov_br/ES7lAQOPVzxCrallVlyI0WEBm8j-7N3pZXdKvy18ZK6KAA?e=qhPoYA`

`https://smeprefeituraspgov-my.sharepoint.com/:b:/g/personal/thais_ng_sme_prefeitura_sp_gov_br/EdaToyQsVe5Jo5sM69TZYZIB5lk2nOOCZr1BK-0NqYdzHw?e=ClI4gg`

`https://smeprefeituraspgov-my.sharepoint.com/:b:/g/personal/thais_ng_sme_prefeitura_sp_gov_br/EfpBcdjTt9BBtwzZibs-nHUBDX3yVv6SAR6KwscyrEU_5A?e=Vy4anc`

**Protótipos:**

Home page: [https://www.figma.com/file/AJSnPLfZcIm9m8Zj21EBsu/Vaga-na-Creche?node-id=0%3A1](https://www.figma.com/file/AJSnPLfZcIm9m8Zj21EBsu/Vaga-na-Creche?node-id=0%3A1)

**Resultado da busca:** [https://www.figma.com/file/AJSnPLfZcIm9m8Zj21EBsu/Vaga-na-Creche?node-id=11%3A158](https://www.figma.com/file/AJSnPLfZcIm9m8Zj21EBsu/Vaga-na-Creche?node-id=11%3A158)

Vaga remanescente: [https://www.figma.com/file/AJSnPLfZcIm9m8Zj21EBsu/Vaga-na-Creche?node-id=82%3A241](https://www.figma.com/file/AJSnPLfZcIm9m8Zj21EBsu/Vaga-na-Creche?node-id=82%3A241)


## [](#links-úteis)Links Úteis

Homologação:

[https://hom-vaganacreche.sme.prefeitura.sp.gov.br/](https://hom-vaganacreche.sme.prefeitura.sp.gov.br/)

Produção:

[https://educacao.sme.prefeitura.sp.gov.br/vaga-na-creche/](https://educacao.sme.prefeitura.sp.gov.br/vaga-na-creche/)

## [](#comunicação)Comunicação

Canal de comunicação

Telegram

-   Alinhamento sobre produto
    

-   Comunicar novidades sobre os produtos
    
-   Movimentar a comunidade
    
-   Falar tópicos que não demandem discussões profundas
    


## [](#como-contribuir)Como contribuir

Contribuições  são super bem  vindas! Se você  tem  vontade de construir o portal da secretaria municipal e educação  conosco, veja o nosso  guia de contribuição  onde  explicamos  detalhadamente  como  trabalhamos e de que formas  você  pode  nos  ajudar  a  alcançar  nossos  objetivos. Lembrando que todos  devem  seguir  nosso  código de conduta.


## [](#repositórios)Repositórios

[SME-VagaNaCreche]
[https://github.com/prefeiturasp/SME-VagasNaCreche](https://github.com/prefeiturasp/SME-VagasNaCreche)

[SME-VagaNaCreche-API]
[https://github.com/prefeiturasp/SME-VagasNaCreche-API](https://github.com/prefeiturasp/SME-VagasNaCreche-API)

[SME-VagaNaCreche-FrontEnd] [https://github.com/prefeiturasp/SME-VagasNaCreche-FrontEnd](https://github.com/prefeiturasp/SME-VagasNaCreche-FrontEnd)


## [](#instalação-e-configuração) Instalação e Configuração

Em desenvolvimento.
