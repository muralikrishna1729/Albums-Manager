# Albums Manager

Albums Manager is a React-based web application for managing albums integrated with a backend JSON server. The app supports features like searching, sorting, pagination, deleting, and exporting albums to a CSV file.

---

## Features
- **Search Filter**: Quickly search for albums by title.
- **Sort Albums**: Sort albums by ID or title.
- **Pagination**: Navigate through multiple pages of albums.
- **View Album Details**: Display album details in a modal.
- **Delete Confirmation**: Confirm before deleting an album.
- **Export to CSV**: Export the list of albums to a CSV file.
- **Dark/Light Theme**: Toggle between dark and light modes.
- **Responsive Design**: Optimized for various screen sizes.

---

## Prerequisites
- Node.js (v16 or later)
- npm or yarn
- JSON Server (for backend)

---

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/albums-manager.git
cd albums-manager
```

### 2. Install Dependencies
Run the following command to install required packages:
```bash
npm install
```

### 3. Run the Backend
Set up the JSON Server for the backend:
```bash
npx json-server --watch db.json --port 8000
```

### 4. Start the Application
Launch the React development server:
```bash
npm start
```
Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

---

## Backend
The application uses a JSON Server running on [http://localhost:8000](http://localhost:8000). A sample `db.json` file might look like this:
```json
{
  "albums": [
    { "id": 1, "title": "Album 1" },
    { "id": 2, "title": "Album 2" },
    { "id": 3, "title": "Album 3" }
  ]
}
```

---

## Deployment
To deploy this project:

### 1. Build the Production Files
```bash
npm run build
```

### 2. Host the `build` Folder
Host the `build` folder on a static hosting service like Netlify, Vercel, or GitHub Pages.

---

## License
This project is licensed under the MIT License.

---

## Guide to Push Project to GitHub

1. **Initialize Git in Your Project**
   Open your project folder in a terminal and run:
   ```bash
   git init
   ```

2. **Add Files and Commit**
   ```bash
   git add .
   git commit -m "Initial commit"
   ```

3. **Add the Remote Repository**
   ```bash
   git remote add origin https://github.com/your-username/albums-manager.git
   ```

4. **Push the Code**
   ```bash
   git branch -M main
   git push -u origin main
   ```

