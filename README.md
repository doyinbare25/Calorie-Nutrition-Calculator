# Calorie & Nutrition Calculator

## Project Overview

This project is a **Calorie & Nutrition Calculator** built in Python, designed to calculate and display the total calories, fats, sugars, protein, and carbohydrates for different foods based on user input.

The tool takes food items and their quantities (in grams) as input, then calculates and displays the nutritional values based on data from a nutrition dataset (`nutrition.json`). This project simulates adding this feature to a health and wellness app, helping users make more informed dietary decisions.

## Features

- Accepts user input for food items and their quantities (in grams)
- Calculates total nutritional values including:
  - Calories
  - Total Fat
  - Protein
  - Carbohydrates
  - Sugars
- Handles missing or unknown food items (with an error message)
- Built using Python and dictionary-based data structures

## Dataset

The `nutrition.json` dataset contains nutritional information for various food items. The data provided is based on **per 100 grams** for each food.

| Column        | Description                                           |
|---------------|-------------------------------------------------------|
| `food`        | The name of the food item                             |
| `calories`    | Calories per 100 grams                                |
| `total_fat`   | Total fat content (grams per 100 grams)               |
| `protein`     | Protein content (grams per 100 grams)                 |
| `carbohydrate`| Carbohydrate content (grams per 100 grams)            |
| `sugars`      | Sugars content (grams per 100 grams)                  |

Tech Stack

Python - for building the application and performing calculations
JSON - for reading and processing the nutrition data

Learning Points
Developed skills in working with Python for data-driven applications
Practiced handling dictionaries and user input
Gained experience in building practical features for health-focused applications
