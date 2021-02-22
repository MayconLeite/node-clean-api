<p>Essa API faz parte do treinamento do professor Rodrigo Manguinho (Mango) na Udemy.</p>
<p>O objetivo do treinamento é mostrar como criar uma API com uma arquitetura bem definida e desacoplada, utilizando TDD (programação orientada a testes) como metodologia de trabalho, Clean Architecture para fazer a distribuição de responsabilidades em camadas, sempre seguindo os princípios do SOLID e, sempre que possível, aplicando Design Patterns para resolver alguns problemas comuns.</p>
<h2><a id="user-content-link-para-a-documentação-da-api" class="anchor" aria-hidden="true" href="#link-para-a-documentação-da-api"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><a href="http://fordevs.herokuapp.com/api-docs" rel="nofollow"><strong>Link para a documentação da API</strong></a></h2>

<blockquote>
<h2><a id="user-content-princípios" class="anchor" aria-hidden="true" href="#princípios"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Princípios</h2>
</blockquote>
<ul>
<li>Single Responsibility Principle (SRP)</li>
<li>Open Closed Principle (OCP)</li>
<li>Liskov Substitution Principle (LSP)</li>
<li>Interface Segregation Principle (ISP)</li>
<li>Dependency Inversion Principle (DIP)</li>
<li>Separation of Concerns (SOC)</li>
<li>Don't Repeat Yourself (DRY)</li>
<li>You Aren't Gonna Need It (YAGNI)</li>
<li>Keep It Simple, Silly (KISS)</li>
<li>Composition Over Inheritance</li>
<li>Small Commits</li>
</ul>
<blockquote>
<h2><a id="user-content-design-patterns" class="anchor" aria-hidden="true" href="#design-patterns"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Design Patterns</h2>
</blockquote>
<ul>
<li>Factory</li>
<li>Adapter</li>
<li>Composite</li>
<li>Decorator</li>
<li>Proxy</li>
<li>Dependency Injection</li>
<li>Abstract Server</li>
<li>Composition Root</li>
<li>Builder</li>
<li>Singleton</li>
</ul>
<blockquote>
<h2><a id="user-content-metodologias-e-designs" class="anchor" aria-hidden="true" href="#metodologias-e-designs"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Metodologias e Designs</h2>
</blockquote>
<ul>
<li>TDD</li>
<li>Clean Architecture</li>
<li>DDD</li>
<li>Conventional Commits</li>
<li>GitFlow</li>
<li>Modular Design</li>
<li>Dependency Diagrams</li>
<li>Use Cases</li>
<li>Continuous Integration</li>
<li>Continuous Delivery</li>
<li>Continuous Deployment</li>
</ul>
<blockquote>
<h2><a id="user-content-bibliotecas-e-ferramentas" class="anchor" aria-hidden="true" href="#bibliotecas-e-ferramentas"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Bibliotecas e Ferramentas</h2>
</blockquote>
<ul>
<li>NPM</li>
<li>Typescript</li>
<li>Git</li>
<li>Docker</li>
<li>Jest</li>
<li>MongoDb</li>
<li>Travis CI</li>
<li>Swagger</li>
<li>Bcrypt</li>
<li>JsonWebToken</li>
<li>Faker</li>
<li>Coveralls</li>
<li>Validator</li>
<li>Express</li>
<li>Apollo Server Express</li>
<li>Graphql</li>
<li>Graphql ISO Date</li>
<li>Supertest</li>
<li>Husky</li>
<li>Lint Staged</li>
<li>Eslint</li>
<li>Standard Javascript Style</li>
<li>Sucrase</li>
<li>Nodemon</li>
<li>Rimraf</li>
<li>In-Memory MongoDb Server</li>
<li>MockDate</li>
<li>Module-Alias</li>
<li>Copyfiles</li>
<li>Npm Check</li>
<li>Bson ObjectId</li>
<li>Apollo Server Integration Testing</li>
</ul>
<blockquote>
<h2><a id="user-content-features-do-node" class="anchor" aria-hidden="true" href="#features-do-node"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Features do Node</h2>
</blockquote>
<ul>
<li>Documentação de API com Swagger</li>
<li>API Rest com Express</li>
<li>GraphQL com Apollo Server</li>
<li>Log de Erro</li>
<li>Segurança (Hashing, Encryption e Encoding)</li>
<li>CORS</li>
<li>Middlewares</li>
<li>Nível de Acesso nas Rotas (Admin, User e Anônimo)</li>
<li>Deploy no Heroku</li>
<li>Servir Arquivos Estáticos</li>
</ul>
<blockquote>
<h2><a id="user-content-features-do-graphql" class="anchor" aria-hidden="true" href="#features-do-graphql"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Features do GraphQL</h2>
</blockquote>
<ul>
<li>Types</li>
<li>Queries</li>
<li>Mutations</li>
<li>Resolvers</li>
<li>Directives</li>
<li>Scalars</li>
<li>Plugins</li>
</ul>
<blockquote>
<h2><a id="user-content-features-do-git" class="anchor" aria-hidden="true" href="#features-do-git"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Features do Git</h2>
</blockquote>
<ul>
<li>Alias</li>
<li>Log Personalizado</li>
<li>Branch</li>
<li>Reset</li>
<li>Amend</li>
<li>Tag</li>
<li>Stash</li>
<li>Rebase</li>
<li>Merge</li>
</ul>
<blockquote>
<h2><a id="user-content-features-do-typescript" class="anchor" aria-hidden="true" href="#features-do-typescript"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Features do Typescript</h2>
</blockquote>
<ul>
<li>POO Avançado</li>
<li>Interface</li>
<li>TypeAlias</li>
<li>Namespace</li>
<li>Utility Types</li>
<li>Modularização de Paths</li>
<li>Configurações</li>
<li>Build</li>
<li>Deploy</li>
<li>Uso de Breakpoints</li>
</ul>
<blockquote>
<h2><a id="user-content-features-de-testes" class="anchor" aria-hidden="true" href="#features-de-testes"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Features de Testes</h2>
</blockquote>
<ul>
<li>Testes Unitários</li>
<li>Testes de Integração (API Rest &amp; GraphQL)</li>
<li>Cobertura de Testes</li>
<li>Test Doubles</li>
<li>Mocks</li>
<li>Stubs</li>
<li>Spies</li>
<li>Fakes</li>
</ul>
<blockquote>
<h2><a id="user-content-features-do-mongodb" class="anchor" aria-hidden="true" href="#features-do-mongodb"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a>Features do MongoDb</h2>
</blockquote>
<ul>
<li>Connect e Reconnect</li>
<li>Collections</li>
<li>InsertOne e InserMany</li>
<li>Find, FindOne e FindOneAndUpdate</li>
<li>DeleteMany</li>
<li>UpdateOne</li>
<li>Aggregation (Match, Group, Unwind, Lookup, AddFields, Project, Sort)</li>
<li>ObjectId</li>
<li>Upsert e ReturnOriginal</li>
<li>Push, Divide, Multiply, ArrayElemAt, Cond, Sum</li>
<li>Filter, Map, Reduce, MergeObjects, ConcatArrays</li>
</ul>
</article>
      </div>
  </div>
