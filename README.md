# AuctionHub - Online Auction Website

A responsive Django-based online auction platform with a modern UI.

## Features

- Responsive landing page with animations and modern UI
- Image slider for featured auctions
- Testimonials section
- Mobile-friendly design

## Technologies Used

- **Backend**: Django 5.2
- **Frontend**: 
  - HTML5, CSS3, JavaScript
  - Bootstrap 5
  - Font Awesome
  - AOS Animation Library
  - Swiper JS

## Setup Instructions

1. Clone the repository:
   ```
   git clone <repository-url>
   cd Auc-1
   ```

2. Create a virtual environment and activate it:
   ```
   python -m venv env
   .\env\Scripts\activate  # Windows
   source env/bin/activate  # Unix/MacOS
   ```

3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Run migrations:
   ```
   python manage.py migrate
   ```

5. Generate placeholder images (optional):
   ```
   python scripts/generate_placeholders.py
   ```

6. Run the development server:
   ```
   python manage.py runserver
   ```

7. Open your browser and navigate to: `http://127.0.0.1:8000/`

## Project Structure

- `auction_site/` - Django project settings and configuration
- `home/` - App for the landing page
- `static/` - Static assets (CSS, JS, images)
- `templates/` - HTML templates
- `scripts/` - Utility scripts

## Future Enhancements

- User authentication and profiles
- Auction listing and bidding functionality
- Real-time bid updates
- Payment integration
- Admin dashboard

## License

This project is licensed under the MIT License - see the LICENSE file for details. 