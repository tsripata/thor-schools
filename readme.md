# thor-schools

## 📚 Description
**thor-schools** is a rapid proof-of-concept (POC) project built in **one day** to enable quick, side-by-side comparison of primary schools in Thailand.  
All school information was generated through deep research assisted by OpenAI, and the entire codebase was written with the help of OpenAI’s GPT (including Codex).

This project aims to help parents quickly filter and compare schools based on distance, travel time, tuition, curriculum, and unique pros/cons — all in a clean, interactive UI.

---

## 🌐 Live Demo
The project is hosted on **GitHub Pages** and can be accessed here:  
[https://tsripata.github.io/thor-schools/](https://tsripata.github.io/thor-schools/)

---

## 🛠 Tech Stack
- **HTML, CSS, JavaScript**
- Data stored in static **JSON** format
- **Google Maps links** for location search
- Research and data curation by **OpenAI GPT**
- Coding assistance by **OpenAI Codex**

---

## 🎯 Key Features
- **Compare schools at a glance**  
  Quickly scan key information such as curriculum, tuition, and location.

- **Detailed pros & cons**  
  5+ researched pros and cons for each school, sourced from official school websites and parent reviews.

- **Travel time awareness**  
  Includes normal, peak morning (8:00), and peak afternoon (15:00) commute times for better decision-making.

- **Search & filter** *(planned)*  
  Filter schools based on commute times, distance, or tuition budget.

---

## 🧪 Process — How This POC Was Generated
1. **Define the scope**  
   Focused on **primary schools only** in Bangkok and nearby areas.

2. **Data gathering**  
   - Collected official information from school websites (tuition fees, curriculum, contact details).
   - Researched parent reviews and independent school rankings.
   - Verified commute distances and times using **Google Maps**.

3. **Data structuring**  
   - Created a structured JSON format containing:
     - Name, type, curriculum, tuition
     - Distance from home, normal and peak travel times
     - Pros & cons (5 each)
     - Logo URLs and official website links

4. **Code generation**  
   - Used OpenAI Codex to generate JavaScript for reading and rendering the JSON data.
   - Implemented Google Maps search links for each school.
   - Designed the UI for quick, side-by-side comparisons.

5. **Iteration & refinement**  
   - Added missing schools based on user feedback.
   - Expanded pros and cons with more specific and actionable details.
   - Verified logo URLs and corrected map search queries.

---

## 📌 Next Steps
- Add **interactive filters** (distance, tuition, curriculum).
- Implement **sort by travel time** or **sort by tuition**.
- Deploy to **GitHub Pages** for public access.

---

## 🙏 Credits
- **Data & Research:** OpenAI GPT, official school websites, parent review forums.
- **Code Generation:** OpenAI Codex.
- **Logos & Images:** School official websites.
