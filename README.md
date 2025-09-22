## Team - THE SKY


# SoulNect

HopeWell is a soulful mental well-being web app that helps users reconnect with themselves through mood tracking, journaling, meditation, and minimal community engagement. After being shelved for two years, the project was finally revived with a refreshed experience focused on mindfulness and emotional resilience.



## 🔗 Repository Links



## 🌟 Features

* **Mood Logging**: Pick how you feel and track your emotional patterns.
* **Mood Dashboard**: See your mood trends over time in a gentle, visual way.
* **Journal**: A clean, distraction-free space to write, reflect, and revisit thoughts.
* **Meditation Sessions**: Choose from soothing ambiences and durations with guided breath prompts.
* **Streak System**: Encouragement to show up consistently, without pressure.
* **Community**: Share thoughts, respond to others, and explore a simple, safe public space.

## 🛠️ Technologies Used

* **Frontend**: React.js, TailwindCSS, Framer Motion
* **Backend**: Node.js, Express.js (Not open sourced)
* **Database**: MongoDB (Mongoose)
* **Authentication**: JWT + bcrypt
* **Deployment**: Vercel



### User

* `POST /signup`
* `POST /signin`

### Mood Logs

* `GET /moodlog/latest/:userId`
* `GET /moodlog/:userId`
* `POST /moodlog`
* `GET /moodlog/streak/:userId`

### Journals

* `POST /journal`
* `GET /journal/:userId`
* `DELETE /journal/:id`

### Meditation

* `POST /meditation/log`
* `POST /meditation/log/mood`
* `GET /meditation/logs/:userId`
* `GET /meditation/streak/:userId`

### Community

* `GET /post`
* `POST /post`
* `GET /post/:postId`
* `POST /comment`
* `GET /comment/:postId`

## 🔐 Authentication

Secure JWT-based login with password hashing.
