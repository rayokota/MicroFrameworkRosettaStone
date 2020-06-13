# The Micro-Framework Rosetta Stone

With all the micro-frameworks that are available for web development, how does one choose?  The code generators below will allow you to create the exact same database-backed web application using several different micro-frameworks.  As micro-frameworks are ideal for providing RESTful web services to single-page applications, each generated web application uses the same [AngularJS](http://angularjs.org/) front-end.  Hopefully this will give you an idea what it is like to develop with each micro-framework.

Language | Micro-Framework | ORM | Code Generator
--- | --- | --- | ---
C# | [Nancy](http://nancyfx.org/) | [NHibernate](http://nhibernate.info) or [ORMLite](https://github.com/ServiceStack/ServiceStack.OrmLite) | https://github.com/rayokota/generator-angular-nancy
Clojure | [Luminus](http://www.luminusweb.net) | [Korma](https://github.com/korma/Korma) | https://github.com/rayokota/generator-angular-luminus
Common Lisp | [Caveman2](http://8arrow.org/caveman/) | [Integral](https://github.com/fukamachi/integral) or [Postmodern](http://marijnhaverbeke.nl/postmodern/) | https://github.com/rayokota/generator-angular-caveman2
Dart | [Start](https://github.com/lvivski/start) | [Dart ORM](https://github.com/ustims/DartORM) | https://github.com/rayokota/generator-angular-start
Elixir | [Dynamo](https://github.com/dynamo/dynamo) | [Ecto](https://github.com/elixir-lang/ecto) | https://github.com/rayokota/generator-angular-dynamo
Erlang | [Axiom](https://github.com/tsujigiri/axiom) | [SumoDB](https://github.com/inaka/sumo_db) | https://github.com/rayokota/generator-angular-axiom
F# | [Suave](http://suave.io/) | [ORMLite](https://github.com/ServiceStack/ServiceStack.OrmLite) | https://github.com/rayokota/generator-angular-suave
Frege | [Chinook](https://github.com/fregelab/chinook) | [Sirocco](https://github.com/fregelab/sirocco) | https://github.com/rayokota/generator-angular-chinook
Go | [Martini](https://github.com/go-martini/martini) | [Gorp](https://github.com/coopernurse/gorp) | https://github.com/rayokota/generator-angular-go-martini
Groovy | [Ratpack](http://www.ratpack.io/) | [GORM](https://gorm.grails.org) | https://github.com/rayokota/generator-angular-ratpack
Haskell | [Scotty](http://hackage.haskell.org/package/scotty) | [Persistent](http://hackage.haskell.org/package/persistent) | https://github.com/rayokota/generator-angular-scotty
Java | [Dropwizard](http://www.dropwizard.io) | [Hibernate](http://hibernate.org/orm) | https://github.com/rayokota/generator-angular-dropwizard
Java 8 | [Spark](http://sparkjava.com/) | [Hibernate](http://hibernate.org/orm) | https://github.com/rayokota/generator-angular-spark
Javascript | [Express.js](http://expressjs.com) | [Sequelize](http://sequelizejs.com) | https://github.com/rayokota/generator-angular-express-sequelize
Lua | [Orbit](http://keplerproject.github.io/orbit/) | [Orbit ORM](http://keplerproject.github.io/orbit/reference.html) | https://github.com/rayokota/generator-angular-orbit
OCaml | [Opium](https://github.com/rgrinberg/opium) | [Mirage ORM](https://github.com/mirage/orm) | https://github.com/rayokota/generator-angular-opium
Perl | [Mojolicious](http://mojolicio.us) | [DBIx::Class](http://search.cpan.org/perldoc?DBIx::Class) | https://github.com/rayokota/generator-angular-mojolicious
PHP | [Slim](http://www.slimframework.com/) | [Eloquent ORM](http://laravel.com/docs/eloquent) | https://github.com/rayokota/generator-angular-slim
Python | [Flask](http://flask.pocoo.org/) | [SQLAlchemy](http://www.sqlalchemy.org) | https://github.com/rayokota/generator-angular-flask
Racket | [Spin](https://github.com/dmac/spin) | [Racquel](https://github.com/brown131/racquel) | https://github.com/rayokota/generator-angular-spin
Ruby | [Sinatra](http://www.sinatrarb.com/) | [ActiveRecord](https://github.com/rails/rails/tree/master/activerecord) or [DataMapper](http://datamapper.org) | https://github.com/rayokota/generator-angular-sinatra
Rust | [Nickel](http://nickel-org.github.io) | [Diesel](https://github.com/sgrif/diesel) | https://github.com/rayokota/generator-angular-nickel
Scala | [Scalatra](http://scalatra.org) | [Squeryl](http://squeryl.org) | https://github.com/rayokota/generator-angular-scalatra
Swift | [Kitura](http://www.kitura.io) | [Fluent](https://github.com/vapor/fluent) | https://github.com/rayokota/generator-angular-kitura

