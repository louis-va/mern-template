# MERN Template

This template provides a minimal setup to get React working with Typescript, Vite and a Express / Mongo backend.

<!-- Technology -->
## Packages

| Client      | Server    |
|-------------|-----------|
| Vite        | Express   |
| React       | MongoDB   |
| Typescript  | Mongoose  |
| ESLint      | CORS      |
|             | Dotenv    |
|             | Typescript|
|             | ESLint    |


<!-- GETTING STARTED -->
## Getting Started

The client and the server run independantly. The client is connected to the server's API via localhost. The API's URL can be edited in the client's ```.env``` file.

### ⚙️ Prerequisites

You need to have node and npm installed on your machine to run this project locally.  

#### npm
  ```sh
  npm install npm@latest -g
  ```

### 💾 Installation

#### 1. Clone the repo
```sh
git clone git@github.com:louis-va/mern-template.git
```
#### 2. Install NPM packages
```sh
# root of the project
npm install
```
#### 3. Install client and server NPM packages
```sh
# root of the project
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

### 🚀 Execution

#### Run client & server
```sh
# root of the project
npm run dev
```

#### Only run client
```sh
cd client/
npm run dev
```

#### Only run server
```sh
cd server/
npm run dev
```

### 🚚 Production

#### Build then run client & server
```sh
# root of the project
npm run build
npm run start
```

#### Deployment
When deploying the project, set the ```VITE_API_URL``` in the client's ```.env.production``` file as the URL to your database and configure the ```allowedOrigins``` in the server's ```index.ts``` to allow your client's URL to connect to the server.

### 🏠 Localhost
**Client**: http://localhost:3000 <br>
**Server**: http://localhost:8000

You can edit those values in the server's ```.env``` file and the client's ```vite.config.ts``` file. <br>
If you edit the client's port, you'll have to edit the ```allowedOrigins``` in the server's ```index.ts``` file with the new port.