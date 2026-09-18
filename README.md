# PackMe 🧳

Mobile-first progressive web app for intelligent travel packing lists.

## Features
- Create trips with destination, date, duration, trip type and travelers.
- Automatic geocoding and weather forecast via Open-Meteo when online.
- Adaptive visual theme for day trips, city, beach, mountains and camping.
- Quantity-aware packing rules for adults and children (e.g. diapers, shirts, underwear).
- Weather/activity-aware additions.
- Swipe right to pack; swipe left to return an item.
- Add or delete custom items.
- Reusable person profiles and trip duplication.
- Local browser storage and PWA support.

## GitHub Pages
Upload the contents of `packme/` to a repository and enable GitHub Pages from the repository's Actions/Pages settings. The app uses only static HTML/CSS/JS.

## Weather
PackMe uses Open-Meteo's public geocoding and forecast endpoints. Internet access is needed for fresh weather data; the basic checklist still works if the weather request fails.
