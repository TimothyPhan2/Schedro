# 📅 Schedro

**Schedro** is a minimalistic scheduling web app that allows users to share calendars via a magic link and collaboratively book appointments. Designed with simplicity and real-time collaboration in mind, the app lets users create overlapping appointments, assign group tags, and customize visual cues with colors.

---

## 🚀 Features

- 🔗 **Shareable Calendars** — Generate a magic link to share your calendar with others.
- ➕ **Collaborative Appointments** — Anyone with the link can add appointments.
- 🎨 **Custom Group Tags** — Tag events by group (e.g. Doctor, Team A, Teacher).
- 🌈 **Color-Coded Entries** — Choose a color for each appointment to stay organized.
- 📊 **Overlapping View Mode** — Toggle a view to easily see overlapping events.
- 🔄 **Real-Time Sync** — Built with Supabase for live updates across devices.

---

## 🛠 Tech Stack

| Layer       | Tech                         |
|-------------|------------------------------|
| Frontend    | [Next.js](https://nextjs.org) + [TypeScript](https://www.typescriptlang.org/) |
| Styling     | [TailwindCSS](https://tailwindcss.com) |
| Backend     | [Supabase](https://supabase.com) (PostgreSQL, Realtime, Auth) |
| Hosting     | [Vercel](https://vercel.com) |
| UI Library  | [shadcn/ui](https://ui.shadcn.com)  |

---

## 📦 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/schedro.git
cd schedro
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env.local` file and add your Supabase project credentials:

```
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_anon_key
```

> You can find these in your Supabase project settings under **API**.

### 4. Run locally

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📌 Roadmap

- [x] Basic calendar UI
- [x] Appointment creation modal
- [x] Real-time Supabase syncing
- [x] Overlapping appointment view toggle
- [ ] PWA support (planned)
- [ ] Google Calendar integration
- [ ] Role-based permissions
- [ ] Notifications & reminders

---

## 📄 License

Distributed under the MIT License. See [LICENSE](LICENSE) for details.
