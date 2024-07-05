Here is your first subgraph.

Its a Spring boot starter project with some GraphQL dependencies to get you started.

Here are the steps to doing your first query

1. Add schema definition by adding types and definition to
   resources/schema/schema.graphqls
2. Generate code via Netflix plugin 
    mvn graphqlcodegen:generate
3. Add your resolver class with a Query
4. Run your application
5. Checkout http://localhost:8081/graphiql

Example schema definitions and resolver reference [here](http://localhost:8081/graphiql?path=/graphql)