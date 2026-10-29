# Java Labs

Three standalone Java console exercises focused on object-oriented programming. The project directories and user-facing prompts retain their original Turkish names and learning context.

## Projects

| Directory | Exercise |
| --- | --- |
| [`Çalışan Yönetim Sistemi/`](<Çalışan Yönetim Sistemi/>) | Employee management with inheritance, abstract classes, interfaces, and role-specific employees |
| [`Kitap otomasyon sistemi/`](<Kitap otomasyon sistemi/>) | Library inventory, borrowing, and returns |
| [`Ürün alım-satım sistemi/`](<Ürün alım-satım sistemi/>) | Products, stock, a shopping cart, and a sample user workflow |

Each directory is an independent default-package application with its own `Main.java` entry point.

## Compile and run

Use JDK 17 or newer. From inside one project directory:

```bash
mkdir build
javac -encoding UTF-8 -d build *.java
java -cp build Main
```

Repeat the commands separately for each project. The applications are interactive and read choices from the terminal.

## Repository hygiene

Compiled `.class` files and IDE output directories are intentionally excluded. Build the exercises locally from source rather than committing generated output.

The users, employees, books, and products initialized by the examples are fictional demo data. These exercises are learning projects rather than production management or commerce systems.
