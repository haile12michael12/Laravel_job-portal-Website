# 💼 Laravel Job Portal Website

A modern, full-featured **Job Portal** built with **Laravel 10.x**. This platform connects employers and job seekers through a dynamic and user-friendly interface, offering job listings, applications, company profiles, and user dashboards.

---

## 🚀 Features

✅ **User Roles:**
- 👨‍💼 Employer: Post and manage job listings.
- 👩‍💻 Job Seeker: Browse and apply for jobs.
- 🛠️ Admin: Manage users, jobs, and site content.

✅ **Job Listings**
- Full-time, Part-time, Freelance, Remote
- Job filtering by category, location, salary, and keywords
- Job bookmarking and saving

✅ **Employer Tools**
- Create and manage company profile
- Post/edit/delete job listings
- View applicants for each job

✅ **Job Seeker Tools**
- Build/edit resume (CV) and profile
- Apply to jobs with 1-click
- Track applications in a personal dashboard

✅ **Admin Dashboard**
- User management
- Job approval system
- Category, location, and role management
- Analytics & reporting

✅ **Additional Features**
- Email notifications (job alerts, application confirmations)
- SEO-friendly URLs
- Responsive design
- Rich text job descriptions with Markdown/CKEditor

---

## 🛠️ Tech Stack

- **Backend:** Laravel 10
- **Frontend:** Blade Templates / Bootstrap / Tailwind CSS
- **Authentication:** Laravel Breeze / Jetstream
- **Database:** MySQL / PostgreSQL
- **Email:** Laravel Mail (Mailgun, SMTP, etc.)
- **Others:** Laravel Policies, Queues, RESTful APIs

---

## 📦 Installation


# Clone the repo
git clone https://github.com/your-username/laravel-job-portal.git
cd laravel-job-portal

# Install dependencies
composer install
npm install && npm run dev

# Environment setup
cp .env.example .env
php artisan key:generate

# Set your database credentials in .env
# Run migrations and seeders
php artisan migrate --seed

# Serve the app
php artisan serve

## 📁 Project Structure
app/Models - Eloquent models (User, Job, Application, etc.)

app/Http/Controllers - Controller logic

resources/views - Blade templates for UI

routes/web.php - Web routes

database/migrations - DB schema definitions

## 🌐 Screenshots
## 📄 License
This project is open-source and available under the MIT license.

🙌 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss your idea.
