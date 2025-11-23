Fast Food Nutrition Dashboard

Project Overview
This project analyzes nutrition data from major fast food chains using Tableau visualizations. It explores calorie content, macronutrient balance, and sodium levels across hundreds of menu items. The goal is to uncover patterns in nutrient density and help consumers identify healthier alternatives.

Dataset
- File: `fastfood_cleaned.csv`
- Contains 300+ food items from McDonald’s, Chick-fil-A, Sonic, Burger King, Dairy Queen, Subway, and Arby’s
- Nutrients tracked: Calories, Total Fat, Saturated Fat, Trans Fat, Protein, Sodium, Carbs, Sugar, Fiber, Cholesterol, Vitamins, Calcium

 Visualizations
1. Macronutrient Breakdown (Stacked Bar Chart)
- **X-axis:** Food Item  
- **Y-axis:** Stacked bars of Total Fat, Protein, and Carbs  
- **Filter:** Restaurant  
- Helps compare nutrient composition across items and chains

2. Restaurant-Level Nutrient Comparison
- One stacked bar per restaurant showing average nutrient values  
- Simplifies comparison across chains

3. Top 10 High-Calorie Items
- Bar chart showing top 10 items by Calories  
- Colored by restaurant for context

 4. Scatter Plot: Fat vs Protein
![Fat vs Protein Scatter Plot](dashboard_screenshot.png)

This scatter plot visualizes the relationship between **Total Fat** and **Protein** across fast food items:
- **X-axis:** Total Fat (g)  
- **Y-axis:** Protein (g)  
- **Each dot:** One food item  
- Reveals clusters of burgers, sandwiches, and salads based on nutrient density

 Key Insights from Scatter Plot
- Items with **high fat and low protein** may be less nutritionally balanced  
- **Grilled chicken and wraps** tend to offer **higher protein per gram of fat**  
- **Burgers and fried items** cluster in the **high-fat, moderate-protein zone**  
- Outliers with **extremely high protein** (e.g., double meat sandwiches) are visible in the top-right quadrant

Tools Used
- **Tableau:** Data visualization  
- **Excel:** Data cleaning and preprocessing  
- **GitHub:** Project hosting and documentation  




