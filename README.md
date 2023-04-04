# Learn-Awesome
A collection of links to various content related to software development, engineering and architecture




## Microsoft Channel ##

* dotNet - YouTube Channel 
<br/> https://www.youtube.com/c/dotNET

* dotNet - Blog
<br/> https://devblogs.microsoft.com/dotnet/

* dotNet Architecture Guides - Site
<br/> https://dotnet.microsoft.com/en-us/learn/dotnet/architecture-guides

* Microsoft Developer - YouTube Channel
<br/> https://www.youtube.com/c/MicrosoftDeveloper

* dotNet Foundation - YouTube Channel
<br/> https://www.youtube.com/c/NETFoundation






## Conferences ##

* NDC Conferences
<br/> https://www.youtube.com/c/NDCConferences

* Domain-Driven Design Europe
<br/> https://www.youtube.com/channel/UC3PGn-hQdbtRiqxZK9XBGqQ
<br/> https://dddeurope.com/

* Explore DDD
<br/> https://www.youtube.com/exploreddd
<br/> http://exploreddd.com/

* GOTO Conferences
<br/> https://www.youtube.com/c/GotoConferences

* QCon
<br/> https://www.youtube.com/nctv






## Persons ##

* Nick Chapsas
<br/> https://www.youtube.com/c/Elfocrash
<br/> https://nickchapsas.com/

* Mark Richards
<br/> https://www.youtube.com/channel/UC-Z7T0lAq_xECevIz8E5R5w
<br/> https://developertoarchitect.com/

* Simon Brown
<br/> https://simonbrown.je/

* Chris Richardson - Microservices.io
<br/> https://microservices.io/index.html

* Vaughn Vernon
<br/> https://www.youtube.com/c/VaughnVernon/playlists
<br/> https://kalele.io/

* Sam Newman
<br/> https://samnewman.io/

* Andrew Lock | .NET Escapades
<br/> https://andrewlock.net/

* Mathias Verraes
<br/> https://verraes.net/

* Oskar Dudycz
<br/> https://event-driven.io/en/
<br/> https://github.com/oskardudycz

* Elemar JR
<br/> https://elemarjr.com/

* Herberto Graça
<br/> https://herbertograca.com/tag/software-architecture/

* Jimmy Bogard
<br/> https://jimmybogard.com/
<br/> https://lostechies.com/

* Ardalis is Steve Smith
<br/> https://ardalis.com/

* Gunnar Peipman
<br/> https://gunnarpeipman.com/






## C4 Model ##

* The C4 model for visualising software architecture
<br/> https://c4model.com/

* Create C4 models and diagrams
<br/> https://www.diagrams.net/blog/c4-modelling

* O modelo C4 de documentação para Arquitetura de Software
<br/> https://www.infoq.com/br/articles/C4-architecture-model/

* PlantUML + C4 Model
<br/> https://github.com/plantuml-stdlib/C4-PlantUML
<br/> https://plantuml.com/






## Architectural patterns, Hexagonal, layered, clean, etc. ##

O que é BOLOVO?

BOLOVO é um padrão de arquitetura em camadas legado do Java para trabalhar com sistemas distribuídos (n-tier) onde os objetos dos processos não mantinham seu estado.

Este nome foi cunhado por Phil Calçado e significa Bussiness Objects, Layers Objects e Value Objects.

Este tipo de arquitetura leva ao desenvolvimento procedural onde componentes de uma camada mais exterior, os layer objects, chamam funções de objetos de negócio que processam os dados e criam os objetos de valores, os quais são retornados para os layers objects.

Na prática, value objects são classes que contém apenas informações (campos propriedades, sem comportamento), bussiness objects são classes que tem apenas métodos (ou seja, as procedures) além da dependência de outros serviços (de bussiness ou layer). Por fim, layer objects são classes que conectam as pontas (ou componentes).

Arquitetura orientada a BOLOVO, ou programação procedural, é um forte fator para criação de Big Ball of Mud.

Muitas pessoas (principalmente no Brasil) apresentam a arquitetura BOLOVO com forma de implantar o Domain-Driven Design, o que não passa de vigarice.
É comum o Domain Layer virar Value Objects, Application Layer virar Bussiness Objects, e outras camandas Layer Objects.

