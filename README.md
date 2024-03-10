# 📓 Notion Clone (Notes taking app)

#### Create and Edit Notes like in Notion

## Features

- **Slash Commands** (Type `/` to turn the block into different content types)
- **HTML Support** (Use regular HTML tags like `<a>` in text blocks)
- **Image Support** (Upload images by using the `/image` command)
- **Drag And Drop** (Reorder blocks easily by drag and drop)
- **Guest Editing** (Anyone can create public pages and share them via link)
- **User Management** (Create an account to create private pages)
- **Scheduled Jobs** (Delete inactive pages and accounts automatically)

## Tech Stack

The frontend is built with Next.js and fully server-side rendered. On the backend, a REST API handles saving user content and user management.

#### Frontend

Next.js · React.js · SCSS/SASS

#### Backend

Express.js · MongoDB with Mongoose · Nodemailer · JWT (Cookie-based)