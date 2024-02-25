## Key Features

1. **User Authentication:**
   - Secure user registration and login system.
   - Passwords are securely hashed using Django's authentication system.

2. **Profile Management:**
   - Users can create and update their profiles with a bio, location, and profile image.
   - Profile images are stored and served using Django's media handling.

3. **Post Management:**
   - Users can upload posts with images and captions.
   - Posts are stored in the database and linked to user profiles.

4. **Interaction:**
   - Users can like and unlike posts.
   - Follow and unfollow other users to customize their home feed.

5. **Home Feed:**
   - Displays posts from users that the current user is following.
   - Own posts are also visible in the home feed.

6. **Explore Page:**
   - Users can discover new content by exploring posts from all users.

7. **Search:**
   - Search functionality allows users to find other users and posts.

8. **Multi-User Support:**
   - The platform is designed to support multiple users concurrently.
   - Each user has a unique profile, posts, and interactions.

## Project Structure
mediaapp
│
├── manage.py
│
├── userauth/
│   ├── __init__.py
│   ├── admin.py
│   ├── migrations/
│   │   └── ...
│   ├── models.py
│   ├── tests.py
│   └── views.py
│
├── templates/
|   ├── edit_profile.html
│   ├── base.html
│   ├── main.html
│   ├── explore.html
│   ├── profile.html
│   ├── search_user.html
│   ├── loginn.html
|   ├── modal.html
|   ├── profile_upload.html
|   ├── base.html
|   ├── search.html
|   └── signup.html
│
├── media/
│   ├── post_images/
|   ├── profile_images/
│   └── blank-profile-picture
│
├── static/
│   ├── css/
│   │   └── app.css
│   ├── js/
│       └── app.js
│   
├── socialmedia/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
|   ├── asgi.py
│   └── wsgi.py
│
└── db.sqlite3

