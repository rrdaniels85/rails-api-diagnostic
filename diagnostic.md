# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
The back end manages, saves and stores information in a database for the app which can be accessed by users at any given time.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
Model
```

Which layer in the MVC pattern communicates with the model?

```md
Controller
```

Why don't we use views in our interpretation of the MVC pattern?

```md
We have serializers that replace all the views needed for our apps.
```

What does C.R.U.D stand for?

```md
Create, Read, Update, Destroy
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
Model
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
POST, GET, PATCH, PUT, DELETE
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
1) The request is received by the server/router.
2) It is then routed to the correct controller.
3) The controller then contacts the model and gives it the request.
4) The model interacts with the database and attempts to complete the required request.
5) A response is then sent back to the front end and client in the form of JSON.
```

What is the command to generate a new rails-api app?

```bash
rails new [app name here]
```

What is the command to start an instance of a rails server?

```bash
rails server
or...
bundle exec rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
1) bin/rake db:drop
2) bin/rake db:create
3) bin/rake db:migrate
4) bin/rake db:seed
5) bin/rake db:examples
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
bin/rails generate scaffold pet name:string age:integer
```
