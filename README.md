# DDD - Domain-Driven Design 

Domain-Driven Design trata-se de uma orientação dada por Eric Evans, à comunidade de softwares orientados a objetos, com o objetivo de salvar projetos de softwares que não fizeram o uso correto do paradigma, e também com o objetivo de orientar a comunidade para que nos novos projetos não cometam os mesmos erros de outrora. 

A orientação a objetos é uma ótima ferramenta para o desenvolvimento de softwares, pois sua utilização correta fornece uma série de benefícios durante a vida útil do software. Os principais benefícios são a manutenibilidade (fácil e flexível), a reutilização de código, a produtividade e o ROI (o mais importante para os negócios).

O problema é que durante muitos anos a comunidade focou pontos importantes do desenvolvimento de um software, mas deu pouca atenção ao ponto central, que é o domínio do problema. Essa escolha gerou uma série de avanços aos pontos priorizados, mas gerou uma série de problemas no ponto central de sistemas empresariais, que num dado momento começou a contaminar todos os pontos de desenvolvimento. E é por isso que convivemos ainda hoje com softwares legados, até mesmo de baixa/média complexidade, que exigem servidores parrudos, infraestrutura de auto custo e que muitas vezes mais trazem prejuízos do que lucros. 

Assim como DDD, os princípios SOLID, também são conceitos fundamentais no desenvolvimento de software. Diferentemente do DDD, que pode ser aplicado somente em projetos complexos, os princípios SOLID podem e devem ser aplicados em todo e qualquer projeto de software orientado a objetos.

Não é fácil projetar software com qualidade, pois durante anos fomos orientados a projetar sem começar pela análise do ponto central (o problema do negócio) e sim a começar pela análise de interface com o usuário (UI) ou pelo modelo relacional de dados (MER) e aí vai. 

Durante anos especialistas (arquitetos e engenheiros) fizeram uma série de contribuições para tornar o projeto de softwares orientados a objetos mais fácil, e Eric Evans que cunhou o termo DDD teve a coragem de unir fundamentos, conceitos, técnicas, boas práticas e padrões e aplicá-los em projetos práticos (Design Flexível + Tijolos de Construção). 

Portanto DDD é uma orientação baseada na aplicação prática de fundamentos, conceitos, técnicas, boas práticas e padrões de projetos que em certos casos deu certo e em outros deu errado. 

Como o próprio Eric Evans fala, DDD é framework. É um framework pois não é uma receita pronta para tudo e sim uma abordagem que pode ser usada e ajustada de acordo com a necessidade de cada projeto. 

Inclusive não é possível desenvolver software de qualidade só com a aplicação correta dos fundamentos do paradigma e com receitas técnicas (tijolos de construção). É necessário também preocupar-se com o processo. Portanto projeto sem processo certamente vai falhar. Por isso Eric Evans fala muito em processo ágil.

Tijolos de Construção:
- Entidade (Entity Object)
- Agregado (Aggregate Object)
- Objeto Valor (Value Object)
- Fábrica (Factory Pattern)
- Serviço (Service)
- Repositório (Repository Pattern)
- Contexto Delimitado (Bounded Context)
- Mapa de Contexto
- Mapa de Nagevação 
- Módulos/Pacotes
- Arquitetura em Camadas 

Bases do DDD:
- O projeto deve ser digirido pelo modelo do domínio, ou seja, devemos priorizar a modelagem do ponto central.
- O modelo deve ser baseado em uma linguaguem onipresente (ubíqua), ou seja, todos os interessados devem falar a mesma lingua.

--- 

**Fontes** 

- Livro Domain-Driven Design - Atacando as Complexidades no Coração do Software (Eric Evans)
- Livro Implementando Domain-Driven Design (Vaughn Vernon)
- https://martinfowler.com
- http://domainlanguage.com (Eric Evans)
- https://www.youtube.com/watch?v=dnUFEg68ESM (Eric Evans)
- https://www.devmedia.com.br/ddd-domain-driven-design-com-net/14416
- http://www.eduardopires.net.br/2016/08/ddd-nao-e-arquitetura-em-camadas 
- http://www.eduardopires.net.br/2012/06/ddd-tdd-bdd 
- http://www.eduardopires.net.br/2016/03/ddd-bounded-context 
- https://www.lambda3.com.br/2017/10/desmistificando-o-ddd 
- https://www.lambda3.com.br/2017/11/ddd-aplicado-case-fluxo-de-producao-de-equipamentos-por-demanda
- https://www.lambda3.com.br/2016/10/podcast-14-domain-driven-design 
- http://blog.caelum.com.br/domain-driven-design-no-falando-em-java-2008 
- http://mouforum.blogspot.com.br/2011/05/thinking-ddd-with-patterns-part-1.html
- https://www.youtube.com/watch?v=Swc2F6MPtnY (Leandro Magnani)
- https://robsoncastilho.com.br/2016/10/15/domain-driven-design-rapido-e-rasteiro-re-post/#more-4390
- https://robsoncastilho.com.br/2014/04/16/introduzindo-a-camada-de-aplicacao
- https://robsoncastilho.com.br/2015/11/26/implementado-servicos-de-aplicacao-transacionais
- http://www.fabriciorissetto.com/blog/ddd-bounded-context
- http://andrebaltieri.com/cursos/modelando-dominios-ricos
- https://www.youtube.com/watch?v=gxP4uPaIJ3s (Ângelo Ocanã)
- http://alistair.cockburn.us/Hexagonal+architecture
- https://chicoary.wordpress.com/2012/10/31/hexagonal-architecture-in-smalltalk-series
- http://jeffreypalermo.com/blog/the-onion-architecture-part-1 
- https://8thlight.com/blog/uncle-bob/2012/08/13/the-clean-architecture.html
- https://medium.com/@stephanhoekstra/clean-architecture-in-net-8eed6c224c50
- https://herbertograca.com/category/development/architecture 
- https://www.entropywins.wtf/blog/2016/11/24/implementing-the-clean-architecture
- https://medium.com/@ronanrodrigo/viper-arquitetura-de-software-e-carros-bee4a85c613f
- https://talyssonoc.github.io/2017/04/03/NodeJS-e-boas-praticas-separar-conceitos-nao-precisa-ser-chato 
- https://github.com/talyssonoc/node-api-boilerplate
- https://www.youtube.com/watch?v=jEhL0B70xME (Camila Campos - DDD e Clean Architecture)
- https://www.youtube.com/watch?v=3kbJeDYBx-w&list=LLjfiO5nLjfnyAkqZJ4TZB_Q&index=67 (CQRS - Introdução - Software em Contexto)
- https://www.devmedia.com.br/cqrs-um-modelo-para-aplicacoes-escalaveis/29844
- https://www.infoq.com/br/presentations/bounded-context-e-cqrs-na-evolucao-de-aplicacoes-dotnet-legadas