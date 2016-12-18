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
  createVideo(video: {
    title:"Foo",
    duration:300,
    released:true}
  ) {
        id
      title
    }
}
```