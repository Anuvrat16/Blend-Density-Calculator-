Density Blend Master 🧪
Precision Formulation Density Calculator for Professionals

Density Blend Master is a lightweight, mobile-responsive web application designed for pharmaceutical scientists, chemists, and culinary professionals. It calculates the final bulk density of a mixture containing up to 25 different ingredients with varying densities.

🚀 Live Demo
[anuvrat03.github.io]

📋 Features
* Dynamic Ingredient Management:Add up to 25 ingredients per formulation.
* Dual-Unit Input:Seamlessly toggle between grams (mass) and pmL (volume).
* Smart Back-Calculation: Automatically calculates missing mass/volume values based on the specific gravity (density) of each ingredient.
* Real-Time Dashboard:A sticky header provides instant updates on:
  * Total Batch Mass (g)
  * Total Batch Volume (mL)
  * *Final Blend Density (g/mL or cc)
* Mobile-First Design:Optimized for use in labs, cleanrooms, and kitchens using TrebEdit or mobile browsers.

 🧮 How it Works
The app uses the fundamental density sum logic to ensure accuracy:

$$\rho_{blend} = \frac{\sum \text{Mass}_{i}}{\sum \text{Volume}_{i}}$$

Where:
- If input is in grams: $Volume = \text{Mass} / \text{Density}$
- If input is in mL: $\text{Mass} = \text{Volume} \times \text{Density}$

 🛠️ Technology Stack
* HTML5/CSS3:Custom card-based UI with floating labels.
* JavaScript (Vanilla):Real-time calculation engine (no external libraries required).

📖 How to Use
1. Add Ingredient:Click the "+ Add Ingredient" button.
2. Enter Details:Input the ingredient name (optional) and quantity.
3. Set Density:Enter the known density of that specific ingredient (e.g., Glycerin = 1.26).
4. View Results:The blue dashboard at the top will update your final blend density immediately.

 📄 License
This project is open-source and free to use for professional and educational purposes.
