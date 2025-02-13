# BubbleWomen - A Women’s Safety Mobile Application  

## 📌 Project Description  
Women's safety remains a critical global concern, with underreporting of public harassment and violence being a persistent issue. BubbleWomen is a mobile application designed to enhance safety by providing real-time safety feedback, GPS location tracking, and an SOS alert system. The app leverages crowd-sourced safety data to create a safer community, allowing women to navigate urban areas confidently.  

### Key Features:  
- 🚨 **SOS Alerts:** Instantly notify trusted contacts and nearby users during emergencies.  
- 📍 **Location-Based Safety Ratings:** View and contribute to safety ratings of public locations.  
- 📝 **Anonymous Blogging:** Share experiences and read others’ reports to stay informed.  
- 🔐 **Secure Authentication:** User data is encrypted and protected using JWT authentication.  
- 🌍 **Community Engagement:** Encourages collective safety efforts and public awareness.  

---

## 🎯 Scope of the Project  
The BubbleWomen application aims to serve as a **technological intervention for women's safety** by addressing the following:  

1. **Breaking the Silence:**  
   - Women often avoid reporting incidents due to **social stigma and fear of retaliation**.  
   - The app provides a **safe, anonymous platform** for women to share safety concerns.  

2. **Technology as a Safety Tool:**  
   - Integrates **real-time GPS tracking**, emergency alerts, and user-generated safety data.  
   - Offers a **social media-inspired UI** to make interaction intuitive.  

3. **Widespread Accessibility:**  
   - Available on **Android and iOS**, requiring minimal technical expertise to use.  
   - Aimed at users in **urban and rural areas** where safety infrastructure is lacking.  

4. **Encouraging Community Participation:**  
   - Users can **view and rate locations** based on safety experiences.  
   - Law enforcement and researchers can analyze safety trends for better **policy-making**.  

---

## 🏗️ Description of Model Architecture  
BubbleWomen follows a **Model-View-Controller (MVC)** architecture for efficiency and scalability:  

### **1️⃣ Model (Data Layer)**
- Stores user data, locations, safety ratings, and SOS alerts.  
- Uses **MongoDB** for flexible, scalable storage.  
- Implements **JWT authentication** for user security.  

### **2️⃣ View (User Interface)**
- **React Native** frontend with TypeScript ensures a smooth, responsive UI.  
- Features a **map interface** for easy navigation and interaction.  
- Includes pages for **registration, login, blog posts, and SOS alerts**.  

### **3️⃣ Controller (Backend Logic)**
- Developed using **Spring Boot (Java 21)** for handling API requests.  
- **Notification Service:** Sends emergency alerts to nearby users.  
- **Location Controller:** Manages safety ratings and location-based reports.  

### **Technology Stack:**
- 🏗️ **Frontend:** React Native with TypeScript  
- 🖥️ **Backend:** Spring Boot with Java 21  
- 🗄️ **Database:** MongoDB (NoSQL)  
- 🔒 **Security:** JWT Authentication + Bcrypt Encryption  
- 📡 **Notifications:** Expo Notification API  
- ☁️ **Hosting:** Catalyst Cloud Computing  

---

## 👥 Target End Users  
BubbleWomen is designed for a **diverse range of users**, ensuring inclusivity and impact.  

### **1️⃣ Women & Vulnerable Individuals**  
- Primary beneficiaries who seek a **safer way to navigate public spaces**.  
- Can contribute real-time **safety feedback** and receive **community support**.  

### **2️⃣ Law Enforcement & Safety Organizations**  
- Can utilize **crowd-sourced safety data** for better **crime prevention and resource allocation**.  
- Provides **trend analysis** to enhance public security strategies.  

### **3️⃣ Community & Social Activists**  
- Citizens and volunteers can **respond to SOS alerts** and assist those in distress.  
- Helps in building a **support network for women's safety**.  

### **4️⃣ Researchers & Policymakers**  
- Can analyze app data to **understand crime trends** and propose **policy changes**.  
- Offers valuable insights into **gender-based violence patterns** in public spaces.  

---

## 📊 Results  
The BubbleWomen app has demonstrated **promising results** across different safety scenarios:  

### **1️⃣ Secure User Authentication**  
- ✅ **Encrypted Login System:** Ensures data privacy with JWT authentication.  
- 🛑 **Error Handling:** Incorrect password alerts users with a validation message.  

### **2️⃣ Location-Based Safety Ratings**  
- 📍 **Interactive Map UI:** Users can mark unsafe locations and view real-time ratings.  
- ⭐ **Average Rating Calculation:** Aggregates ratings to help users make informed decisions.  
- ⚠️ **User Prompt:** Ensures markers are accurately placed before posting reports.  

### **3️⃣ Anonymous Blogging for Incident Reporting**  
- 📝 **Users can share incidents** without revealing personal identities.  
- 🔍 **View Past Reports:** Access previous user experiences for situational awareness.  
- 🌐 **Community Feedback:** Encourages active participation and vigilance.  

### **4️⃣ Emergency SOS System**  
- 🚨 **Instant Alerts:** Notifies nearby users and trusted contacts during emergencies.  
- 📡 **Live Location Sharing:** Sends GPS data for immediate assistance.  
- 📩 **Push Notifications:** Nearby users receive alerts via Expo Notifications.  

### **5️⃣ Real-World Impact**  
- 📈 **Increased User Engagement:** Many users actively contribute safety data.  
- 🏙️ **Urban and Rural Adoption:** App usage spans across different regions.  
- 🛡️ **Safer Public Navigation:** Women report **higher confidence** when using the app.  

---

## 🚀 Future Enhancements  
BubbleWomen aims to evolve with **AI-driven safety insights and predictive alerts**, such as:  
- **🗺️ Safety Routing System:** AI-based path recommendations using safety ratings.  
- **🎙️ Voice & Chat Assistant:** AI-generated alerts when approaching unsafe areas.  
- **🛰️ Offline Functionality:** Safety updates accessible without internet connectivity.  

---

**Empowering Women Through Technology. Stay Safe, Stay Aware.** 🚀✨  
