# Borderless-AI

## Getting started

### First setup

1. Clone the repository:

    ```sh
    gh repo clone deAdler-alt/Borderless-AI
    ```

2. Navigate to the project directory:

    ```sh
    cd ChatKNML-main
    ```

3. Create a new branch for your development work:

    ```sh
    git checkout -b {your_branch_name}
    ```

4. Make sure you are working on the correct branch:

   ```sh
    git status
    ```

### Starting app development

1. Copy the `.env.example` file:

    ```sh
    cp .env.example .env
    ```

   Modify the environment variables to suit your requirements.

2. Launching services using the "dev" profile:

    ```sh
    docker compose --profile dev up
    ```

### Starting app production

#### Starting app

```sh
docker compose --profile prod up
```


1. Launching llm and embedding

    1.1. Running on cpu

    ```sh
    docker compose --profile cpu up
    ```

    1.2. Running on gpu

    ```sh
    docker compose --profile gpu up
    ```
