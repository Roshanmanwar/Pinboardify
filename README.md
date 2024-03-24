# Project Title  : Pinbordify
<img src="https://github.com/Roshanmanwar/Pinboardify/blob/main/Screenshots/profile.JPG"/>

Pinbordify is a social media platform project built with Express, Node.js, MongoDB, and Pug template engine. It allows users to create accounts, share posts, interact with posts through likes, manage their profiles, and explore a feed of posts from other users.

## Features

- **User Authentication**: Users can register, log in, and log out securely using session-based authentication.
- **Profile Management**: Users can view and update their profiles, including changing profile pictures.
- **Post Creation and Management**: Users can create, edit, and delete their own posts.
- **Post Interactions**: Users can like  the posts.
- **Feed Page**: Users can view a feed of posts from all users.
- **Responsive Design**: The application is designed to be usable across various devices.

## Technologies Used

- **Backend**: Node.js, Express.js
- **Database**: MongoDB , mongoose
- **Session Management**: Express-session, 
- **Templating Engine**: Pug 
- **Frontend Styling**: CSS, Bootstrap 
- **File Uploads**: Multer middleware


# Register Page
<img src="https://github.com/Roshanmanwar/Pinboardify/blob/main/Screenshots/register.JPG"/>

To start using Pinbordify, you'll need to create a new account by registering. This process involves providing some basic information and ensuring that your email address is unique within our system.

Instructions
-  New User Registration: If you're new to Pinbordify, follow these steps to create a new account:

Navigate to the Registration Page.
-  Fill out the registration form by entering your name, email address, desired username, and password.
-  Click on the "Register" button to submit the form.
-  email Verification: After submitting the registration form, you may need to verify your email address. Check your inbox for a verification email from Pinbordify and follow the instructions provided to verify your email.

-  Redirect to Login: Once your registration is successfully completed, you'll be automatically redirected to the Login Page. Here, you can use the credentials you provided during registration to log in to your newly created account.

Notes
-  Unique Email Address: Make sure to provide a unique email address during registration. If the email address you enter is already registered in Pinbordify, you'll need to use a different email address.

-  Password Security: Choose a strong and secure password to protect your account from unauthorized access. Avoid using easily guessable passwords and consider using a combination of letters, numbers, and special characters.


# Login Page.
<img src="https://github.com/Roshanmanwar/Pinboardify/blob/main/Screenshots/pinbordify-login.JPG"/>

The Pinbordify Login page allows users to access their accounts by providing their registered email address and password.

Instructions
-  Accessing the Login Page: Navigate to the Login Page of Pinbordify.

-  Entering Credentials: Enter your registered email address and password in the provided fields.

-  Logging In: Click on the "Login" button to submit your credentials and access your account.

Notes
-  Correct Credentials: Make sure to enter the correct email address and password that you provided during the account registration process.

-  Error Handling: If the email and password entered do not match the records in our system, an error message will be displayed. Please double-check your credentials and try again.



# Profile Page
<img src="https://github.com/Roshanmanwar/Pinboardify/blob/main/Screenshots/profile.JPG"/>
<img src="https://github.com/Roshanmanwar/Pinboardify/blob/main/Screenshots/your post.JPG"/>

The Authorized User Page is accessible only to authorized users who have successfully logged in to their accounts. It provides various features for managing user profiles, uploading posts, and interacting with other users' posts.

Features
-  Profile Picture Update: Authorized users can update their profile pictures directly from this page.

-  Post Upload: Users can upload new posts, including images and descriptions, to share with others.

-  Logout: The "Logout" button allows users to securely log out of their accounts.

-  Feed Navigation: Users can navigate to the feed page to view posts from other users.

-  View Your Posts: Users can see the posts they have uploaded to the platform.

-  Delete Posts: Authorized users can delete their own posts if they wish to remove them from the platform.

-  Post Likes: Users can see how many people have liked their posts.

Instructions
-  Updating Profile Picture: Click on the profile picture icon to update your profile picture.

-  Uploading Posts: Use the provided interface to upload new posts, including images and descriptions.

-  Logout: Click on the "Logout" button to securely log out of your account.

-  Navigating to Feed: Use the "Feed" button to navigate to the feed page to view posts from other users.

-  Managing Your Posts: On the authorized user page, you can view and delete your own posts as needed.

-  Viewing Likes: See how many people have liked your posts displayed alongside each post.

Notes
-  Authorization: Access to this page is restricted to authorized users who have successfully logged in to their accounts.

-  Post Management: Users have control over the posts they upload, including the ability to delete them if desired.


# Feed Page

<img src="https://github.com/Roshanmanwar/Pinboardify/blob/main/Screenshots/post 1.JPG"/>
<img src="https://github.com/Roshanmanwar/Pinboardify/blob/main/Screenshots/post 2.JPG"/>

The Feed Page allows users to browse through posts uploaded by other users. Users can view posts, interact with them by liking them, and engage with the Pinbordify community.

Features
-  Browse Posts: Users can scroll through the feed to browse posts uploaded by other users.

-  View Other Users' Posts: The feed displays posts uploaded by other users, allowing users to discover new content and engage with the Pinbordify community.

-  Like Posts: Users can like posts to show appreciation for the content uploaded by other users.

Instructions
-  Accessing the Feed Page: Navigate to the Feed Page of Pinbordify to start browsing posts.

-  Browsing Posts: Scroll through the feed to view posts uploaded by other users. Each post may include images, descriptions, and other details provided by the user who uploaded it.

-  Interacting with Posts: Users can interact with posts by liking them. Simply click on the "Like" button associated with a post to add a like.

Notes
-  Community Engagement: The feed page encourages community engagement by allowing users to discover and interact with content uploaded by other users.

-  Liking Posts: Liking posts is a way to show appreciation for the content and support fellow users within the Pinbordify community.



## Installation

1. Clone the repository:

-  git clone https://github.com/Roshanmanwar/pinbordify

2. Install dependencies:
-  npm install

3. PORT=3050
-  MONGODB_URI=mongodb://localhost:27017/PINTREST

4. start
-  npm start

5. Visit
-  `http://localhost:3050` in your web browser to view the application.





   



