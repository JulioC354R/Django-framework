# Curso completo de Django

Seção 1: Introdução

Apenas uma seção introdutória ao curso.

Seção 2: Ambiente de desenvolvimento no macOS, Linux Ubuntu e Windows para Python

Nessa seção vou mostrar como criar o seu ambiente de desenvolvimento Python 3.10 nos sistemas macOS Monterey, Windows 11 e Linux Ubuntu.

Seção 3: Configurações do Visual Studio Code VS Code e ambiente virtual venv

Aqui vamos aprender a configurar o Visual Studio Code VS Code para que ele nos ajude a ter mais produtividade ao trabalhar com Python e Django. Também vamos aprender a usar o venv para criação e utilização de ambientes virtuais com Python.

Seção 4: Ambiente Django e Git e Github com chaves SSH (Iniciando o primeiro projeto)

Essa é a seção que vamos aprender a criar o nosso primeiro projeto Django com venv para ambiente virtual, configurar chaves SSH, o git e o github. Assim seu projeto já poderá entrar para seu portfólio para mostrar para possíveis contratantes dos seus serviços. Isso é super útil para entrar no mercado de trabalho.

Seção 5: Django URLs, Views e Templates

Nessa seção vamos conhecer o URLConf, geralmente urls py, do Django para adicionar URLs na nossa aplicação. Vamos trabalhar com as views, que são similares a controllers na arquitetura MVC, e os templates (que são similares às views na arquitetura MVC) do padrão MTV exclusivo do Django. Costumamos comparar a arquitetura exclusiva do Django (MTV - Model, template, view) com a famosa arquitetura MVC existente no mercado. Não se preocupe, você não precisa ter nenhum conhecimento prévio para entender isso.

Seção 6: Django Staticfiles: Arquivos estáticos, imagens, css e javascript

Essa é a seção que vamos aprender a configurar o servidor de arquivos estáticos do Django. Também vamos conhecer alguns comandos usados para gerenciar esses arquivos, como collectstatic e demais. Arquivos estáticos são arquivos que são geralmente servidos diretamente pelo nosso servidor, sem ter algum processamento adicional. Geralmente são imagens, CSS, JavaScript, vídeos e mais.

Seção 7: Django Templates: herança, blocos, if, for e mais

Nessa seção vamos usar todo o poder das templatetags e filters do Django Templates, além de usar recursos de programação dentro dos nossos templates HTML. O Django permite usar lógica dentro do template HTML, com isso é possível executar loops, condicionais e lógica de programação diretamente na página que o usuário vê. Como vamos ver no curso, isso não é recomendável, mas em alguns casos é muito útil.

Seção 8: Django Models e ORM (Object Relational Mapper)

Vamos conhecer os Models e o ORM (Object Relational Mapper) do Django para salvar nossos dados com segurança em bases de dados SQL. Aqui é onde se encontra a maior força do Django. Ele consegue fazer algumas mágicas maravilhosas para ligar seu código com os dados da base de dados.

Seção 9: Djanto testing - Introdução aos testes unitários no Django com Pytest e Unittest

Nessa seção vamos fazer uma introdução aos testes unitários no Django usando o VS Code, Pytest, Unittest e Djanto Test. Testar sua aplicação é extremamente importante, isso agiliza o desenvolvimento, evita os bugs, evita regressões e muito mais.

Seção 10: Usando request.GET no Django e Introdução ao TDD (Test Driven Development)

Vamos aprender a obter valores de request.GET para usar dentro do nosso sistema com Django. Também veremos uma Introdução ao TDD (Test Driven Development) para desenvolvimento guiado por testes.

Vamos entender URL Query Strings e como trabalhar com esses valores com segurança.

Seção 11: Django Pagination - Paginação de QuerySet com Django Paginator

Nessa seção vamos aprender a criar paginação usando o Django Paginator. O mais legal é que tudo aqui será feito manualmente por nós. Não vamos usar nenhuma lib além do Django e o nosso próprio código para montar uma lógica de paginação.

Seção 12: Django Messages - Enviando flash messages para o usuário

O Django tem o Django Messages que pode ser usado para exibir mensagens na tela do usuário com sucesso, erro, informações, debug e mais. Vamos aprender a usar essas flash messages nessa seção.

Seção 13: Django Forms - Criando formulários soltos ou baseados em Models

Nessa seção vamos aprender a criar formulários usando Django Forms. Usaremos formulários soltos com forms.Form e atrelados ao model com forms.ModelForm. Outra mágica impressionante do Django.

Seção 14: Testes funcionais com Selenium e chromedriver

Vamos aprender a escrever testes funcionais usando o selenium e o chromedriver. Os testes funcionais são similares ao que o próprio usuário faria no seu sistema, ou seja, são testes reais da aplicação. Nesses testes, nós abrimos o navegador, procuramos algo na página, clicamos ou escrevemos algo, executamos o conteúdo e verificamos se o que era esperado ocorreu. Isso é feito de maneira automatizada, então mais um ponto para a praticidade que é trabalhar com o Python, Django e Selenium.

Seção 15: Criando a dashboard do autor de conteúdo (área administrativa)

Nessa seção vamos criar uma área administrativa para que o usuário possa manipular dados na nossa aplicação. Com isso podemos permitir que ele tenha controle total sobre os seus dados. Como dados pessoais e posts que tenha criado em nosso sistema. Essa área administrativa é diferente da área admin que vem por padrão no Django, porque ela nos dará muito mais controle sobre o que o usuário poderá manipular.

