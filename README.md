# Based on

- Code base: https://github.com/apollographql/apollo-server
- docs:
  - https://www.apollographql.com/docs/apollo-server/getting-started/
  - https://www.apollographql.com/tutorials/fullstack-quickstart/01-introduction
- Fetching from Rest: https://www.apollographql.com/docs/apollo-server/data/fetching-rest#adding-a-query-parameter
- Using Apollo with typescript: https://www.apollographql.com/docs/react/v2/development-testing/static-typing/

# Typescript

Use CodeGen (https://the-guild.dev/graphql/codegen)

# links:

- https://www.apollographql.com/docs/apollo-server/workflow/generate-types/

# Steps

- Update the Schema.graphql
- run the generate or use watch

`yarn graphql-codegen --watch "src/\*_/_.js"`

use reference generated in code

# References:

## To disabling the landing page

https://www.apollographql.com/docs/apollo-server/api/plugin/landing-pages/#disabling-the-landing-page

# ToDo:

- [x] Desabilitar pagina uso das queries
- [x] Usar via PostMan
- [ ] Pegar as orders
- [x] Conectar com o Partners e authenticar fazendo refresh do token
- [ ] Authenticar o usuário pegar dados da ApiMinhaVoltz - na api minha voltz é usando session? como recuperar dados do usuário logado. Talvez a authenticação deve ser feita pelo Kong? e o Kong habilitar o uso do graphQL
- [ ] Validar o token do usuário
- [ ] Usar cache

# Next Steps:

- ideas to separate the files (Query, mutation)
  https://www.apollographql.com/blog/modularizing-your-graphql-schema-code
