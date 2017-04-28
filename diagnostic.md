# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
The back-end or  "server-side", is essential to a functioning site and controls updates and changes. Essentially everything the user can't see in the browser such as databases and servers.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
Model
```

Which layer in the MVC pattern communicates with the model?

```md
The controller
```

Why don't we use views in our interpretation of the MVC pattern?

```md
I am not sure, here
```

What does C.R.U.D stand for?

```md
CREATE, READ, UPDATE, DESTROY
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
During just about all of it! The client server and controller are all using a GET
request to retrieve data from the model. When a client modifies something, they are using a PATCH reques. There are other similarities, as well.
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
Index, Read, Create, Update, Destroy
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
- client requests data
- server receives request
- server queries the applicable controller
- controller queries the model
- model checks if the data exists and if so gives it back to controller
- the controller than send the info back to the server
- the server than the requested person to the client
```

What is the command to generate a new rails-api app?

```bash
I am not sure on this one...
```

What is the command to start an instance of a rails server?

```bash
bundele/exec rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
// your response here
-bin/rails db: create
-bin/rails db: drop
-bin/rails db: migrate
-bin/rails db: seed

```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
rails-api g scaffold pet name:string

```
