<p align="center">
  <img src="assets/banner.svg" alt="SPMB Admissions SaaS Banner" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Framework-Laravel-FF2D20?style=flat-square&logo=laravel" alt="Laravel">
  <img src="https://img.shields.io/badge/Model-Multi--Tenant_SaaS-0284C7?style=flat-square" alt="Multi-Tenant">
  <img src="https://img.shields.io/badge/Exports-PDF_|_Excel_Reports-10B981?style=flat-square" alt="Exports">
  <img src="https://img.shields.io/badge/Sector-EdTech_Admissions-D97706?style=flat-square" alt="EdTech">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-gray?style=flat-square" alt="License"></a>
</p>

## Overview

Institutional student admissions frequently overwhelm administrative personnel with unverified document submissions, manual data entry, and fragmented reporting. Developed for **Life Media**, this multi-tenant student admission management portal built on **Laravel** digitizes registration, document validation, and institutional admissions reporting.

---

## Core Capabilities

- **Multi-Tenant Architecture**: Supports multiple school branches and academic programs under distinct tenant configuration boundaries.
- **Document Verification Workflow**: Web interface for administrative officers to inspect, verify, or request revision of applicant diplomas and certificates.
- **Automated Reporting Suite**: Generates printable PDF registration confirmation cards and multi-column Excel spreadsheets for entrance exam scheduling.
- **Applicant Progress Tracking**: Interactive registration timeline allowing applicants to track submission verification, exam schedules, and announcement results.

---

## Quickstart

```bash
git clone https://github.com/MasterPandaa/SPMB.git
cd SPMB
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve
```

---

## License

This project is licensed under the [MIT License](LICENSE).
