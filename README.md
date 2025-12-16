
# Vehicle Pickup Calculator

A web-based travel cost calculator for vehicle pickups, designed to quickly estimate travel expenses based on distance and mileage rate.

## 🚗 Features

- **Real-time Autocomplete**: Fast address suggestions powered by LocationIQ API
- **Accurate Distance Calculation**: Uses OSRM (Open Source Routing Machine) for precise driving distances
- **Simple Cost Estimation**: Calculates total travel cost at $2.00 per mile
- **Mobile Friendly**: Responsive design works on all devices
- **Clean Interface**: Modern, intuitive UI with gradient styling

## 🌐 Live Demo

Visit the live calculator: [https://cameronoberlies.github.io/vehicle-pickup-calculator/](https://cameronoberlies.github.io/vehicle-pickup-calculator/)

## 📋 How It Works

1. Enter a vehicle location (city, state, or full address)
2. Select from the autocomplete suggestions or press Enter
3. View calculated travel cost and distance to Shelby, NC

**Default Settings:**
- Destination: Shelby, NC
- Rate: $2.00 per mile

## 🛠️ Technologies Used

- **HTML/CSS/JavaScript**: Pure vanilla JS, no frameworks
- **LocationIQ API**: Geocoding and autocomplete services
- **OSRM API**: Driving distance calculations
- **GitHub Pages**: Free hosting

## 🔧 Customization

To customize for your own use:

1. **Change Destination**: Update `DEST_LAT`, `DEST_LON`, and `DESTINATION` variables in the JavaScript
2. **Change Rate**: Modify `RATE_PER_MILE` constant
3. **API Key**: Replace the LocationIQ API key with your own (free tier: 5,000 requests/day)

## 📝 License

Free to use and modify for personal or commercial purposes.

## 🙏 Acknowledgments

- LocationIQ for geocoding services
- OSRM for routing calculations
- OpenStreetMap contributors for map data
