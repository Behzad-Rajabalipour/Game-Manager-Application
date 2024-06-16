
# Game Manager

Game Manager is a comprehensive application designed to manage and organize video games. It allows users to add, edit, delete, and search for games in their collection, providing detailed information about each game.

## Features

- Add new games to the collection
- Edit existing game details
- Delete games from the collection
- Search for games by title, genre, or platform
- View detailed information about each game, including title, genre, release date, and platform
- User-friendly interface with responsive design

## Technologies Used

- **Frontend:**
  - HTML
  - CSS
  - JavaScript
  - React

- **Backend:**
  - Node.js
  - Express.js
  - TypeScript

- **Database:**
  - MongoDB

- **Other Tools:**
  - Docker
  - Webpack
  - Babel
  - Prettier
  - Husky

## Getting Started

### Prerequisites

To run this project locally, you need to have the following installed:

- Node.js
- npm (Node package manager)
- MongoDB
- Docker (optional, for running with Docker)

### Installation

1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/Behzad-Rajabalipour/game-manager.git
   \`\`\`
2. Navigate to the project directory:
   \`\`\`bash
   cd game-manager
   \`\`\`
3. Install the dependencies for both the backend and the frontend:
   \`\`\`bash
   npm run install:global
   \`\`\`

### Running the Application

#### Using Docker

1. Start the application using Docker Compose:
   \`\`\`bash
   npm run start:docker
   \`\`\`
2. Open your browser and navigate to \`http://localhost:3000\` to see the application in action.

#### Without Docker

1. Start the MongoDB server:
   \`\`\`bash
   mongod
   \`\`\`
2. Start the backend server:
   \`\`\`bash
   npm run start:server
   \`\`\`
3. Start the frontend development server:
   \`\`\`bash
   npm run start:client
   \`\`\`
4. Open your browser and navigate to \`http://localhost:3000\` to see the application in action.

## Usage

- **Adding a New Game:**
  - Navigate to the "Add Game" section
  - Fill out the form with the game's details (title, genre, release date, platform, etc.)
  - Click "Add Game" to save the new game to your collection

- **Editing a Game:**
  - Browse your game collection and select the game you want to edit
  - Click on the "Edit" button
  - Update the game details and click "Save" to apply the changes

- **Deleting a Game:**
  - Browse your game collection and select the game you want to delete
  - Click on the "Delete" button to remove the game from your collection

- **Searching for a Game:**
  - Use the search bar to find games by title, genre, or platform
  - View the search results and click on a game to see its details

## Project Structure
![image](https://github.com/Behzad-Rajabalipour/game-manager/assets/115672803/b644b033-a38e-452f-9aa9-251dcb3d67ea)

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository
2. Create a new branch (\`git checkout -b feature/your-feature-name\`)
3. Make your changes
4. Commit your changes (\`git commit -m 'Add some feature'\`)
5. Push to the branch (\`git push origin feature/your-feature-name\`)
6. Open a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Special thanks to all the contributors who have helped in developing this project.
- [React](https://reactjs.org/)
- [Node.js](https://nodejs.org/)
- [Express.js](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)

---

Feel free to reach out if you have any questions or need further assistance!
