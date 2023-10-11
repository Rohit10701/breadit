
# Breadit - A Modern Fullstack Reddit Clone 

This repository contains the source code for bredit built with the Next.js App Router, TypeScript , Tailwind & AWS RDS(MySQL as Database) with redis cache.


## Features

 - Infinite scrolling for dynamically loading posts
 - Authentication using NextAuth & Google
 - Custom feed for authenticated users
 - Advanced caching using [Upstash Redis]
 - Optimistic updates for a great user experience
 - A beautiful and highly functional post editor
 - Image uploads & link previews
 - Full comment functionality with nested replies

## Technologies Used

`Next.js` `React.js` `HTML/CSS` `AWS RDS(MySQL)` 
`Typescript` `Redis` `Tailwind` `Prisma`

## Getting started

To get started with this project, run

```bash
  git clone https://github.com/Rohit10701/reddit-clone.git
```
```
  yarn install
```
```
  yarn prisma generate
```
```
  yarn run dev
```


and make a .env file and copy these variables into that:

```bash
DATABASE_URL=
NEXTAUTH_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=

REDIS_URL=
REDIS_SECRET=
```

## License

MIT
