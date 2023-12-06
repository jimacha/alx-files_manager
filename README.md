# 0x04. Files Manager

## Overview

Welcome to my Files Manager project, where I'm diving deep into the realm of back-end development. Throughout this learning journey, I'll be immersing myself in various technologies and concepts to build a robust file management platform. By the end of this project, my goal is to articulate the intricacies of the following concepts confidently:

## Learning Objectives

1. **Creating an API with Express:**
   - **Example:** Setting up routes for file operations (e.g., upload, view, permissions) using ExpressJS, simplifying communication between the front-end and back-end.

2. **User Authentication:**
   - **Example:** Implementing token-based authentication using JSON Web Tokens (JWT), ensuring secure access to the file management system.
   
3. **Data Storage in MongoDB:**
   - **Example:** Designing and implementing MongoDB schemas for storing file metadata, exploring the benefits of NoSQL in handling diverse file types.

4. **Temporary Data Storage in Redis:**
   - **Example:** Using Redis to cache frequently accessed file information, reducing database queries and improving overall application performance.

5. **Setting up and Using a Background Worker (Kue):**
   - **Example:** Integrating Kue as a background worker to asynchronously generate thumbnails for uploaded images, preventing delays in file viewing.

## Technologies I'm Using

- **JavaScript (ES6):** Leveraging the modern syntax of ECMAScript 6 for cleaner and more readable code.
  
- **NoSQL Database (MongoDB):** Utilizing MongoDB for its schema-less structure, facilitating the storage of file metadata.
  
- **In-memory Data Store (Redis):** Employing Redis for efficient caching, optimizing the retrieval of frequently accessed file information.
  
- **NodeJS:** Harnessing the power of NodeJS for scalable server-side JavaScript execution.
  
- **ExpressJS:** Streamlining API development with ExpressJS, creating a flexible and minimalistic web application framework.
  
- **Kue (Background Processing):** Integrating Kue to handle background tasks such as thumbnail generation, ensuring a seamless user experience.

## Features I'm Building

1. **User Authentication via Token:**
   - **Example:** Generating and validating JWTs to authenticate users, securing the file management API.

2. **File Listing:**
   - **Example:** Designing an API endpoint to retrieve a paginated list of all uploaded files, enhancing navigation for users.

3. **File Upload:**
   - **Example:** Implementing a file upload mechanism, supporting various file types (e.g., images, documents) and ensuring proper error handling.

4. **Permission Management:**
   - **Example:** Allowing users to modify file permissions, controlling access and facilitating secure file sharing.

5. **File Viewing:**
   - **Example:** Creating an API endpoint for viewing files, supporting different file types and providing a seamless viewing experience.

6. **Thumbnail Generation for Images:**
   - **Example:** Utilizing Kue for background processing to generate thumbnails for uploaded images, enhancing user interaction.

## Implementation Guidelines

While I'll be following step-by-step guidance, I'm excited to inject creativity into the process. For example, I might experiment with different authentication strategies, explore advanced MongoDB querying, or optimize Redis caching strategies based on real-world scenarios. This project isn't just about following instructions; it's about hands-on exploration and understanding. Happy coding, and let's make this learning journey memorable!