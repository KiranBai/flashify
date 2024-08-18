

# Flashify | Take u Forward Assignment 

Flashify is a powerful web application designed to create and manage flashcards, enhancing learning and memorization processes.


## Key Features

- **AI-Powered Flashcard Creation**: Put your text and generate question and answer flashcards
- **Manual Creation Option**: Create your manual cards
- **Flashcard Management**:Easily view and edit your flashcards
- **Intuitive User Interface**: Easy navigation and user-friendly experience

## Tech Stack

### Frontend
- React with Vite 

### Backend
- Node.js and Express.js

### Database
- MySQL for structured data storage
- Redis for caching and performance optimization

### Deployment
- MySQL hosted on Railway
- Backend deployed on Render
- Frontend hosted on Cloudflare Pages

### AI Integration
- OpenAI API for intelligent flashcard generation

### Additional Tools
- Zod for data validation
- Sequelize as the ODM



## File Structure
```
|-- backend
|     -- src
|       |-- config
|       |-- controllers
|       |-- middlewares
|       |-- migrations
|       |-- models
|       |-- routes
|       |   `-- v1
|       |-- seeders
|       `-- services
|-- frontend
    |-- dist
    | -- src
        |-- components
        |-- hooks
        |-- pages
.github
  -- workflows
```

## Setting up project

### Clone the project
```
git clone https://github.com/KiranBai/flashify.git
```
### Install dependencies 
- Move to frontend folder and run the command - `pnpm install`
- Moce to backend folder and run the command - `pnpm install`

### Setup ENV File
- Backend
  ```
    OPEN_AI_API_KEY=
    DB_USERNAME=
    DB_PASSWORD=
    DB_DATABASE=
    DB_HOST=
    DB_PORT=
    REDIS_USERNAME=
    REDIS_PASSWORD=
    REDIS_HOST=
    REDIS_PORT=
    NODE_ENV=development | test | production
  ```
- Frontend
```
    VITE_BACKEND_URI=http://localhost:3000
```
### Local Database:



### Run your backend and frontend server
  - cd to backend `pnpm run dev`
  - cd to frontend `pnpm run dev`

### Wohoo ! congrats you are done with setup  :)
  







