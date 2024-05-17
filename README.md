# Interactive Comment Section

## Project Overview
This project is an interactive comment section built using React. The app allows users to add, edit, delete, and reply to comments. It includes features like upvoting/downvoting comments and a responsive design for both desktop and mobile views.

## Live Demo
Check out the live demo of the project [here](https://interactive-comments-section-azure.vercel.app/).

## Project Structure
Here's an overview of the project directory structure:

| Folder | File | Description |
| --- | --- | --- |
| root | | |
| | .gitignore | Git ignore file |
| | README.md | Project README |
| | data.json | Data file |
| | index.html | Entry HTML file |
| | package-lock.json | NPM package lock file |
| | package.json | NPM package file |
| | style-guide.md | Style guide |
| | style.css | Main stylesheet |
| components | | |
| | AddComment.jsx | Component to add comments |
| | Comment.jsx | Component to display a comment |
| | EditComment.jsx | Component to edit comments |
| | Reply.jsx | Component to reply to a comment |
| public | | |
| | favicon-32x32.png | Favicon |
| | icon-delete.svg | Delete icon |
| | icon-edit.svg | Edit icon |
| | icon-minus.svg | Minus icon |
| | icon-plus.svg | Plus icon |
| | icon-reply.svg | Reply icon |
| | project-screenshot.png | Project screenshot |
| public/design | | |
| | active-states.jpg | Active state designs |
| | desktop-design.jpg | Desktop design |
| | desktop-modal.jpg | Desktop modal design |
| | desktop-preview.jpg | Desktop preview |
| | mobile-design.jpg | Mobile design |
| | mobile-modal.jpg | Mobile modal design |
| public/images | | |
| | | Image assets |
| public/images/avatars | | |
| | image-amyrobson.png | Amy Robson avatar |
| | image-amyrobson.webp | Amy Robson avatar webp |
| | image-juliusomo.png | Julius Omo avatar |
| | image-juliusomo.webp | Julius Omo avatar webp |
| | image-maxblagun.png | Max Blagun avatar |
| | image-maxblagun.webp | Max Blagun avatar webp |
| | image-ramsesmiron.png | Ramses Miron avatar |
| | image-ramsesmiron.webp | Ramses Miron avatar webp |
| src | | |
| | App.jsx | Main React component |
| | index.jsx | Entry JavaScript file |



### Components
- **AddComment.jsx**: Handles adding new comments.
- **Comment.jsx**: Displays a single comment with options to edit, delete, and reply.
- **EditComment.jsx**: Handles editing an existing comment.
- **Reply.jsx**: Handles replying to a specific comment.

### Public Assets
- **design**: Contains design mockups for different states and views (active states, desktop design, desktop modal, etc.).
- **images**: Includes avatar images and icons used in the project.

### Source Files
- **App.jsx**: Main application component.
- **index.jsx**: Entry point of the React application.

### Other Files
- **data.json**: Contains sample comment data used for initial state.
- **style-guide.md**: Provides styling guidelines for the project.
- **style.css**: Main stylesheet for the application.

## Getting Started

### Prerequisites
- Node.js and npm should be installed on your machine.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/dmdhaneef/-interactive-comments-section.git
2. Navigate to the project directory:
   
   ```bash
   cd -interactive-comments-section
   ```

3. Install dependencies:
   
   ```bash
   npm install
   ```

### Running the App

To start the development server, run:

```bash
npm start
```

This will launch the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

### Building for Production

To create a production build, run:

```bash
npm run build
```

This will create an optimized build of the app in the `build` folder.

## Features

- **Add Comment**: Users can add new comments.
- **Edit Comment**: Users can edit their own comments.
- **Delete Comment**: Users can delete their own comments.
- **Reply to Comment**: Users can reply to existing comments.
- **Upvote/Downvote**: Users can upvote or downvote comments.

## Design

The design files in the `public/design` folder provide visual guidance for the expected look and feel of the application.

## Avatar Images

Avatar images for users are located in the `public/images/avatars` folder. The project includes both PNG and WebP formats for better performance and compatibility.

## Icons

Icons for actions like delete, edit, reply, upvote, and downvote are located in the `public` folder.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.
