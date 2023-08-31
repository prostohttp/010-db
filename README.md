

 ```
 db.books.insertMany([
{
title: "Вы не знаете JavaScript",
description: "Книга о JavaScript",
authors: "Автор 1"
},
{
title: "Вы не знаете Node.js",
description: "Книга о Node.js",
authors: "Автор 2"
}
]);
```

```
db.books.find({ title: "Вы не знаете JavaScript" });
```

```
  { _id: ObjectId("001") },
  { $set: {
    description: "Новое описание",
    authors: "Новый автор"
  }}
);
```
