# Todo App built with Rocket

This repository is a fork of a basic Todo app from [Rocket Examples](https://github.com/SergioBenitez/Rocket/tree/master/examples/todo)

[View the App Website](http://kiwi-todo.herokuapp.com/)

# Develop Locally

This example makes use of a SQLite database via `diesel` to store todo tasks. As
a result, you'll need to have `sqlite3` and its headers installed:

  * **OS X:** `brew install sqlite`
  * **Debian/Ubuntu:** `apt-get install libsqlite3-dev`
  * **Arch:** `pacman -S sqlite`

followed by:
```bash
cargo run
```
