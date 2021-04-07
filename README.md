# **Skeleton NodeJs**

O Skeleton NodeJs é basicamente um esqueleto de um ambiente para desenvolvimento de um projeto em NodeJs.
</br>O projeto já vem basicamente com ambiente em Docker, configurações de eslint, já configurado para testes unitários com Jest, configurado husky para padrões de commit, configurado com Travis para utilização de integração contínua. Os arquivos de configurações do Jest estão configurados para uma estrutura de Clean Architecture, caso não seja essa a sua arquitetura os arquivos deverão ser alterados.

## **Ferramentas utilizadas**

- Node 13x
- MongoDB
- Docker
- Typescript
- Jest

## **Depois de tudo configurando**

Instale as dependências do projeto rodando o seguinte comando no terminal.

`npm install`

Para iniciar a API execute o comando abaixo no terminal (Docker).

`npm run up`

Para derrubar a API execute o comando abaixo no terminal (Docker).

`npm run down`

Após a inicialização o sistema ficará disponível no endereço (Verificar seu serve para a mesma porta)

`http://localhost:3000/api/`

Para rodar atualizações do código no container deve ser executado o comando abaixo

`tsc -w`

Para rodar os testes unitarios

`npm test:unit `

Teste Integração

`npm test:integration`

Testes Verbosos

`npm test`  
`npm test:verbose`

Test CI para toda vez que dor feito um push

`npm test:ci`
