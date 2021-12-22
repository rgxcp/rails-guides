# 🚃 Rails Guides

## Commands

### 3 Creating a New Rails Project

#### 3.2 Creating the Blog Application

```bash
$ rails new blog
```

### 4 Hello, Rails!

#### 4.1 Starting up the Web Server

```bash
$ bin/rails server
```

#### 4.2 Say "Hello", Rails

```bash
$ bin/rails generate controller Articles index --skip-routes
```

### 5 MVC and You

#### 5.1 Generating a Model

```bash
$ bin/rails generate model Article title:string body:text
```

#### 5.2 Database Migrations

```bash
$ bin/rails db:migrate
```

#### 5.3 Using a Model to Interact with the Database

```bash
$ bin/rails console
```

### 6 CRUDit Where CRUDit Is Due

#### 6.2 Resourceful Routing

```bash
$ bin/rails routes
```

### 7 Adding a Second Model

#### 7.1 Generating a Model

```bash
$ bin/rails generate model Comment commenter:string body:text article:references
$ bin/rails db:migrate
```

#### 7.4 Generating a Controller

```bash
$ bin/rails generate controller Comments
```
