# Comandos Utilizados

A seguir está a lista de comandos utilizados para configurar o projeto:

1. **Inicialize o projeto npm:**
    ```bash
    npm init -y
    ```

2. **Instale TypeScript e as definições de tipo do Node:**
    ```bash
    npm install typescript @types/node -D
    ```

3. **Inicialize o TypeScript (tsconfig.json):**
    ```bash
    npx tsc --init
    ```

4. **Instale o pacote tsx (se necessário):**
    ```bash
    npm install tsx -D
    ```

5. **Instale o framework Fastify:**
    ```bash
    npm install fastify
    ```

6. **Inicie os containers Docker em background:**
    ```bash
    docker-compose up -d
    ```

7. **Verifique os containers Docker em execução:**
    ```bash
    docker ps
    ```

8. **Visualize os logs de um container específico:**
    ```bash
    docker logs 'id_da_imagem'
    ```

9. **Instale o Prisma ORM como dependência de desenvolvimento:**
    ```bash
    npm install prisma -D
    ```

10. **Inicialize o Prisma no projeto:**
    ```bash
    npx prisma init
    ```

11. **Execute uma migração do Prisma (ambiente de desenvolvimento):**
    ```bash
    npx prisma migrate dev
    ```

12. **Inicie o Prisma Studio para gerenciamento do banco de dados:**
    ```bash
    npx prisma studio
    ```

13. **Instale o pacote Zod para validação de esquemas:**
    ```bash
    npm install zod
    ```
    