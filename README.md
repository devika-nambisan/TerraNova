# 🌎 TerraNova — Scan. Sort. Save Earth! 🌟

TerraNova is a fun hackathon project built at **HackTx** to make responsible waste disposal **easy, rewarding, and even a little magical**.
It uses **in-browser Machine Learning** to identify an item and instantly tell you how to dispose of it the right way.️

## 🌟 Core Features
- **ML Classification:** Uses MobileNet (TensorFlow.js) to identify items as Plastic, Glass, Paper, Metal, Compostable, or E-Waste.  
- **Localized Guidance:** Shows exactly how to dispose of your items and helps you find nearby recycling or hazardous drop-off centers on a cute, interactive **Leaflet.js map**.  
- **Gamified Habit:** Earn stars 🌟 for correct disposal and watch your **Galaxy grow**, making recycling fun and motivating!  
- **100% Frontend:** Built with HTML, CSS, and Vanilla JavaScript — runs fast in any browser, no downloads needed.

## 🚀 Installation & Usage
1. Clone the repository:  
git clone https://github.com/devika-nambisan/TerraNova.git
2. Open the file `terranova-app-final3.html` in your browser and start saving the planet! 🌍  

## 💡 Inspiration
Every day, millions of people want to do the right thing for the planet — to recycle, compost, or properly dispose of waste — but it’s not always obvious where things go.
**TerraNova** was born to fix that!  
_"TerraNova"_ means **“New Earth,”** and our mission is to make eco-friendly choices **as simple as snapping a photo**, helping everyone take small actions that add up to big environmental wins. 

## 🧩 How It Works
1. Snap a photo of an item with your device camera  
2. MobileNet (TensorFlow.js) analyzes it right in your browser  
3. The item gets sorted into one of six categories 
4. Instructions pop up instantly
5. Check nearby recycling/hazardous sites on the interactive map
6. Dispose correctly and **earn stars for your Galaxy**! 

## ⚙️ Tech & Implementation
- **Frontend:** HTML, CSS, Vanilla JavaScript  
- **Machine Learning:** MobileNet via TensorFlow.js  
- **Camera Access:** `navigator.mediaDevices.getUserMedia()`  
- **Map:** Leaflet.js + OpenStreetMap tiles  
- **Gamification:** Star counter & particle animations saved in `localStorage`  
- **Privacy:** 100% client-side, no data sent anywhere 👀  

## 🛠 Challenges
- Making sure the ML model accurately recognizes different items 
- Getting the star animation to scale nicely 
- Handling camera permissions across all browsers 

## 🏆 Accomplishments
- Built a **working prototype in under 24 hours** 
- Designed a **clean, intuitive interface** for instant recycling guidance 
- Created a **fun, gamified experience** that motivates daily eco-friendly habits 

## 🌈 Future Plans
- Expand the **AI recognition database** for more items
- Add **streaks, badges, and leaderboards** for extra motivation
- Social features to **share eco-achievements** with friends
- Partner with schools, cities, and recycling programs
- Track and visualize **cumulative environmental impact** over time

## 👩‍💻 Team
- Abhinaya Guduru  
- Devika Nambisan  
- Sanjita Kelkar  
- Tejaswini Kalikiri  

Let's make the world a little greener, one scan at a time! 🌍✨
