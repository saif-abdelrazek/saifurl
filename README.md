# SaifURL

A modern, fullstack URL shortener service with user authentication, dashboard, custom domains, and more.

---

## Features

- 🔗 **Shorten URLs** with custom aliases and multiple domains
- 👤 **User authentication** (sign up, sign in, password reset)
- 🏠 **Dashboard** to manage your short URLs
- 📊 **Click tracking** for each short URL
- 🎨 **Light/Dark theme** support
- 🛡️ **Email verification** for secure accounts
- 🛠️ **Profile management** (update info, change password)
- 🌐 **HashRouter** for static hosting compatibility
- 🏷️ **Status badge** for service health

---

## Getting Started

### 1. **Clone the repository**

```sh
git clone https://github.com/saifabdelrazek011/saifurl.git
cd saifurl
```

### 2. **Install dependencies**

```sh
npm install
```

### 3. **Set environment variables**

Create a `.env` file if you want to override the default API URL:

```
VITE_API_URL=https://api.saifabdelrazek.com/v1
```

### 4. **Run the app**

```sh
npm run dev
```

The app will be available at [http://localhost:5173](http://localhost:5173) (or your Vite dev port).

---

## Project Structure

```
src/
  components/         # Reusable UI components
  contexts/           # React context providers (Dashboard, Shorturls)
  pages/              # Main pages (Dashboard, Profile, Auth, etc.)
  router.jsx          # Main router with HashRouter and routes
  main.jsx            # App entry point
```

---

## Usage

- **Sign up** and verify your email.
- **Sign in** to access your dashboard.
- **Create, edit, and delete** short URLs.
- **Copy** short URLs with one click.
- **Switch themes** using the toggle in the header or profile.
- **Manage your profile** and change your password.
- **Reset your password** via the "Forget Password" page.
- **Check service status** via the badge in the header/footer.

---

## Deployment

- The app uses **HashRouter** for static hosting (e.g., Netlify, Vercel, GitHub Pages).
- Make sure your backend API is accessible at the URL set in `VITE_API_URL`.

---

## Credits

- Built by [Saif Abdelrazek](https://saifabdelrazek.com)
- Status badge powered by [Uptime Kuma](https://status.saifabdelrazek.com)

---

## License

MIT License
