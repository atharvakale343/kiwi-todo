# Todo App built with Rocket

This repository is a fork of a basic Todo app from [Rocket Examples](https://github.com/SergioBenitez/Rocket/tree/master/examples/todo)

[View the App Website](http://kiwi-todo.herokuapp.com/)

# Develop Locally

In Bash:
```bash
brew install libpq && brew link --force libpq

echo DATABASE_URL=<a local or remote postgres URI> $'\n'ROCKET_DATABASES="{postgres_database={url=\"${DATABASE_URL}\", pool_size=1, timeout=20}}" > .env

cargo run
```