Uma outra forma falsa de apresentar a implementação de uma arquitetura para DDD é fazendo um de-para de uma antiga arquitetura utilizado em aplicativos Windows Forms onde as camadas eram divididas em Presenter Layer, Bussiness Login Layer (BLL) e Data Access Layer (DAL). BLL vira Application Layer e DAL é dividida em Domain Layer e Infra. Esta arquitetura veio do VB para .Net e também foi levada ao Asp.Net. Como a BOLOVO, ela tende ao desenvolvimento procedural e a criação de Big Ball of Mud.

* O que é BOLOVO - Slides - Article
<br/> https://pt.slideshare.net/MayogaX/bolovo-no-use-por-a
<br/> https://www.slideshare.net/pcalcado/in-portuguese-arquitetura-java-em-2007
<br/> https://www.alura.com.br/artigos/o-que-e-modelo-anemico-e-por-que-fugir-dele
<br/> https://www.alura.com.br/artigos/nao-aprender-oo-getters-e-setters
<br/> http://blog.caelum.com.br/nao-aprender-oo-getters-e-setters/

* Alistair Cockburn - Hexagonal Architecture - Blog 
<br/> https://alistair.cockburn.us/hexagonal-architecture/

* DDD, Hexagonal, Onion, Clean, CQRS, … How I put it all together - Blog 
<br/> https://herbertograca.com/2017/11/16/explicit-architecture-01-ddd-hexagonal-onion-clean-cqrs-how-i-put-it-all-together/

* Reflecting architecture and domain in code
<br/> https://herbertograca.com/2019/06/05/reflecting-architecture-and-domain-in-code/

* Arquitetura Gritante
<br/> https://blog.dyegomaas.com.br/posts/artigo-arquitetura-gritante/

* Arquitetura Gritante com MediatR
<br/> https://blog.dyegomaas.com.br/posts/artigo-arquitetura-gritante-com-mediatr/

* Ian Cooper - Conference - Decoupling from ASP.NET - Hexagonal Architectures in .NET
<br/> https://skillsmatter.com/skillscasts/5744-decoupling-from-asp-net-hexagonal-architectures-in-net

* Phil Calçado - How to write a Repository - Blog
<br/> https://philcalcado.com/2010/12/23/how_to_write_a_repository.html

* Phil Calçado - Pattern: Using Pseudo-URIs with Microservices - Blog
<br/> https://philcalcado.com/2017/03/22/pattern_using_seudo-uris_with_microservices.html

* Cinco coisas que todo desenvolvedor de software deve saber sobre Arquitetura de Software - Blog
<br/> https://www.infoq.com/br/articles/architecture-five-things/?itm_source=infoq&itm_campaign=user_page&itm_medium=link

* O Papel do Arquiteto de Solução - Blog
<br/> https://www.infoq.com/br/articles/papel-arquiteto-solucao/?itm_source=infoq&itm_campaign=user_page&itm_medium=link

* Arquitetura “gritante” e a organização do código-fonte - Blog
<br/> https://robsoncastilho.com.br/2020/07/25/arquitetura-gritante-e-a-organizacao-do-codigo-fonte/

* Enterprise Integration Patterns - Blog
<br/> https://www.enterpriseintegrationpatterns.com/index.html

* SOFTWARE DELIVERY PROCESS - Blog
<br/> https://www.goeleven.com/guides/software-delivery-process/?utm_source=substack&utm_medium=email

* Clean Architecture with ASP.NET Core 3.0 - Jason Taylor - NDC Sydney 2019
<br/>https://www.youtube.com/watch?v=5OtUm1BLmG0




## Domain Driven Design ##

* Eric Evans — Tackling Complexity in the Heart of Software - YouTube
<br/> https://www.youtube.com/watch?v=dnUFEg68ESM

* DDD and Microservices: At Last, Some Boundaries! - YouTube
<br/> https://www.youtube.com/watch?v=sFCgXH7DwxM

* Eric Evans - Good Design is Imperfect Design - YouTube
<br/> https://www.youtube.com/watch?v=lY54TmmEllY

* Modelling Time - Eric Evans - DDD Europe 2018 - YouTube
<br/> https://www.youtube.com/watch?v=T29WzvaPNc8

