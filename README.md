# User comments

## Introduction

We're constantly using social networks: reading forum comments or company reviews, writing comments to friends, responding to others' comments. Have you ever wondered how to store this information in a database? For example, a person leaves a post and others comment, leave likes, or repost. But it doesn't end there... You can also reply, like these comments, like the replies to these comments, like the replies to the replies to these comments, and so on to infinity (it seems scarier than it is). This infinite loop is quite common, and there are many different solutions online, but please create your own before looking elsewhere.


## Releases

### Release 0. Design!

Let's develop a social network database with the following entities *(you don't need a separate model for each entity!)*:
- users
- posts
- comments
- replies to comments
- likes

Take 20 minutes to think about the architecture (independently with a pen and paper), then consult with your classmates. Listen to their solutions and choose the most optimal one; there's no one right solution, but try to find the most suitable solution for this situation.

### Release 1. Schemes, models, data

You designed the database, but this information isn't accessible to a computer: it's in your head or on a piece of paper. Now, shift everything to schemas and models. Now, create a seeder file and populate the database with initial values. The `faker.js` library may be helpful.

### Release 2. Requests
Use your models' methods (write your own or use some standard ones) to:

- Display all comments for a specific post.
- Display all responses for a specific comment.
- Display all users who liked the post.
- On behalf of a user, write a comment on a specific post.
- On behalf of a user, reply to a specific comment.

## Conclusion

You already practiced the most difficult part of databases, designing: creating a database structure and writing basic queries. If you run into problems with release 0, please spend more time studying this topic by watching a [Youtube video](https://www.youtube.com/watch?v=N-sAZB9G9zI) (rus), reading articles on designing. Here are 2 articles that discuss design in sufficient detail ([article 1](https://habr.com/ru/post/535588), [article 2](https://intuit.ru/studies/courses/1001/297/lecture/7409).
); they have examples and a `Use Cases` section, which may prove .interesting/helpful

