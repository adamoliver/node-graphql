# Experiments with Node GraphQL

Uses an Express server with GraphIQL


```
{
  videos {
    id
    title
    }
}


mutation M {
  createVideo(title:"Foo",duration:300,released:true) {
    id
    title
  }
}
```