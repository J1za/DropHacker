<p align="center">
  <a href="#">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://i.imgur.com/PerdOdz.png">
      <img src="https://i.imgur.com/PerdOdz.png" height="128">
    </picture>
    </a>
    <h1 align="center">DropHacker</h1>
  
</p>

<p align="center">
  <a aria-label="Join the community on Telegram" href="#">
    <img alt="" src="https://github.com/rubenlagus/TelegramBots/raw/master/TelegramBots.svg">
  </a>
</p>

## What is DropHacker?

Software is a convenient tool that abuses blockchains to run
wallets between them and potentially profit from any drops of these
coins. All of our solutions are unique developments code to provide best security for web3 community

## Getting Started

#### 1. Clone repository

```bash
git clone https://github.com/J1za/DropHacker
```

#### 2. Go to the root folder

```bash
cd Drophacker
```

#### 3. Install All Dependensies

```bash
npm i
```

#### 4. Create, Reset and Fill DB

```bash
# Create dev.db in ./prisma/...
npx prisma migrate dev
```

WE ARE DONE, project is ready to use.

## Build The Project

```bash
npm run build
```

## Start the project

```bash
npm start
```

## Utilities

You can see, what is inside the database, and if needed change something.
(Use it on your own risk)

```bash
npx prisma studio
# Reset the DB
npx prisma migrate reset
```
