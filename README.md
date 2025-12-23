# healthify
HealthiFy is an app that analyzes the nutritional content of food using AI and a comprehensive food database, providing a healthiness score and detailed breakdown of key categories. Built with React, Node.js, and Python, the app leverages APIs for data and the OpenAI API for input processing

Inspiration
My objective is to create a platform that raises awareness about food content and promotes healthier eating habits. With Healthify, my mission is to catalyze positive change by employing innovative technology to empower individuals with comprehensive information regarding their food choices. My project aligns seamlessly with critical domains such as healthcare, agriculture, safety, and education, as it equips users with the knowledge and tools to make informed nutritional decisions and prioritize their overall well-being.

What it does
Healthify empowers users to input recipes, ingredient lists, or any type of food, and employs AI and a comprehensive food database to analyze its nutritional content. The application calculates a healthiness score on a scale of 0 to 100%, where 100% signifies the healthiest option. My calculations are predicated on Nutri-Scoree, a nutritional rating system. Additionally, the app provides a detailed breakdown of the food across seven key categories: sugar, saturated fats, calories, protein, salt, fruits, and vegetables. Complementarily, the app presents a sidebar with comprehensive nutrition facts, enabling users to discern the quality of their meals with clarity and intuitiveness.

How it was built 
To commence the development process, I utilized Figma as the initial prototyping platform, ensuring that the user interface and user experience (UI/UX) were designed to be user-friendly, visually appealing, and straightforward. Subsequently, the front-end was developed using React and Vite for deployment. This combination of technologies enabled the utilization of JSX and CSS (with Bootstrap) for styling purposes. For the back-end development, Node.js and Python were employed, while OAuth2.0 was integrated to access Fatsecret’s extensive nutrition database. Furthermore, the OpenAI API was employed to process user inputs and guarantee the generation of accurate and structured outputs. This amalgamation of tools facilitated the creation of a robust platform that effectively caters to user requirements.

Challenges I ran into
* Accessing the Fatsecret API using OAuth2.0 authentication was difficult due to IP whitelisting and unclear documentation regarding end-point access.
* Designing responsive CSS to fit different screen sizes was time-consuming.
* Ensuring accurate word recognition with the OpenAI API posed challenges.
* Finding a suitable and meaningful name for the app took significant brainstorming.
* Parsing JSON responses from APIs and formatting them correctly was tricky.
* Scoping the project to balance ambition and feasibility was an ongoing challenge.

Accomplishments I'm we’re proud of
I am particularly proud of the overall design and user experience, particularly the intuitive circular meter that displays food scores. Overcoming backend challenges such as API integration and effectively utilizing AI was another significant achievement. Furthermore, I deeply appreciate the project’s impactful idea, which empowers users to make healthier food choices. Lastly, the experience enabled me to acquire new technical and project management skills within a short time frame.

What I learned
Throughout this project, I have refined my project management abilities,and acquired hands-on experience in AI development and implementation by integrating and working with the OpenAI API.
