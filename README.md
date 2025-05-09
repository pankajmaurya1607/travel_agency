# 🌍 Travel Agency

A modern, full-stack React application for planning and managing travel experiences.

![Travel Agency Banner](https://images.unsplash.com/photo-1503220317375-aaad61436b1b?ixlib=rb-4.0.3&q=85&fm=jpg&crop=entropy&cs=srgb&w=1200)

## ✨ Live Demo

Visit our website: [Travel Agency](https://travel-agency-nu-seven.vercel.app/)

## 🚀 Features

- **Interactive Trip Planning** - Create and customize your travel itineraries
- **User Authentication** - Secure login and registration system
- **Responsive Design** - Beautiful UI that works on all devices
- **Real-time Updates** - Stay informed about your travel plans
- **AI-Powered Recommendations** - Get personalized travel suggestions using Gemini AI
- **Rich Media Integration** - Beautiful imagery from Unsplash API
- **Data Visualization** - Powered by Syncfusion components

## 🛠️ Technology Stack

- **Frontend**: React, React Router, TailwindCSS
- **Backend**: Appwrite (BaaS)
- **AI Integration**: Google Gemini API
- **Image API**: Unsplash
- **UI Components**: Syncfusion
- **Deployment**: Vercel

## 🏁 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:

```bash
git clone https://github.com/pankajmaurya1607/travel_agency.git
```

2. Navigate to the project directory:

```bash
cd travel_agency
```

3. Install dependencies:

```bash
npm install
```

4. Create a `.env.local` file with your API keys (see example below)

5. Start the development server:

```bash
npm run dev
```

Your application will be available at `http://localhost:5173`.

## 🔑 Environment Variables

Create a `.env.local` file in the root directory with the following variables:

```
# Syncfusion 
VITE_SYNCFUSION_LICENSE_KEY=your_syncfusion_key

# Appwrite
VITE_APPWRITE_PROJECT_ID=your_project_id
VITE_APPWRITE_API_KEY=your_api_key
VITE_APPWRITE_DATABASE_ID=your_database_id
VITE_APPWRITE_USERS_COLLECTION_ID=your_users_collection_id
VITE_APPWRITE_TRIPS_COLLECTION_ID=your_trips_collection_id
VITE_APPWRITE_API_ENDPOINT=https://fra.cloud.appwrite.io/v1

# Gemini
GEMINI_API_KEY=your_gemini_api_key

# Unsplash
UNSPLASH_ACCESS_KEY=your_unsplash_access_key
```


## 🎨 Styling

This project uses [Tailwind CSS](https://tailwindcss.com/) for styling, providing a clean and responsive user interface.


## 👨‍💻 Author

**Pankaj Maurya**
- GitHub: [pankajmaurya1607](https://github.com/pankajmaurya1607)

---

Built with ❤️ using React, React Router, and Appwrite.
