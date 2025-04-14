# 🍽️ Personal Rule Based Food Assistant Chatbot

This project implements a simple **Prolog-based chatbot** that interacts with users about their meals, ingredients, and caloric intake. It remembers past inputs and can reason about what you can eat based on your preferences and remaining daily calories.

---

## 📜 Overview

The chatbot accepts natural language-like input sentences (in lowercase) and responds based on a knowledge base of food properties. It supports:

- Logging what you ate and when  
- Calorie calculations  
- Ingredient-based recommendations  
- Food preference tracking  
- Queries about food contents and types  
- Session-based memory with repeated answer handling

---

## 🔍 Supported Sentence Formats

| Intent                        | Example Input                                        |
|-------------------------------|-----------------------------------------------------|
| Meal Logging                  | `i ate eggs for breakfast`                          |
| Ask for Calories              | `how many calories does pasta contain`             |
| Ask Remaining Calories        | `how many calories do i have left`                 |
| Ask Food Contents             | `what does pasta contain`                          |
| Ask About Food Type in Item   | `what kind of fruit does salad contain`            |
| Ask for Description           | `what is avocado`                                  |
| Ask if Food is in Item        | `is avocado a fruit in salad`                      |
| Ask What to Eat with Filters  | `what can i have for dinner that contains tomato`  |
| Ask Permission to Eat         | `can i have pasta for lunch`                       |
| State Dislike / Allergy       | `i do not eat nuts`                                |
