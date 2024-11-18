## 🌐 [Versão em Português do README](README.md)

# Pong - Player vs Computer

This project is an interactive version of the classic Pong game, allowing a competition between a player and the computer. It features different difficulty levels, player name customization, sound effects, and an immersive visual experience with animations and dynamic images.

## 🔨 Project Features

- **Difficulty Modes:** Easy, Medium, and Hard, adjusting the computer AI's behavior.
- **Full Control:** The player can interact using keyboard and mouse to configure and play.
- **Customization:** Enter the player's name before starting the game.
- **Scoreboard:** Tracks points to determine the winner.
- **Sound Interactivity:** Unique sounds for collisions and goals.
- **Start and Restart Screens:** Navigation between different game states with intuitive buttons.

### Visual Example of the Project
![chrome-capture-2024-11-17](https://github.com/user-attachments/assets/e2e7401c-7ab5-4ce1-8ca9-bb911b9d85dd)

## ✔️ Technologies and Techniques Used

- **JavaScript**: Game logic and event handling.
- **p5.js Library**: Rendering and interactive animations.
- **HTML5**: Application structure.
- **CSS3**: Styling and responsive design.
- **p5.sound**: Sound effects implementation.
- **Images and Audio**: Custom sprites and sound files.

## 📁 Project Structure

- **index.html**: Main HTML file.
- **script/**
    - `sketch.js`: Contains all the game logic.
- **sounds/**
    - `bounce.wav`: Collision sound.
    - `goal.wav`: Goal sound.
- **sprites/**
    - `barra01.png`: Player paddle sprite.
    - `barra02.png`: Computer paddle sprite.
    - `bola.png`: Ball sprite.
    - `fundo1.png`, `fundo2.png`: Game background sprites.
    - `fundo_inicio.jfif`: Start screen background.
- **style/**
    - `reset.css`: Resets default styles.
    - `style.css`: Visual settings and responsiveness.

## 🛠️ How to Open and Run the Project

To run the project locally, follow these steps:

1. **Ensure Node.js is Installed**:
    - [Node.js](https://nodejs.org/) is required to run the project. Verify if it's installed by running:
      ```bash
      node -v
      ```
    - If it's not installed, download and install the recommended version.

2. **Clone the Repository**:
    - Copy the repository URL and run the following command in your terminal:
      ```bash
      git clone <REPOSITORY_URL>
      ```

3. **Install a Local Server**:
    - Use a local server like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) on VS Code or set up a server with:
      ```bash
      npx serve
      ```

4. **Open the Project**:
    - Navigate to the project directory and start the local server. Open your browser using the provided URL.

## 🌐 Deploy

To deploy the project and make it available online, you can use free platforms like **GitHub Pages**, **Vercel**, or **Netlify**:

### 1. **GitHub Pages**
- Upload the project files to a GitHub repository.
- Go to the repository settings.
- Under **Settings > Pages**, configure the `main` branch (or the branch containing the project) to serve the site.
- After a few minutes, your project will be available at the provided GitHub Pages link (usually `https://<your-username>.github.io/<repository-name>`).

### 2. **Vercel**
- Create an account on [Vercel](https://vercel.com/).
- Click **New Project** and import your GitHub repository.
- Configure the basic options and click **Deploy**.
- Vercel will generate a unique link to access your project (e.g., `https://your-project.vercel.app`).

### 3. **Netlify**
- Create an account on [Netlify](https://www.netlify.com/).
- Drag and drop the project folder into Netlify's deployment interface.
- Wait for the publication and access the automatically generated link (e.g., `https://your-project.netlify.app`).

### Deployment Requirements
- Ensure all project files (HTML, CSS, JavaScript, sounds, and images) are organized correctly.
- Adjust relative paths in the code if necessary to ensure all files are accessible in the online environment.
- Test locally before deploying to avoid compatibility issues.

Choose the platform that best suits your needs and publish your project to share it with the world!
