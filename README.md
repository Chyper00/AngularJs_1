# Introdução Angular JS

https://angularjs.org/

Download Atom -> https://atom.io/<br>
Download Sublime Text3 -> https://www.sublimetext.com/3<br>
Download Xampp -> https://www.apachefriends.org/pt_br/download.html
<hr> 
<center>
<img src = "https://media.learncafe.co/courses/17679_0.jpg" width="600px">
</center>


<strong>Entendendo o framework</strong>

<p>O angulars é um framework javascript criado pelo Miško Hevery e Adam Abrons, atualmente a ferramenta é mantida pela Google.
O angular segue os padrões MVC/MVVM/MVP/MVW e usa o conceito de SPA (Single Page Application).</p>


<strong>MVC? MVVM? MVP? MVW?</strong>
<center>
<img src="https://pbs.twimg.com/media/DMdhkyfV4AA6521.jpg" width="300px">
</center>  

<strong>MVC</strong>
<p>MVC ou Model View Controller é nada mais que um padrão de arquitetura de software, que separa as aplicações em 3 camadas. A camada de interação do usuário(view), a camada de manipulação dos dados(model) e a camada de controle(controller).</p>

<strong>MVVM</strong>
<p>O Model View View Model assemelha-se em alguns aspectos ao MVC e ao MVP (Model View Presenter). O MVVM é uma especialização do MVP adaptado para a arquitetura do WPF E Silverlight. Conceitualmente, o MVVM e o MVP são idênticos, o que os diferencia é que o MVVM é específico para a arquitetura do WPF e Silverlight e o MVP é independente de plataforma.</p>

<strong>MVP</strong>
<p>No MVP a camada Presenter assume a função de mediadora (executada pelo Controller em MVC). Além disso, a View é responsável por manipular os eventos UI, que era o trabalho do Controller. Model se torna estritamente um modelo de domínio.</p>

<strong>MVW</strong>
<p>O MVW significa Model View Whatever, ou seja, tanto faz qual padrão você acha que vai programar em angularjs, pare de perder tempo com isso, apenas faça.</p>


<img src ="http://i0.kym-cdn.com/photos/images/newsfeed/000/840/284/995">

<p>Após toda essa sopinha de letras, o que realmente importa para nós é o padrão MVC, que é conhecido pela maioria dos desenvolvedores e adotado pela maioria dos frameworks.</p><br>


<img src="https://cdn-images-1.medium.com/max/800/1*0rb6xMqFKDTbYvB5jAooNA.gif">


<p>No padrão MVC, temos uma clara separação de responsabilidades, onde, o controller tem como função manipular os dados que se encontram no model e que vão ser representado na view que é uma espécie de ‘espelho’ para os models, tudo isso graças ao two way binding.</p>

<p>No two-way data binding, as alterações na view são refletidas na fonte de dados e atualizações na fonte refletem na view sem a necessidade de manipulação explícita do DOM, facilitando e muito a nossa vida com isso.</p>

<p>Single Page Application
SPA ou (Single Page Application) é uma forma de desenvolvermos uma aplicação inteira apenas em uma página. WTF? Sim, apenas em uma página.</p>

<p>Com SPA, conseguimos criar um esquema de rotas, que quando solicitadas, atualizam apenas partes da página, mantendo sempre a mesma base. Em resumo, em aplicações SPA apenas parte da view precisa ser alterada, mantendo-se todo o restante intacto, melhorando com isso a experiência de usuário e diminuindo o tráfego de requisições.</p>

<p>Conclusão
Como visto anteriormente, o angularjs é um framework javascript que visa facilitar a criação de SPA’s, possibilitando um desenvolvimento rápido e eficiente. Atualmente ele se encontra na versão 1.5.x, mas a versão 2 já se encontra disponível e totalmente reformulada.</p>


texto por <a href ="https://medium.com/@hudsonbrendon?source=post_header_lockup">Hudson Brendon</a>
fonte : https://medium.com/@hudsonbrendon/angularjs-series-entendendo-o-framework-1499a841d51f 
