Western Study Finder is a web application designed to help students at Western University find open classrooms and quiet spaces for studying. Whether libraries are full or you just need a change of scenery, this tool makes it easy to locate available study spots in real-time, so you can focus on your work.

---

## 🌟 **Features**
- **Real-Time Availability**: Check which classrooms are open for studying across campus.
- **Interactive Map**: Visualize classroom locations and availability on a detailed map.
- **Proximity Sorting**: Sort classrooms based on their distance from your current location.
- **Google Maps Integration**: Click on a classroom to get a route to it via Google Maps.
- **Predictive Recommendations**: Plan your study sessions by viewing spots likely to be less busy during specific times.

---

## 🛠️ **Tech Stack**
### **Frontend**
- **[Next.js](https://nextjs.org/)**: Robust React-based framework for building the user interface.
- **[Mapbox GL](https://docs.mapbox.com/mapbox-gl-js/)**: Interactive maps for visualizing classroom locations.
- **[Tailwind CSS](https://tailwindcss.com/)**: Utility-first CSS framework for consistent and responsive design.

### **Backend**
- **[Flask](https://flask.palletsprojects.com/)**: Lightweight Python web framework to handle APIs and logic.
- **Haversine Formula**: Calculate distances between user and classrooms.
- **Database**: PostgreSQL/MongoDB (used for storing classroom availability and usage data).

### **APIs**
- **Google Maps API**: For generating walking routes to study spots.
- **Geolocation API**: To fetch user location for proximity-based sorting.

---
