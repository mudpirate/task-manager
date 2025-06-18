# Task Manager API

A modern, full-stack task management application built with Node.js, Express, MongoDB, and a beautiful responsive frontend.

## 🚀 Features

- **CRUD Operations**: Create, Read, Update, and Delete tasks
- **Modern UI**: Beautiful glassmorphism design with animations
- **Responsive Design**: Works perfectly on desktop and mobile devices
- **Real-time Updates**: Instant feedback for all operations
- **MongoDB Integration**: Persistent data storage
- **RESTful API**: Clean and well-structured backend

## 🛠️ Tech Stack

### Backend

- **Node.js** - JavaScript runtime
- **Express.js** - Web framework
- **MongoDB** - NoSQL database
- **Mongoose** - MongoDB object modeling
- **dotenv** - Environment variable management

### Frontend

- **Vanilla JavaScript** - No framework dependencies
- **CSS3** - Modern styling with animations
- **HTML5** - Semantic markup
- **Google Fonts** - Typography

## 📦 Installation

1. **Clone the repository**

   ```bash
   git clone <your-repo-url>
   cd task-manager
   ```

2. **Install dependencies**

   ```bash
   cd starter
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the `starter` directory:

   ```env
   MONGO_URI=mongodb://localhost:27017/task-manager
   ```

   Or use MongoDB Atlas:

   ```env
   MONGO_URI=mongodb+srv://username:password@cluster.mongodb.net/task-manager
   ```

4. **Start the development server**

   ```bash
   npm start
   ```

5. **Open your browser**
   Navigate to `http://localhost:2000`

## 🎯 API Endpoints

| Method | Endpoint            | Description         |
| ------ | ------------------- | ------------------- |
| GET    | `/api/v1/tasks`     | Get all tasks       |
| POST   | `/api/v1/tasks`     | Create a new task   |
| GET    | `/api/v1/tasks/:id` | Get a specific task |
| PATCH  | `/api/v1/tasks/:id` | Update a task       |
| DELETE | `/api/v1/tasks/:id` | Delete a task       |

## 📁 Project Structure

```
task-manager/
├── starter/
│   ├── app.js              # Main application file
│   ├── package.json        # Dependencies and scripts
│   ├── controllers/        # Route controllers
│   │   └── tasks.js
│   ├── models/            # Database models
│   │   └── Task.js
│   ├── routes/            # API routes
│   │   └── tasks.js
│   ├── db/               # Database connection
│   │   └── connect.js
│   └── public/           # Frontend assets
│       ├── index.html
│       ├── main.css
│       └── browser-app.js
└── final/               # Completed version
```

## 🎨 UI Features

- **Glassmorphism Design**: Modern glass-like effects
- **Smooth Animations**: Hover effects and transitions
- **Responsive Layout**: Mobile-first approach
- **Beautiful Background**: Dynamic gradient with overlay
- **Interactive Elements**: Enhanced button and form styling

## 🔧 Development

### Running in Development Mode

```bash
npm start
```

### Available Scripts

- `npm start` - Start the development server with nodemon
- `npm install` - Install dependencies

## 🌟 Key Features

### Task Management

- ✅ Create new tasks with validation
- ✅ Mark tasks as completed
- ✅ Edit existing tasks
- ✅ Delete tasks with confirmation
- ✅ Real-time status updates

### User Experience

- 🎨 Beautiful, modern interface
- 📱 Fully responsive design
- ⚡ Fast and smooth interactions
- 🔄 Automatic page updates
- 🎯 Intuitive user interface

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the ISC License.

## 🙏 Acknowledgments

- Unsplash for the beautiful background image
- Google Fonts for typography
- The Node.js and Express.js communities

---

**Happy Task Managing!** 🎉
