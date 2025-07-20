# ALX Travel App

A Django-based backend system for listing travel accommodations, managing bookings, and collecting reviews.

## 📌 Project Structure

```bash
alx_travel_app/
├── alx_travel_app/          # Project settings directory
│   ├── settings.py
│   ├── urls.py
│   └── ...
├── listings/                # Main app for listings, bookings, and reviews
│   ├── models.py
│   ├── views.py
│   ├── serializers.py
│   ├── urls.py
│   ├── management/
│   │   └── commands/
│   │       └── seed.py
│   └── ...
├── manage.py
├── requirements.txt
└── README.md
