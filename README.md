## About The Project

![Screenshot from 2024-12-14 10-54-57](https://github.com/user-attachments/assets/21a5357d-9bd7-4e0c-813e-d361da1bafd2)

This task management app was created to streamline the organization of projects and tasks, providing a collaborative platform inspired by tools like Trello and Jira. It allows users to create projects, manage tasks across multiple statuses, and collaborate in real-time with team members.

### Key Features

- **Secure Authentication**: Includes registration, login, email confirmation, and middleware validation.
- **Collaborative Features**: Users can invite collaborators, assign roles (manager, collaborator), and track task progress across five statuses: Pending, On Hold, In Progress, Under Review, and Completed.
- **Comprehensive CRUD Functionality**: Every project and task can be created, viewed, updated, or deleted with ease.
- **Advanced Task Management**: Features include a change history and threaded comments for every task.

### Built With

This app was designed to be both scalable and user-friendly, offering a modern solution to task and project management.

- [Express](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [React](https://reactjs.org)
- [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vite.dev/)
- [TailwindCSS](https://tailwindcss.com/)


## Usage

For those interested in how the project works without having to install it, here are some screenshots showcasing its key features:  

*Login / Register pages*  
![Screenshot from 2024-12-14 10-53-14](https://github.com/user-attachments/assets/8f0f0da3-6b17-49ee-9e38-fddb90ae2b5d)

*Confirm account*  
![Screenshot from 2024-12-14 10-58-33](https://github.com/user-attachments/assets/d7a8390d-e85b-4465-9f03-6f4dda3af99e)
![Screenshot from 2024-12-14 11-08-21](https://github.com/user-attachments/assets/803f21ff-aac7-464e-ba06-0dc2d76a2c38)

*Manage your projects*  
![Screenshot from 2024-12-14 10-54-35](https://github.com/user-attachments/assets/ab1a080b-5fb0-4ee9-b6d5-13f678760977)
![Screenshot from 2024-12-14 10-54-44](https://github.com/user-attachments/assets/7c81fcdc-c5db-48d7-966d-9de0ebf01a07)

*Enter in your project*  
 ![Screenshot from 2024-12-14 10-54-57](https://github.com/user-attachments/assets/ab0f043f-da68-4dad-b507-3c38a02a713e)

*Create tasks* 
![Screenshot from 2024-12-14 10-55-21](https://github.com/user-attachments/assets/ffe38738-55dc-49a5-a25f-1ddc92a1438a)

*Add collaborators* 
![Screenshot from 2024-12-14 10-55-30](https://github.com/user-attachments/assets/96bc0558-9967-489f-9bc3-ecfe3efce93d)
![Screenshot from 2024-12-14 11-06-14](https://github.com/user-attachments/assets/3ed3b5cc-8bc9-4a68-b8eb-e553571e6538)

*Add notes and check logs of a task*
![Screenshot from 2024-12-14 11-07-28](https://github.com/user-attachments/assets/e5c067aa-6fe1-4633-b1fc-323fe0ad8d89)

*Update your profile data* 
![Screenshot from 2024-12-14 10-55-49](https://github.com/user-attachments/assets/5544d17b-013e-4a33-b5cd-9d8c3a73cbfe)
![Screenshot from 2024-12-14 10-55-55](https://github.com/user-attachments/assets/44033f9a-8bce-4f3a-84bf-9161486ec5bd)


## Getting Started

Follow the steps below to set up the project locally:

### Prerequisites

To get started first you will need to install the following:

- NodeJS
- npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Get a free API Key at [MongoDB](https://www.mongodb.com/es/cloud/atlas/register)
2. Get a free API Key at [MailTrap](https://mailtrap.io/es/)
3. Clone the repo
   ```sh
   git clone https://github.com/DaniGarridoNunez/planify_frontend.git
   ```
4. Install NPM packages in both /frontend and /backend
   ```sh
   npm install
   ```
5. Enter your API keys in `.env` at /backend for example:
   ```js
   DATABASE_URL=mongodb+srv://root:<db_password>@cluster0.example.mongodb.net/planify_mern
   FRONTEND_URL=http://localhost:5173
   SMTP_HOST=sandbox.smtp.mailtrap.io
   SMTP_PORT=2525
   SMTP_USER=yourusername
   SMTP_PASS=yourpassword
   JWT_SECRET=palabrasupersecreta
   ```
6. Enter your API keys in `.env.local` at /frontend:
    ```js
    VITE_API_URL=http://localhost:4000/api
    ```
7. And then run in both /frontend and /backend:
   ```sh
   npm run dev
   ```

   
## Roadmap

- [x] Add collaboration support
- [x] Add user roles in projects
- [ ] Improve the Drag & Drop experience
- [ ] Multi-language Support
  - [x] Spanish
  - [ ] English

See the [open issues](https://github.com/DaniGarridoNunez/planify_frontend/issues) for a full list of proposed features (and known issues).

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git switch -c feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See [MIT License](https://opensource.org/licenses/MIT) for more information.

## Contact

Daniel Garrido - danigarridonunez@gmail.com - [LinkedIn Profile](https://www.linkedin.com/in/daniel-garrido-87b041223/)
