

 ```
 db.books.insertMany([
{
title: "Book 1",
description: "Description of Book 1",
authors: "Author 1"
},
{
title: "Book 2",
description: "Description of Book 2",
authors: "Author 2"
}
]);
```

```
db.books.find({ title: "Искомый_заголовок" });
```

```
db.books.updateOne(
  { _id: ObjectId("идентификатор_записи") },
  { $set: {
    description: "новое_описание",
    authors: "новые_авторы"
  }}
);
```
