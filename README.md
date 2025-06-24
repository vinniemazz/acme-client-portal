# Acme Client Portal

Enterprise client portal application providing secure access to project status, deliverables, and billing information.

## Features
- Secure client authentication
- Project dashboard with real-time updates
- Document management system
- Billing and invoice portal
- Support ticket system

## Tech Stack
- **Backend**: Django 4.2 + Django REST Framework
- **Database**: PostgreSQL
- **Task Queue**: Celery + Redis
- **Authentication**: JWT + OAuth2
- **Deployment**: Docker + Gunicorn
- **Testing**: pytest

## Getting Started

### Prerequisites
- Python 3.11+
- PostgreSQL 13+
- Redis (for task queue)

### Installation
```bash
# Clone repository
git clone https://github.com/yourusername/acme-client-portal.git
cd acme-client-portal

# Create virtual environment
python -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Set up database
python manage.py migrate

# Create superuser
python manage.py createsuperuser

# Run development server
python manage.py runserver
