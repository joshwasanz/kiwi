# Kiwi

![Kiwi Logo](https://via.placeholder.com/200x80?text=Kiwi)

Welcome to **Kiwi**, a dynamic marketplace platform where individuals can create, sell, and purchase online courses. Whether you are an educator looking to share your expertise or a learner seeking new skills, Kiwi connects you with the tools and content you need.

## Features

- **Course Creation:** Instructors can easily create and manage their courses with rich content tools.
- **Secure Payments:** Integrated payment system for smooth transactions.
- **User-Friendly Search:** Discover courses based on topics, ratings, and reviews.
- **Interactive Learning:** Engage with instructors and other learners through discussion forums.
- **Customizable Profiles:** Showcase your skills and achievements

## Installation

Follow these steps to set up the Kiwi platform locally:

### Prerequisites

- Node.js (v16+ recommended)
- Python (v3.8+ recommended)
- PostgreSQL
- Git

### Steps

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/kiwi.git
   cd kiwi
   ```

2. **Set Up the Backend:**
   - Navigate to the `backend` folder:
     ```bash
     cd backend
     ```
   - Create and activate a virtual environment:
     ```bash
     python -m venv venv
     source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
     ```
   - Install dependencies:
     ```bash
     pip install -r requirements.txt
     ```
   - Create a PostgreSQL database named `kiwi`.
   - Update the database configuration in `.env`:
     ```
     DB_HOST=localhost
     DB_PORT=5432
     DB_USER=yourusername
     DB_PASSWORD=yourpassword
     DB_NAME=kiwi
     ```
   - Run migrations:
     ```bash
     python manage.py migrate
     ```
   - Start the Django development server:
     ```bash
     python manage.py runserver
     ```

3. **Set Up the Frontend:**
   - Navigate to the `frontend` folder:
     ```bash
     cd ../frontend
     ```
   - Install dependencies:
     ```bash
     npm install
     ```
   - Start the Next.js development server:
     ```bash
     npm run dev
     ```

4. **Access the Application:**
   - Backend: [http://localhost:8000](http://localhost:8000)
   - Frontend: [http://localhost:3000](http://localhost:3000)

## Technologies Used

- **Frontend:** React, Next.js, Tailwind CSS
- **Backend:** Django
- **Database:** PostgreSQL
- **Authentication:** JWT-based authentication

## Contributing

Contributions are welcome! Follow these steps to contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push your branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

Please adhere to the [Code of Conduct](CODE_OF_CONDUCT.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Inspired by platforms like Udemy.
- Thanks to the open-source community for their tools and contributions.

## Connect with Us

- **Website:** [https://kiwi.dev](https://kiwi.dev)
- **Twitter:** [@kiwi_dev](https://twitter.com/kiwi_dev)
- **Discord:** [Join the Community](https://discord.gg/your-invite-code)

---

Empower Learning, Empower Yourself! 🥝