* Language in Context - Eric Evans - DDD Europe 2019 - YouTube
<br/> https://www.youtube.com/watch?v=xyuKx5HsGK8&list=PLf9p-N3ltMTuuYk1zpsjB-D-6pxPkGvwj

* Bounded Contexts - Eric Evans - DDD Europe 2020 - YouTube
<br/> https://www.youtube.com/watch?v=am-HXycfalo&list=PLf9p-N3ltMTvfEj8KNtOomc9algcX0WtG

* Q&A - Eric Evans & Cyrille Martraire - DDD Europe 2021 - YouTube
<br/> https://www.youtube.com/watch?v=MWhs97tUvvw&list=PLf9p-N3ltMTsGX65ZJfnZ5wz8L_FUke-d&index=2

* Practical DDD: Bounded Contexts + Events => Microservices - Podcast
<br/> https://www.infoq.com/presentations/microservices-ddd-bounded-contexts/?itm_source=infoq&itm_campaign=user_page&itm_medium=link

* Definindo Bounded Contexts — Eric Evans durante o DDD Europa - Blog
<br/> https://www.infoq.com/br/news/2019/07/bounded-context-eric-evans/?itm_source=infoq&itm_campaign=user_page&itm_medium=link

* Vaughn Vernon - Domain-Driven Design Europe 2016 - YouTube
<br/> https://www.youtube.com/watch?v=uJ_eyV0JfzE&list=PLVOVVQcwppnF19weqiHCsVW4kS6e1QHCt&index=14

* Vaughn Vernon - Reactive DDD Modeling Uncertainty - YouTube
<br/> https://www.youtube.com/watch?v=F63mKjYnF4M&list=PLVOVVQcwppnF19weqiHCsVW4kS6e1QHCt&index=12

* Vaughn Vernon - How to Use Aggregates for Tactical Design - YouTube
<br/> https://www.youtube.com/watch?v=Xf_aLAK1RfE&list=PLVOVVQcwppnF19weqiHCsVW4kS6e1QHCt&index=5

* Eric Evans - Keynote: DDD Isn't Done: A Skeptical, Optimistic, Pragmatic Look - YouTube
<br/> https://www.youtube.com/watch?v=R2IAgnpkBck

* Strengthening your domain: a primer - Blog
<br/> https://lostechies.com/jimmybogard/2010/02/04/strengthening-your-domain-a-primer/

* DDD Crew - GitHub - Article
<br/> https://github.com/ddd-crew






## Event Driven Architecture ##

* 11 erros comuns em arquiteturas orientadas a eventos e como evitá-los
<br/> https://www.infoq.com/br/articles/11-erros-eda-como-evitar/?itm_source=infoq&itm_campaign=user_page&itm_medium=link

* Pentaho Data Integration - ETL em Software Livre
<br/> https://www.infoq.com/br/articles/pentaho-pdi/?itm_source=infoq&itm_campaign=user_page&itm_medium=link

* Criando uma arquitetura para ingestão de dados com ksqlDB, Schema Registry e Kafka Connect
<br/> https://www.infoq.com/br/articles/apache-kafka-ksqldb/?itm_source=infoq&itm_campaign=user_page&itm_medium=link






## CQS e CQRS ##

* Command Query Separation (CQS) - A simple but powerful pattern - Blog
<br/> https://www.dotnetcurry.com/patterns-practices/1461/command-query-separation-cqs

* Apply CQRS and CQS approaches in a DDD microservice in eShopOnContainers - Blog
<br/> https://learn.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/eshoponcontainers-cqrs-ddd-microservice

* Assinando eventos
<br/> https://learn.microsoft.com/pt-br/dotnet/architecture/microservices/multi-container-microservice-net-applications/subscribe-events

* A Saga on Sagas 
<br/> https://learn.microsoft.com/pt-br/previous-versions/msp-n-p/jj591569(v=pandp.10)

* CQRS facts and myths explained
<br/> https://event-driven.io/en/cqrs_facts_and_myths_explained/?utm_source=substack&utm_medium=email

* CQRS Journey
<br/> https://learn.microsoft.com/pt-br/previous-versions/msp-n-p/jj554200(v=pandp.10)





