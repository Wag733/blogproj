### Blog Project Overview

This project is a straightforward blog application developed with Django. It allows users to create, modify, delete blogs, and manage their personal profiles. Below are the primary functionalities of the project:

### Key Features

1. **User Registration and Authentication**:
   - **Registration**: Users can sign up for a new account by providing a username, email address, and password. The registration form includes validations to ensure usernames are alphanumeric, do not contain numbers, and are unique. Similarly, email addresses must be unique.
   - **Login**: Registered users can log in using their username and password. The login form ensures secure authentication before allowing access to user-specific features.

2. **Blog Management**:
   - **Create Blog**: Authenticated users can create new blog posts by entering a title and content. Each blog post is linked to the user who created it.
   - **Edit Blog**: Users can update their own blog posts, modifying the title and content as needed.
   - **Delete Blog**: Users can delete their own blog posts, permanently removing them from the application.

3. **Account and Profile Management**:
   - **Update Profile**: Users can update their profile information, including uploading a profile image, which is linked to their account.
   - **Edit Account**: Users can change their account details such as username and email address.
   - **Delete Account**: Users can delete their account, which will also delete all associated blogs and profile information.

4. **Blog Viewing**:
   - **View Blogs**: All users, including those not logged in, can view blog posts. The dashboard displays a list of all blog posts, including titles and truncated content, allowing visitors to read blogs without needing an account.

### User

The application includes a pre-created user for demonstration purposes:
- **Username**: Shruti
- **Password**: 1234#1234#

By utilizing these features, users can seamlessly create, manage, and interact with blog content, providing a comprehensive blogging platform.
