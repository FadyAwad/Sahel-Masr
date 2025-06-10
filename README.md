# Sahel Masr - North Coast Egypt Chalets

A responsive web application for browsing and booking chalets in the North Coast of Egypt.

## Project Structure

```
/sahel-masr
├── css/
│   └── styles.css       # All styles for the application
├── js/
│   └── app.js           # Main application logic
├── data/
│   └── chalets.js       # Chalet data
├── img/
│   ├── Logo.png         # Site logo
│   ├── img1.jpg         # Header background
│   └── [chalet images]  # Images for each chalet
└── index.html           # Main HTML document
```

## Features

- Responsive design that works on desktop, tablet, and mobile devices
- Filter chalets by location, price, and number of bedrooms
- Detailed view of each chalet with image gallery
- Booking calendar showing availability
- WhatsApp integration for booking inquiries
- Admin panel for managing bookings (password protected)

## Usage

### For Users

1. Browse chalets on the main page
2. Use filters to narrow down results
3. Click "View Details" to see more information about a chalet
4. Check availability calendar
5. Click "Book Now on WhatsApp" to initiate a booking

### For Admins

1. Click "Toggle Admin Panel" at the bottom right
2. Enter the admin password (default: 4454)
3. Select a chalet, date range, and availability status
4. Click "Update Status" to change booking availability

## Technical Details

- Uses pure HTML, CSS, and JavaScript (no frameworks)
- Stores booking data in localStorage for persistence
- Responsive design using CSS Grid and Flexbox
- Password-protected admin functionality

## License

Made by Eng. Fady Motir 