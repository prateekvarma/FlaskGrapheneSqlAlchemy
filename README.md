# Testing the GraphQL service :

After booting the server, go to http://localhost:5000/graphql

Paste the following query to see results :
```
{
  allEmployees{
    edges{
      node{
        id
        name
        department{
          name
        }
      }
    }
  }
}
```