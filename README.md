# pickleball
Pickleball Gear Recommendation App

Project Overview

The Pickleball Gear Recommendation App is designed to help users find the best pickleball gear (paddles and shoes) tailored to their preferences and needs. This app focuses on backend functionality, using Python, to gather user input and provide personalized recommendations from a predefined dataset.

Purpose

Solve the problem of finding suitable gear for pickleball players based on their skill level, gender, and other preferences.

Keep the app simple and intuitive while allowing for future scalability.

Serve as a portfolio project with potential to grow into a real product.

Current Scope

Features:

User Input Collection:

Gather information about the user:

Gender (Male/Female).

Skill Level (Beginner, Intermediate, Advanced).

Gear Type (Paddles, Shoes).

Wide Shoes (if applicable).

Basic Recommendation Logic:

Based on the user’s input, provide gear recommendations from a dataset of paddles and shoes.

Test with an initial dataset of:

15 paddles (5 for each skill level).

30 shoes (15 men’s and 15 women’s, including wide options).

Data Storage:

Temporarily store user data in Python dictionaries.

Future Enhancements

Data Storage and Analysis:

Store user preferences to identify trends and improve recommendations.

Analyze user data for insights like popular gear or common preferences.

Web/App Integration:

Build a front-end interface to make the app user-friendly.

Integrate the backend with a front-end framework like Flask or Django.

Additional Features:

Include more gear options (e.g., bags, balls, sweatbands).

Allow users to leave reviews and ratings for gear.

Add filtering options for budget and brand preferences.

How It Works

Input Workflow:

Gender:

"Are you male or female?"

Skill Level:

"What’s your skill level? Beginner, Intermediate, or Advanced?"

Optional: Checkbox to input pickleball score for data collection.

Gear Type:

"What do you need a recommendation for? (Select all that apply: Paddles, Shoes)"

Wide Shoes (Conditional):

If "Shoes" is selected: "Do you have wide feet or need wide shoes? (Yes/No)"

Output:

Provide 5 paddle and 5 shoe recommendations that match the user’s preferences.

Technical Details

Current Tools & Technologies:

Programming Language: Python

Data Handling:

User inputs stored in Python dictionaries.

Gear data stored in Python lists or JSON for initial testing.

Logic:

Filters recommendations based on user input (gender, skill level, gear type).

Initial Dataset Structure:

Paddles:

Name

Skill Level

Paddle A

Beginner

Paddle B

Intermediate

Paddle C

Advanced

Shoes:

Name

Gender

Wide

Skill Level

Shoe X

Male

No

Beginner

Shoe Y

Female

Yes

Intermediate

Shoe Z

Male

Yes

Advanced
