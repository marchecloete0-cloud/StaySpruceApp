# StaySpruceApp

A React + Supabase application for managing stay spruce operations.

## 📋 Prerequisites

- Node.js 16+ and npm (or yarn)
- Supabase account and project
- Git

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/marchecloete0-cloud/StaySpruceApp.git
cd StaySpruceApp
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up Environment Variables

Create a `.env` file in the root directory based on `.env.example`:

```bash
cp .env.example .env
```

Then fill in your Supabase credentials:

```env
VITE_SUPABASE_URL=your_supabase_url_here
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key_here
```

You can find these values in your Supabase project settings:
- Go to https://supabase.com
- Navigate to your project
- Settings → API
- Copy the URL and Anon Key

### 4. Run the Development Server

```bash
npm run dev
```

The app will automatically open in your browser at `http://localhost:3000`

## 📁 Project Structure

```
StaySpruceApp/
├── src/
│   ├── components/          # React components
│   │   └── StaySpruceApp.jsx
│   ├── config/              # Configuration files
│   │   └── supabaseClient.js
│   ├── styles/              # CSS files
│   │   ├── index.css
│   │   └── App.css
│   └── main.jsx             # Entry point
├── supabase/
│   └── migrations/          # Database migrations
│       └── 001_initial_schema.sql
├── index.html               # HTML entry point
├── vite.config.js           # Vite configuration
├── package.json             # Dependencies and scripts
├── .env.example             # Environment variables template
├── .gitignore               # Git ignore rules
└── README.md                # This file
```

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 📚 Next Steps

1. **Create your database schema** in Supabase
2. **Update the Supabase migration** in `supabase/migrations/001_initial_schema.sql`
3. **Modify `StaySpruceApp.jsx`** to match your data model
4. **Add more components** as needed in `src/components/`

## 📖 Documentation

- [React Documentation](https://react.dev)
- [Supabase Documentation](https://supabase.com/docs)
- [Vite Documentation](https://vitejs.dev)

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📝 License

This project is open source and available under the MIT License.

---

**Happy coding! 🎉**
