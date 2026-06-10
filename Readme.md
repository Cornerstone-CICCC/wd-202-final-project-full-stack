# WAD202 Final Project - Full Stack Real-Time Web App

**Welcome!**

This final project will help you build a full stack web application using Node.js, Express, Astro, authentication, API calls, and WebSockets.

Teams: **4-5 students**

> Once teams are created, there are no more changes to team membership.

## Submission Checklist

* Push your final code to GitHub.
* Make sure the app runs from the `main` branch.
* Include a clear `README.md`.
* Include a presentation deck.
* Hosting is **not required**.
* Hosting both frontend and backend is a **big bonus**.
* Every team member should contribute through Git commits.

## The Challenge

Build a full stack web application using:

* Astro frontend
* Node.js and Express backend
* Tailwind CSS
* MVC pattern
* Session-based authentication using cookies
* WebSockets for at least one real-time feature
* `.env` for configuration and secrets
* Server-memory data storage
* (Optional) One external API call — free APIs only

Your app should feel like a real product with users, protected pages, real-time interaction, and a clear purpose.

## Project Options

Pick **one** project. Two teams may choose the same one.

### 1. Real-Time Chat App

Log in and chat one-on-one or in group rooms.

* Direct messages and group rooms; create / join / leave rooms
* Online-users list and typing indicators
* Message history kept in server memory
* **Real-time:** live messages, presence, and typing indicators
* **Optional API:** GIPHY (GIFs) or LibreTranslate (translate messages)

### 2. Customer Support Live Chat

Visitors open a support chat; logged-in admins reply.

* Visitors are anonymous (no login). Only admins log in — the admin dashboard is the protected page.
* Public chat widget to start a chat
* Admin dashboard with a live queue of incoming chats
* Any admin can open a chat and reply; status: open → closed
* **Real-time:** visitor messages appear on the dashboard instantly; live two-way chat
* **Optional API:** ip-api.com (visitor location / timezone)

### 3. Food Ordering Dashboard

Order from a menu; orders appear on a live kitchen board.

* Menu with items and prices; cart with server-side validation
* Order history
* Kitchen board grouped by status
* **Real-time:** new orders appear instantly; status updates (Received → Preparing → Ready) push back to the customer
* **Optional API:** TheMealDB (menu items and photos)

### 4. Live Auction House

List items and bid; the highest bid and countdown update live.

* Browse auctions (item, current price, time left)
* Place bids (server checks the bid beats the current one)
* Countdown timer; auto-close and declare a winner; outbid alerts
* **Real-time:** live bid and countdown updates; outbid and winner notifications
* **Optional API:** Frankfurter (currency) or Unsplash (images)

### 5. Social Media / Blog Feed

Log in, write blog posts, and see them on a shared feed.

* Create posts (title + body); feed of posts, newest first
* Profile pages; follow / unfollow; likes and comments
* **Real-time:** new posts and notifications appear on the feed live
* **Bonus:** attach images to posts; curate the feed by who you follow
* **Optional API:** Unsplash (images) or DiceBear (avatars)

## Minimum Requirements

Your project must include:

### Frontend

* Astro frontend
* Multiple pages or views
* Tailwind CSS styling
* Responsive design
* Clean component structure

### Backend

* Node.js and Express backend
* MVC structure
* Separate routes, controllers, and data/model files
* Server-side validation for important forms

### Authentication

* User registration
* User login
* User logout
* Session cookies
* Protected routes
* User-specific dashboard or page
* All logged-in users have the same permissions — no admin or role tiers (keep it simple)

### WebSockets

Use WebSockets for at least one meaningful real-time feature, such as:

* Live chat
* Live notifications
* Live leaderboard
* Live order updates
* Live task updates
* Live voting or polling

### Other Requirements

**Data**

* A database is **not required**.
* Data may be stored in server memory using arrays or objects.
* It is acceptable if data resets when the server restarts.

**API Calling**

* Using an external API is **optional**.
* If you use one, it must be a **free** public API.

**Environment Variables**

* Use `.env` for secrets or config values.
* Do not commit `.env` to GitHub.
* Include a `.env.example` file with placeholder values.

Example:

```txt
PORT=3000
SESSION_SECRET=your_session_secret_here
API_KEY=your_api_key_here
```

## Time Management

The project timeline is limited, so plan carefully before coding.

Your team should clearly decide:

* How much time to spend on setup
* How much time to spend on UI design
* Who is responsible for each feature
* Which features are required vs optional
* When coding should stop so testing and presentation work can begin

Do not spend too much time making the UI perfect at the start. Build the core functionality first, then improve the design.

Recommended priority:

1. Project setup and task distribution
2. Authentication
3. Main pages and core features
4. WebSocket functionality
5. API integration
6. UI polish and responsive design
7. Testing and presentation preparation

## Git Control

* Protect the `main` branch.
* Work on feature branches.
* Push regularly.
* Use clear commit messages.
* Pull often to avoid conflicts.
* Do not commit `.env` or `node_modules`.

## Presentation Requirements

Each team must present for about **~15 minutes**. (QA Time 5-10mins additional)

Start your presentation with the **live demo first**. After the demo, explain the rest of the project.

Your presentation should include:

* Demo of the working app
* What your app does
* Who the users are
* Main features
* Tech stack
* Authentication flow
* WebSocket feature
* API integration
* Team member contributions
* Challenges faced
* What you would improve with more time

Every team member should speak.

## Marking Criteria

Your final project will be evaluated based on:

* Functionality
* Full stack structure
* Project structure (clean MVC organization)
* Authentication
* WebSocket implementation
* API integration (if used)
* Code quality and readability
* UI/UX
* Responsiveness
* GitHub contribution history
* Teamwork
* Error handling
* Presentation quality

> GOOD Luck!
