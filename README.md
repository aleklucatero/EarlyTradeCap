  <h3 align="center">Early Trade</h3>


Explore social media tailored towards day traders with this user-friendly platform that has a nice look and lots of features. Easily create and explore posts, and enjoy a strong authentication system and quick data fetching using React Query for a smooth user experience.

Tech Stack:

- React.js
- Appwrite
- React Query
- TypeScript
- Shadcn
- Tailwind CSS



Some of the features:
- A robust authentication system ensuring security and user privacy

- Homepage for users to explore posts, with a featured section for top creators

- Enable users to like and save posts, with dedicated pages for managing liked and saved content

- A detailed post page displaying content and related posts for an immersive user experience

- A user profile page showcasing liked posts and providing options to edit the profile

- Allow users to browse and explore other users' profiles and posts

- Implement a user-friendly create post page with effortless file management, storage, and drag-drop feature

- Provide users with the ability to edit the content of their posts at any time

- A responsive UI with a bottom bar, enhancing the mobile app feel for seamless navigation

- Incorporate the React Query (Tanstack Query) data fetching library for, Auto caching to enhance performance, Parallel queries for efficient data retrieval, First-class Mutations, etc

- Utilize Appwrite as a Backend as a Service solution for streamlined backend development, offering features like authentication, database, file storage, and more
 

-----------------------------------------


Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/aleklucatero/EarlyTradeCap.git
cd ET
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
VITE_APPWRITE_URL=
VITE_APPWRITE_PROJECT_ID=
VITE_APPWRITE_DATABASE_ID=
VITE_APPWRITE_STORAGE_ID=
VITE_APPWRITE_USER_COLLECTION_ID=
VITE_APPWRITE_POST_COLLECTION_ID=
VITE_APPWRITE_SAVES_COLLECTION_ID=
```

Replace the placeholder values with your actual Appwrite credentials. You can obtain these credentials by signing up on the [Appwrite website](https://appwrite.io/).

**Running the Project**

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.
