# Grapevine - A Social Media and Microblogging App

## About

Grapevine is a social media and microblogging app similar to Twitter. Users can make posts on this platform and like each other's platforms. These posts may include media such as images. Additionally, users can friend or unfriend other users. Users can also view the profiles of specific users and the posts exclusive to that user. Each user on the platform has their own account that they must register first before being able to login. Once logged in, users are only authorized to their account's permissions (making posts, adding/removing friends, etc.).

## Technologies/Modules Used

- MERN stack: MongoDB stores users & posts and an Express app is serving a REST API to a Vite (React) frontend
- Designed the UI into individual, reusable widgets by incorporating MUI components
- Utilized JSON Web Tokens to authenticate and authorize user accounts when logging in
- Mangaged authorization global states via Redux to ensure each account's home page is personalized
- Modeled the login/registration forms with Formik and defined validation schemas with Yup


![image](https://github.com/edisonwang03/grapevine-social-media/assets/49788106/2a6331ce-cc43-47b6-a3b1-a5792041a2a9)
