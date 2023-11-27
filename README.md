# React + TypeScript + Vite + Express + Mongo

This template provides a minimal setup to get React working with Typescript and Vite with an Express / Mongo backend.

<!-- GETTING STARTED -->
# Getting Started

The client and the server run indepedantly. The client is connected to the server's API via localhost. The API's URL can be edited in the client's ```.env``` file.

## ⚙️ Prerequisites

You need to have node and npm installed on your machine to run this project locally.  

### npm
  ```sh
  npm install npm@latest -g
  ```

## 💾 Installation

### 1. Clone the repo
```sh
git clone git@github.com:louis-va/mern-template.git
```
### 2. Install NPM packages
```sh
npm install
```
### 3. Install client and server NPM packages
```sh
npm run install
```
OR
```sh
cd client/
npm install
```
```sh
cd server/
npm install
```

## 🚀 Execution

### Run client & server
```sh
npm run dev
```

### Only run client
```sh
cd client/
npm run dev
```

### Only run server
```sh
cd server/
npm run dev
```

## 🚚 Production
### Build then run client & server
```sh
npm run build
npm run start
```

## 🏠 Localhost
**Client**: localhost:3000 <br>
**Server**: localhost:8000

You can edit those values in the server's ```.env``` file and the client's ```vite.config.ts``` file. <br>
If you edit the client's port, you'll have to edit the ```allowedOrigins``` in the server's ```index.ts``` file.