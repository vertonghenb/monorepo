# Recipe API - Monolithic Repository

## Prerequisites

- Node.js installed
  - https://nodejs.org/en/
- Angular CLI installed
  - `npm install -g @angular/cli`
- DotNet 5.0 Installed
- SQL Database installed on localhost 
  - If you're an apple fanboi, refer to Web III for running a SQL Server Database in a Docker container.

## Getting started -  Development

````
git clone this repository
````

### Client

```
cd Client
npm install
ng build
npm start
```

### Server

```
cd Server/RecipeApi
dotnet watch run
```

---

## Getting started -  Production

### Client

```
cd Client
npm install
ng build
```

### Server

```
cd Server/RecipeApi
dotnet run
```

## 