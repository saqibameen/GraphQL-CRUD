# GraphQL CRUD App Using NodeJS, Apollo, and MongoDB

> A Simple CRUD App Using GraphQL, NodeJS, Apollo, and MongoDB

## 🚀Getting Started

### Step #0

Clone the repo. Make sure you have MongoDB installed and running.

### Step #1

Install dependencies.

```shell
npm install
```

## Step #2

Run the server.

```shell
npm start
```

## Step #3

Go to `http://localhost:4000/graphql` and start playing with GraphQL.

Below is a simple query to add data:

```graphql
mutation {
  addMovie(name: "GraphQL Movie", producer: "John doe", rating: 9.5) {
    id
    name
    rating
    producer
  }
}
```


## Get in Touch!

👋 Say hi [@saqibameen on Twitter →](https://twitter.com/saqibameen)
