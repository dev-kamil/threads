# Threads
## About the project
This is clone of the Instagram's new text app.

## Installation
* Clone the repository
* Sign up on [Clerk](https://clerk.com) and set-up a project
* Set-up a MongoDB account
* Set-up an [uploadthing](https://uploadthing.com) account

## Secrets format
To make the application work properly, you need to create an `.env.local` file in the root directory in the following format.
```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=

CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

DB_USER=
DB_PASS=
MONGODB_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=
```

## Credits
[Build and Deploy a Full Stack MERN Next.js 13 Threads App](https://youtu.be/O5cmLDVTgAs?si=wG9uedhXF9byjUqw)
