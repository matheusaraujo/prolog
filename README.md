# Prolog Dev Container

This project sets up a **Prolog** development environment inside a **VSCode Dev Container**, using **SWI-Prolog** on **Alpine Linux**.

## How to Use

1. Open this project in **VSCode**.
2. When prompted, select **"Reopen in Container"** to start the dev container.
3. To run the Prolog interpreter, use the following command:

```bash
swipl
```

4. To load and run a Prolog program (e.g., `hello-world.pl`):

```prolog
?- ['hello-world.pl'].
?- hello_world.
```
