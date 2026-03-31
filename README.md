🌾 Kisan Setu – Your Farming Hub

Kisan Setu is a modern, farmer-centric web application designed to bridge the gap between technology and agriculture. It provides farmers with essential tools, insights, and resources to improve productivity, make informed decisions, and stay connected with agricultural services.

🚀 Features
🌱 Farmer Dashboard – Centralized platform for managing farming activities
📊 Data Visualization – Interactive charts for insights using Chart.js & Recharts
🌍 Multi-language Support – Powered by i18next for accessibility
📅 Calendar & Planning Tools – Track farming schedules
🔐 Authentication & Backend – Integrated with Supabase
🎨 Modern UI – Built with Tailwind CSS + ShadCN UI
⚡ Fast Performance – Powered by Vite + React
📱 Responsive Design – Works across devices
🛠️ Tech Stack
Frontend
⚛️ React 18
⚡ Vite
🎨 Tailwind CSS
🧩 ShadCN UI + Radix UI
State & Data
🔄 React Query (@tanstack/react-query)
📦 Supabase
Forms & Validation
React Hook Form
Zod
Visualization
Chart.js
Recharts
Animations
Framer Motion
Testing
Vitest
Playwright
📁 Project Structure
kisan-setu/
│── public/              # Static assets
│── src/
│   ├── components/      # Reusable UI & layout components
│   │   ├── ui/          # ShadCN UI components
│   ├── pages/           # App pages (if applicable)
│   ├── App.tsx          # Main app component
│   ├── main.tsx         # Entry point
│   ├── index.css        # Global styles
│── package.json
│── tailwind.config.ts
│── vite.config.ts
⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/your-username/kisan-setu.git
cd kisan-setu
2️⃣ Install dependencies
npm install

or (if using Bun)

bun install
3️⃣ Setup Environment Variables

Create a .env file in the root directory:

VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_anon_key
4️⃣ Run the development server
npm run dev

App will run at:

http://localhost:5173
🧪 Testing

Run tests:

npm run test

Watch mode:

npm run test:watch

End-to-end testing (Playwright):

npx playwright test
🏗️ Build for Production
npm run build

Preview build:

npm run preview
🎯 Future Improvements
📡 Real-time weather integration
🤖 AI-based crop recommendations
🛒 Marketplace for farmers
📍 Location-based advisory
📲 Mobile app version
🤝 Contributing

Contributions are welcome!

Fork the repository
Create a new branch
Commit your changes
Push and create a PR
📄 License

This project is licensed under the MIT License.

👨‍🌾 Vision

Empower every farmer with digital tools to make agriculture smarter, more efficient, and sustainable.
