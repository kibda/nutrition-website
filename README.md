# 🏋️‍♂️ Coaching & Nutrition Tracker App

An all-in-one web application to help users manage their health and fitness journey by tracking their meals, workouts, booking sessions with coaches, and following personalized nutrition programs.

## 🚀 Features

### 👤 User Features
- Sign up / Login with role-based access (User or Coach)
- Personalized dashboard with nutritional summary
- Track daily meals with automatic nutritional calculation (calories, proteins, carbs, fats)
- View progress over time with charts and summaries
- Follow customized nutrition programs
- Schedule workouts and follow suggested routines
- Book 1-on-1 coaching sessions
- Give feedback and rate coaches
- Edit personal profile and health data

### 🧑‍🏫 Coach/Admin Features
- Manage and create nutrition and workout programs
- View bookings and interact with users
- Add certifications and personal information
- Respond to user feedback
- Manage client history and progression

### 🛠️ Admin Panel (optional)
- Manage all users and coaches
- Moderate feedback and programs
- View usage statistics and analytics

## 🧱 Tech Stack

- **Frontend**: [Next.js](https://nextjs.org/), React, Tailwind CSS
- **Backend**: Node.js, Express.js (or Next.js API routes)
- **Database**: MongoDB with Mongoose
- **Auth**: JWT (JSON Web Tokens)
- **Styling**: Tailwind CSS
- **Charts**: Recharts or Chart.js
- **Payments (optional)**: Stripe
- **Image Uploads (optional)**: Cloudinary / Firebase / AWS S3

## 📁 Folder Structure (example)

/client /components /pages /styles /utils /server /controllers /models /routes /middleware /config .env.local README.md


## 🧪 Installation & Setup

## 🧪 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/coach-nutrition-app.git
cd coach-nutrition-app
```

### 2. Install Dependencies

Using **Yarn**:

```bash
yarn install
```

Or using **npm**:

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env.local` file at the root of your project and add the following:

```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
NEXT_PUBLIC_BASE_URL=http://localhost:3000
```

### 4. Run the Development Server

```bash
npm run dev
```

The app will be running at: [http://localhost:3000](http://localhost:3000)

---

## 📌 Todo

- ✅ Set up MongoDB with Mongoose models  
- ✅ Implement JWT-based authentication  
- ✅ Create User and Coach dashboards  
- [ ] Nutrition plan system  
- [ ] Workout scheduler  
- [ ] Meal tracking with nutrient calculation  
- [ ] Booking system for coaching sessions  
- [ ] Feedback and rating system  
- [ ] Admin dashboard  
- [ ] Deploy to Vercel or another hosting platform  

---

## ✍️ Authors

- **Walid Ben Abid**  
- **Med Yassine Meriah**  
- **Yassine Mkacher**  
- **Ahmed Brahim Mekni**




