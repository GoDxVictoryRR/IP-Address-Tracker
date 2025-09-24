# 🌍 IP Address Tracker

An interactive web app built with **HTML, CSS, and JavaScript** that allows users to track and locate any IP address in real time. The app fetches data such as IP address, location, timezone, and ISP, and displays the location on a map using **Leaflet.js** with **OpenStreetMap tiles**.

---

## ✨ Features

- 🔎 **Automatic IP Detection** – Detects and shows your current IP address on page load.  
- 📍 **Location Lookup** – Search any IP address and view its **location (city, country, postal code)**.  
- ⏱ **Timezone Info** – Displays the IP’s **UTC offset**.  
- 🌐 **ISP Details** – Shows the **Internet Service Provider (ISP)** for the IP.  
- 🗺 **Interactive Map** – Pinpoints the IP’s location on a map with zoom support.  
- ⚡ **Smooth User Experience** – Loading screen and error handling for invalid inputs.  

---

## 🛠️ Technologies Used

- **HTML5** – Structure of the web app  
- **CSS3** – Styling & responsive layout  
- **JavaScript (Vanilla JS)** – App logic, API handling, DOM manipulation  
- **Leaflet.js** – Map rendering and marker support  
- **OpenStreetMap API** – Map tiles  
- **IPify API** – Get user’s current IP  
- **IPAPI** – Fetch geolocation and ISP data  

---

## 🚀 Installation & Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/GoDxVictoryRR/IP-Address-Tracker.git
   ```

2. **Navigate into the project**
   ```bash
   cd IP-Address-Tracker
   ```

3. **Open in browser**
   - Simply open `index.html` in your browser.  
   - Or use a live server (e.g., VS Code extension **Live Server**).  

---

## 🌐 APIs Used

- **[IPify](https://www.ipify.org/)** → To fetch the user’s IP address  
- **[IPAPI](https://ipapi.co/)** → To fetch IP geolocation and ISP info  
- **[OpenStreetMap](https://www.openstreetmap.org/)** → Map tiles  
- **[Leaflet.js](https://leafletjs.com/)** → Display interactive map  

---

## ⚠️ Notes

- Internet connection is required for API calls and map rendering.  
- If API request limits are reached, results may not load.  
- Enter a valid IPv4/IPv6 address for correct results.  

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to fork this repo and submit a pull request.  

---

🔥 Built with ❤️ using **JavaScript + Leaflet.js + OpenStreetMap**  
