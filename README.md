# SPMB — Sistem Penerimaan Murid Baru

Web-based student admissions and online registration management portal built with **Laravel 12** and **Bootstrap 5**.

SPMB simplifies the student enrollment process by providing a centralized dashboard for applicants and administrative staff, replacing manual paper-based admissions with a digital workflow.

---

## Features

- **Applicant Registration & Authentication**: Secure registration and login for prospective students with credential validation.
- **Admissions Dashboard**: Centralized dashboard displaying registration status, announcements, and application progress.
- **Verification Workflow**: Administrative interface for admissions officers to review submitted applicant data and documents.
- **Reporting & Data Export**: Export candidate rosters and admission statistics to PDF and spreadsheet formats for administrative records.
- **Responsive Interface**: Mobile-friendly UI styled with Bootstrap 5 for access across desktop and mobile devices.

---

## Tech Stack

- **Framework**: Laravel 12
- **Backend**: PHP 8.2+
- **Frontend**: Blade Templates, Bootstrap 5.3
- **Database**: SQLite (Default / Development) / MySQL
- **Testing**: Pest PHP / PHPUnit

---

## Getting Started

### Prerequisites

- PHP >= 8.2
- Composer
- Node.js & NPM
- SQLite or MySQL

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/MasterPandaa/SPMB.git
   cd SPMB
   ```

2. **Install PHP dependencies**:
   ```bash
   composer install
   ```

3. **Install frontend dependencies**:
   ```bash
   npm install && npm run build
   ```

4. **Environment setup**:
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

5. **Run database migrations**:
   ```bash
   php artisan migrate
   ```

6. **Start the local development server**:
   ```bash
   php artisan serve
   ```
   Visit `http://127.0.0.1:8000` in your browser.

---

## License

This project is open-source and licensed under the [MIT License](LICENSE).
