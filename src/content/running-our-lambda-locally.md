---
path: /running-locally
title: Running our Lambda locally
tag: backend
date: 2020-05-11T17:46:40.265Z
part: Building backend
chapter: 'Adding libraries '
---
Now we have successfully deploy our function that has a basic Hello World query. We will now go ahead and start testing out how to run it locally.

In your terminal run the following:



```
$ sls offline
```

This will run your Lambda on port 4000. So in your browser if you go to \`localhost:4000/graphql\` you see an instance of GraphQL Playground:



\[add playground image here]

GraphQL Playground is where you can test your Queries/Mutations or Subscriptions for your GraphQL API and see the responses that come back from your server. Also it shows you the schema for your API, which makes it self documenting to a certain extent. 



Now we can run the following query :



```

{

hello
}
```



It should return the following:



\[Add hello world data return here]

Now that is working! Lets continue to setup the other libraries we need.