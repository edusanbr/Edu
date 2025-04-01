# Olympic Medal Prediction Model (Learning Project)
Adapted from Dataquest Tutorial for educational purposes

📌 Project Overview
This project adapts a machine learning tutorial to predict Olympic medal counts, focusing on:
- Practical implementation of regression techniques
- Handling real-world data challenges
- Developing actionable insights from model outputs

🔧 My Adaptations & Improvements

# Key modifications I implemented:
1. Enhanced visualization with Seaborn's pairplot and custom scatterplots
2. Added temporal validation (pre/post 2012 split)
3. Implemented log-transform for skewed target variable
4. Developed intuitive error analysis by medal ranges
   
📊 Key Technical Insights
-  Aspect	Finding	Practical Implication
-  Top Predictor	Historical medals (2.1× impact)	Past performance matters most
-  Model Error	MAE = 3.3 medals	Reliable for macro-estimates
-  Data Challenge	50% zeros in target variable	Required log-transform

## Technical Stack
- Python (pandas, scikit-learn)
- SHAP for interpretability
- Seaborn/Matplotlib for visualization

💡 Learning Outcomes
- Through this adaptation, I gained:
- Hands-on experience with sklearn's pipeline
- Understanding of log-transform for skewed data
- Practical knowledge of temporal validation
- Improved data storytelling skills

Note: This project was adapted from Dataquest's tutorial as part of my machine learning journey. The original code was significantly modified for enhanced analysis and visualization.
