# node-graphql


```node
    npm install
```

```node 
    node server2.js
```

Then open a tab on your favorite browser to localhost:4000/graphql


Enter the foloowing under the main Graph QL query area
```js 
    query getSingleCourse($courseID: Int!) {
        course(id: $courseID) {
            title
            author
            description
            topic
            url
        }
    }
```

and the following under the query variables
```js 
    { 
        "courseID":3
    }
```