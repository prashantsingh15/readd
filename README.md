# Internsync
Internsync is a role-based internship management platform built with Django, Tailwind CSS. It streamlines the internship process for students, TPOs ,companies, and admins through clean dashboards and an efficient workflow. A key feature includes allowing students to submit internship deferment requests directly to companies.

Features:-
Students: Browse internships, apply, track status, upload documents.
TPOs: Approve/defer applications, manage students, coordinate with companies.
Companies: Post internships, review applications, shortlist candidates.
Admin: Manage users, oversee platform activity, maintain records.

Tech Stack:-
Frontend: HTML, CSS, Tailwind CSS
Backend: Django, Django REST Framework
Database: SQLite (default), PostgreSQL/MySQL (optional)

Setup:-
1. Clone: git clone https://github.com/yourusername/internsync.git && cd internsync
2. Create venv: python -m venv venv && source venv/bin/activate (Windows: venv\Scripts\activate)
3. Install: pip install -r requirements.txt
4. Migrate: python manage.py migrate
5. Run: python manage.py runserver














# SCREENSHOTS SECTION





# DEC 1
![WhatsApp Image 2025-05-01 at 15 44 00_a592f2a1](https://github.com/user-attachments/assets/73866283-bd22-4a64-804a-95c6ccf43f40)

# DEC 2
![WhatsApp Image 2025-05-01 at 15 44 42_343e7d0f](https://github.com/user-attachments/assets/98100dc4-da68-40c0-90d3-ed3192c9289c)

# DEC 3
![WhatsApp Image 2025-05-01 at 15 45 24_7dc94bb5](https://github.com/user-attachments/assets/8b65065f-c18c-403b-90b3-1a5837de1de9)

# DEC 4
![WhatsApp Image 2025-05-01 at 15 46 19_2862a0e0](https://github.com/user-attachments/assets/77fa827c-a84a-4e37-810e-f78c26e021d0)

# DEC 5
![WhatsApp Image 2025-05-01 at 15 47 02_0c54cebf](https://github.com/user-attachments/assets/cc115624-11bd-49d6-b592-b1faa9988aaa)

# DEC 6
![WhatsApp Image 2025-05-01 at 15 49 44_02a21592](https://github.com/user-attachments/assets/b2cbd822-ea03-430f-9ea3-59c66292913c)

# DEC 7
![WhatsApp Image 2025-05-01 at 15 51 25_e3f00c12](https://github.com/user-attachments/assets/6c0ee509-5dac-4e3d-897e-fe45e314b357)

# DEC 8
![WhatsApp Image 2025-05-01 at 15 53 33_f4370d7b](https://github.com/user-attachments/assets/849cd1c5-cea8-41d4-ae2c-1d4493f756a8)

# DEC 9
![WhatsApp Image 2025-05-01 at 15 54 36_f293a70c](https://github.com/user-attachments/assets/3bf8fe0e-3d29-485d-9088-8e136a1e104e)

# DEC 10
![WhatsApp Image 2025-05-01 at 15 55 22_f39754a1](https://github.com/user-attachments/assets/8982f708-3142-4dd4-8d44-437146393c02)

# DEC 11
![WhatsApp Image 2025-05-01 at 15 56 43_a813a0fb](https://github.com/user-attachments/assets/e84bab0f-9f7a-4e60-bd47-3401c3627518)

# DEC 12
![WhatsApp Image 2025-05-01 at 15 57 29_078a71ec](https://github.com/user-attachments/assets/e29aa071-f354-4625-9822-ea3bb04c8db8)

# DEC 13
![WhatsApp Image 2025-05-01 at 15 57 29_536d7ebf](https://github.com/user-attachments/assets/62de5f6f-d5ad-490b-84d7-6efa791ae098)

# DEC 14
![WhatsApp Image 2025-05-01 at 15 59 23_346b4fad](https://github.com/user-attachments/assets/da71182d-8979-49df-8fd8-a7255e22ffba)

# DEC 15
![WhatsApp Image 2025-05-01 at 15 58 13_7b702ba8](https://github.com/user-attachments/assets/0afa4a8a-d1af-48dd-bf52-94ebb2f61e95)

# DEC 16
![WhatsApp Image 2025-05-01 at 15 58 41_dabcf9d3](https://github.com/user-attachments/assets/96e259b4-f707-47ec-bdec-071e3432e3f1)

# DEC 17
![WhatsApp Image 2025-05-01 at 15 58 59_5446c67b](https://github.com/user-attachments/assets/75e19e14-0a1d-4d5a-b183-f02d65f4cbd1)

# DEC 18
![WhatsApp Image 2025-05-01 at 15 59 42_89157532](https://github.com/user-attachments/assets/7f730bb1-9a41-4226-88fc-41605bc6e98a)







# ** Directory :-
core/
│
├── core/
│   ├── _pycache_/
│   ├── templates/
│   │   └── registration/
│   │        └── login.html  # Django default auth login template
│   ├── _init_.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py   # Project-level URLs
│   └── wsgi.py
│
├── dashboard/
│   ├── migrations/
│   ├── templates/
│   │   └── dashboard/
│   │         ├── dashboard_home.html
│   │         ├── post_internship.html
│   │         ├── manage_internships.html
│   │         ├── applications_received.html
│   │         ├── documents.html
│   │         └── profile_settings.html
│   ├── _init_.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py  # App-level URLs
│   └── views.py
│
├── users/
│   ├── migrations/
│   ├── templates/
│   │   └── users/
│   │         ├── users_home.html
│   │         └── profile_settings.html
│   ├── _init_.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
│
├── media/
├── db.sqlite3
├── manage.py
└── env/

