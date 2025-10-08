# Jiffy - Project Management & HR System

<div align="center">
  <img src="assets/images/Jiffy-favicon.png" alt="Jiffy Logo" width="100"/>
  
  **A comprehensive Project Management and Human Resource Management System**
  
  [![PHP](https://img.shields.io/badge/PHP-7.4+-blue.svg)](https://www.php.net/)
  [![MySQL](https://img.shields.io/badge/MySQL-5.7+-orange.svg)](https://www.mysql.com/)
  [![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
</div>

---

## 📋 Table of Contents

- [About Jiffy](#about-jiffy)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Quick Start](#quick-start)
- [Demo Credentials](#demo-credentials)
- [Modules](#modules)
- [Project Structure](#project-structure)
- [Security](#security)
- [Contributing](#contributing)
- [Support](#support)
- [License](#license)

---

## 🎯 About Jiffy

Jiffy is a powerful, all-in-one **Project Management System (PMS)** and **Human Resource Management System (HRMS)** designed to streamline organizational workflows. It provides comprehensive tools for managing projects, employees, tasks, attendance, payroll, and much more.

Whether you're a startup, educational institution, healthcare provider, or enterprise, Jiffy offers tailored solutions to meet your unique needs with seamless integration capabilities and robust security measures.

---

## ✨ Features

### 🚀 Project Management
- **Project Tracking** - Create, manage, and monitor multiple projects
- **Task Assignment** - Assign tasks to team members with deadlines
- **Module Management** - Organize projects into manageable modules
- **Progress Monitoring** - Real-time project progress tracking
- **Document Management** - Attach and manage project documents
- **Priority Management** - Set and track project priorities

### 👥 HR Management
- **Employee Administration** - Complete employee lifecycle management
- **Attendance Tracking** - Monitor work hours and login records
- **Leave Management** - Handle leave requests and approvals
- **Department Management** - Organize workforce by departments
- **Payroll Management** - Automated salary processing and payslips
- **Recruitment** - Job postings and application management

### 📊 Business Intelligence
- **Reports & Analytics** - Generate comprehensive business reports
- **Time Tracking** - Employee timesheets and time logs
- **Performance Monitoring** - Track individual and team performance
- **Client Management** - Manage clients and invoices

### 🔐 Security & Compliance
- **Role-Based Access Control** - Granular permission management
- **Data Security** - Robust security measures for sensitive data
- **Industry Compliance** - Adherence to standards and regulations
- **Audit Trails** - Complete activity logging

### 🛠️ Customization
- **Flexible Configuration** - Adapt to your unique requirements
- **Integration Ready** - Seamlessly connect with existing tools
- **Custom Workflows** - Design workflows that suit your organization
- **Multi-industry Support** - Tailored for various sectors

---

## 🛠 Technology Stack

### Backend
- **PHP** - Server-side scripting language
- **MySQL** - Relational database management system
- **PHPMailer** - Email functionality

### Frontend
- **HTML5/CSS3** - Modern web standards
- **JavaScript/jQuery** - Interactive user interfaces
- **Bootstrap** - Responsive design framework
- **AOS** - Animate On Scroll library
- **RemixIcon** - Icon library

### Additional Tools
- **CKEditor** - Rich text editor
- **DataTables** - Advanced table plugin
- **Chart.js** - Data visualization
- **Moment.js** - Date/time manipulation

---

## 📦 Installation

### Prerequisites

Before you begin, ensure you have the following installed:
- **XAMPP** (or equivalent Apache + MySQL + PHP stack)
  - PHP 7.4 or higher
  - MySQL 5.7 or higher
  - Apache Web Server
- **Web Browser** (Chrome, Firefox, Safari, or Edge)

### Installation Steps

1. **Clone or Download the Repository**
   ```bash
   git clone https://github.com/karan4533/Jiffy-new.git
   ```

2. **Move to XAMPP Directory**
   ```bash
   # For Windows
   move Jiffy-new C:\xampp\htdocs\
   
   # For Linux/Mac
   mv Jiffy-new /opt/lampp/htdocs/
   ```

3. **Start XAMPP Services**
   - Launch XAMPP Control Panel
   - Start **Apache** and **MySQL** services

4. **Create Database**
   - Open phpMyAdmin: `http://localhost/phpmyadmin`
   - Create a new database named `pms`
   - Import the database schema (if SQL file is provided)

5. **Configure Database Connection**
   - Open `include/config.php`
   - Update database credentials if needed:
     ```php
     $conn = mysqli_connect("localhost", "root", "", "pms");
     ```

6. **Set Up Demo Data (Optional)**
   - Visit: `http://localhost/Jiffy-new/add_dummy_credentials.php`
   - Click "Add Dummy Credentials" button to create test users

7. **Access the Application**
   - Homepage: `http://localhost/Jiffy-new/`
   - Login with demo credentials (see below)

---

## 🚀 Quick Start

### Step 1: Add Demo Users
Visit the following URL to add demo credentials:
```
http://localhost/Jiffy-new/add_dummy_credentials.php
```

### Step 2: Choose Your Role
Select the appropriate login portal based on your role:

- **Admin Portal**: `http://localhost/Jiffy-new/admin/`
- **Management Portal**: `http://localhost/Jiffy-new/management/`
- **Project Portal**: `http://localhost/Jiffy-new/project/`
- **Business Portal**: `http://localhost/Jiffy-new/business/`

### Step 3: Explore Features
After logging in, explore the various modules and features available for your role.

---

## 🔑 Demo Credentials

> **Note**: These are DEMO credentials for testing purposes only!

### 👑 Admin Access (Full Control)
- **Email**: `admin@demo.com`
- **Password**: `admin123`
- **URL**: `http://localhost/Jiffy-new/admin/`
- **Access**: Complete system control

### 💼 Manager Access (Management + Projects)
- **Email**: `manager@demo.com`
- **Password**: `manager123`
- **URL**: `http://localhost/Jiffy-new/management/`
- **Access**: Management and project oversight

### 📊 Project Manager (Project Management)
- **Email**: `project@demo.com`
- **Password**: `project123`
- **URL**: `http://localhost/Jiffy-new/project/`
- **Access**: Project creation and management

### 👤 Employee Access (Business Portal)
- **Email**: `employee@demo.com`
- **Password**: `employee123`
- **URL**: `http://localhost/Jiffy-new/business/`
- **Access**: Personal tasks and objectives

---

## 📚 Modules

### 1. **Management Module**
Complete workforce and organizational management with employee records, departments, and administrative controls.

### 2. **Project Management Module**
Create and manage projects with tasks, milestones, team assignments, and progress tracking.

### 3. **HR & Employee Services**
- Employee onboarding and offboarding
- Attendance tracking and reports
- Leave management system
- Performance evaluations

### 4. **Finance & Accounts**
- Payroll processing
- Salary management
- Payslip generation
- Financial reporting

### 5. **Task Management**
- Task creation and assignment
- Deadline tracking
- Priority management
- Status updates

### 6. **Time Tracking**
- Employee timesheets
- Work hour logging
- Project time allocation
- Productivity analytics

### 7. **Client Management**
- Client database
- Invoice management
- Project associations
- Communication history

### 8. **Recruitment**
- Job posting creation
- Application management
- Candidate tracking
- Interview scheduling

### 9. **Reports & Analytics**
- Custom report generation
- Business intelligence dashboards
- Export functionality (PDF, Excel)
- Data visualization

---

## 📁 Project Structure

```
Jiffy-new/
├── admin/                  # Admin panel and controls
├── management/            # Management portal
├── project/               # Project management portal
├── business/              # Employee/Business portal
├── Accounts/              # Finance and accounting module
├── assets/                # Static assets (CSS, JS, images)
├── assets2/               # Additional frontend assets
├── include/               # Configuration and shared files
├── PHPMailer/            # Email functionality
├── ckeditor/             # Rich text editor
├── vendor/               # Third-party dependencies
├── uploads/              # User uploaded files
├── resume_directory/     # Resume storage
├── pdf/                  # Generated PDF files
├── report/               # Report generation
├── index.php             # Main homepage
├── login.php             # Login page
├── register.php          # Registration page
├── modules.php           # Module listing page
├── services.php          # Services page
├── QUICK_START.txt       # Quick start guide
└── README.md             # This file
```

---

## 🔒 Security

### Production Deployment Checklist

Before deploying to production, ensure you:

1. **Remove Demo Files**
   ```bash
   rm add_dummy_credentials.php
   rm get_credentials.php
   rm test_connection.php
   ```

2. **Change All Passwords**
   - Update all default passwords to strong, unique passwords
   - Use password managers for secure storage

3. **Update Database Credentials**
   - Edit `include/config.php`
   - Use strong database passwords
   - Consider restricting database access by IP

4. **Configure Security Headers**
   - Enable HTTPS/SSL
   - Set appropriate security headers
   - Configure CORS policies

5. **Enable Error Logging**
   - Disable `display_errors` in production
   - Enable error logging to files
   - Monitor logs regularly

6. **Regular Updates**
   - Keep PHP and MySQL updated
   - Update third-party dependencies
   - Apply security patches promptly

7. **Backup Strategy**
   - Implement regular database backups
   - Store backups securely off-site
   - Test restore procedures

### Security Features

- **Password Hashing** - Secure password storage
- **SQL Injection Prevention** - Prepared statements and input sanitization
- **XSS Protection** - HTML special characters escaping
- **Session Management** - Secure session handling
- **Access Control** - Role-based permissions

---

## 🤝 Contributing

We welcome contributions to Jiffy! Here's how you can help:

### Reporting Issues
- Use the GitHub issue tracker
- Provide detailed descriptions
- Include steps to reproduce
- Add screenshots if applicable

### Pull Requests
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Coding Standards
- Follow PSR-12 coding standards for PHP
- Write clear, commented code
- Test thoroughly before submitting
- Update documentation as needed

---

## 📞 Support

### Useful Links

- **View Credentials**: `http://localhost/Jiffy-new/get_credentials.php`
- **Test Database**: `http://localhost/Jiffy-new/test_connection.php`
- **Quick Start Guide**: See `QUICK_START.txt`

### Getting Help

For support or questions:
- Check the documentation
- Review QUICK_START.txt
- Contact the development team
- Report issues on GitHub

### Industry-Specific Solutions

Jiffy provides tailored solutions for:
- 🏢 **Corporate** - Enterprise resource planning
- 🎓 **Education** - Academic institution management
- 🏥 **Healthcare** - Hospital and clinic administration
- 🏭 **Manufacturing** - Production and inventory management
- 💻 **IT Services** - Technology company workflows
- 🏛️ **Government** - Public sector management
- 🚀 **Startups** - Agile project management
- 🏗️ **Construction** - Project and resource tracking
- 🤝 **Consulting** - Client and project management

---

## 💡 Tips

1. **Start with Admin Account** - Use `admin@demo.com` to explore all features
2. **Role-Based Testing** - Each role has different access levels
3. **Password Pattern** - Demo passwords follow `[role]123` pattern
4. **XAMPP Required** - Ensure Apache and MySQL are running
5. **Browser Compatibility** - Best viewed in modern browsers

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 🙏 Acknowledgments

- Bootstrap team for the responsive framework
- CKEditor team for the rich text editor
- All contributors and users of Jiffy
- Open source community

---

## 🌟 Why Choose Jiffy?

- ✅ **All-in-One Solution** - Complete PMS and HRMS in one platform
- ✅ **Easy to Use** - Intuitive interface with minimal learning curve
- ✅ **Customizable** - Adapt to your specific business needs
- ✅ **Secure** - Enterprise-grade security measures
- ✅ **Scalable** - Grows with your organization
- ✅ **Multi-Industry** - Suitable for various sectors
- ✅ **Cost-Effective** - Open source with no licensing fees
- ✅ **Active Development** - Regular updates and improvements

---

<div align="center">
  
  **Made with ❤️ by the Jiffy Team**
  
  [Website](http://localhost/Jiffy-new/) • [Report Bug](https://github.com/karan4533/Jiffy-new/issues) • [Request Feature](https://github.com/karan4533/Jiffy-new/issues)
  
</div>