Seção 16: Class Based Views (CBV) - Usando classes para views no Django

Nessa seção vamos entender como funcionam as Class Based Views (CBV). Elas são uma forma de se trabalhar com objetos Python ao invés de funções dentro das views do Django. Ela não foram criadas para substituir as funções (Function Based Views - FBV), mas trazem algumas melhorias e facilidades para nosso projeto Django.

Seção 17: Deploy da aplicação em um servidor real na Internet

Aqui vamos fazer deploy da aplicação, ou seja, vamos enviar a aplicação para um servidor real, com postgreSQL, ssh, ssl, git, e muitas outras coisas profissionais.

Seção 18: Class Based Views (CBV) com JSONResponse

A essa altura do campeonato, muitas pessoas já adicionariam o DRF (Django Rest Framework) em sua aplicação. Apesar de isso ser super válido e até recomendável, vamos ver como usar JsonResponse para responder via JSON em nossas CBVs. Usaremos o método render_to_response das class based views correspondentes para alterar a forma como os dados são entregues para as aplicações clientes.

Seção 19: Desempenho e Django Debug Toolbar

Fazer aplicações Django pode ser bem simples para quem conhece o framework. Porém, fazer com que o framework perca seu desempenho por erros do desenvolvedor também é extremamente simples. Nessa seção vamos falar de uma lib aliada do desenvolvedor Django, que é a Django Debug Toolbar. É basicamente uma barra de ferramentas que mostra todas as consultas realizadas na base de dados, os templates renderizados e muito mais.

Seção 20: Miscelânea: ORM e Models, Managers, QuerySets, settings, init e mais

Nessa seção vamos ver mais detalhes sobre o ORM, Models, os Managers, as QuerySets, o arquivo settings, os arquivos de init, os Python packages e muito mais. Você vai refinar seu conhecimento em muitas das coisas que vimos em seções anteriores.

Seção 21: Criando um menu com template Django, HTML, CSS e JS para autores

Nessa seção vamos criar um menu com lógica para usuários autenticados e não autenticados. Vamos usar template do Django, HTML, CSS e JavaScript para atingir nosso objetivo.

Seção 22: Criando relações com o User Model do Django

Nessa seção vamos entender como criar relações com o User Model do Django para relacionar coisas como perfis de usuário, compras, fotos, produtos, posts e qualquer outro tipo de dado.

Seção 23: Tradução de um projeto Django (Localização e Internacionalização)

Nessa seção vamos entender e aprender a fazer com que o nosso projeto Django apareça em idiomas diferentes de acordo com o idioma do computador do usuário ou sua localização. Também faremos a tradução de alguns textos para praticar.

Seção 24: Trabalhando com arquivos e imagens no Django

Vamos aprender a trabalhar com arquivos e imagens no Django. Principalmente, vamos redimensionar imagens e também apagar imagens antigas nas atualizações dos posts.

Seção 25: Django Rest Framework - Criando uma API (Application Programming Interface)

Nessa seção vamos aprender a criar uma API (Application Programming Interface) usando o Django Rest Framework.

Seção 26: Django Rest Framework - Class Based Views, JWT, Routers, ViewSets, Paginação e mais

Agora que já conhecemos os serializers do Django Rest Framework e as FBV (function based views), vamos ver novos conceitos, como: CBV (Class Based Views), paginação, autenticação com JWT, ViewSets, Routers e mais.

Seção 27: Django Rest Framework - Escrevendo Testes Unitários Automatizados

Nessa seção vamos aprender a escrever testes unitários automatizados para o Django Rest Framework (DRF). Assim nós conseguiremos evoluir o código e a API RESTful com segurança e sem regressões de código.

Seção 28: CORS - Cross-Origin Resource Sharing no Django Rest Framework

Nessa seção vamos entender o que é CORS - Cross-Origin Resource Sharing no Django Rest Framework. Vamos entender como aplicar esse recurso de segurança na prática em nossa API RESTful.

Extra 1: Bases de dados Relacionais - SQL - MySQL ou MariaDB

Seção extra e introdutória sobre Bases de dados Relacionais - SQL com MySQL ou MariaDB. Recomendável entender sobre banco de dados relacional para trabalhar com o ORM do Django (Models).

Extra 2: Entenda o HTML5 e o CSS3 (Para iniciantes)

Quem vai trabalhar com desenvolvimento web, seja com Django ou outro framework, precisa entender HTML e CSS. Essa é uma seção de introdução do HTML na versão 5 e CSS na versão 3.

Extra 3: Criando uma Landing Page com HTML5 e CSS3

Para dar sequência na seção anterior, vamos criar uma Landing Page usando HTML e CSS. Aprenderemos mais algumas coisas relacionadas que serão de extrema importância na sua carreira.

Extra 4: Comandos Linux, Unix, Mac e Windows WSL2 mais usados no terminal

Aprenda comandos básicos Linux/Unix para navegador no terminal. Essa seção poderá ser seguida usando Windows, Linux ou Mac. Vamos aprender pwd, ls, cd, caminhos absolutos e relativos, e muitos mais. Isso é importante para aprender a trabalhar com servidores web em sistema Linux ou Unix.
