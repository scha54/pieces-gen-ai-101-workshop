# pieces-gen-ai-101-workshop
This is the repository to store the capstone project for the Pieces Gen AI 101 Workshop

Fun Facts Generator App
Overview
The Fun Facts Generator App is a fun, interactive web application that displays random "fun facts" about the User topic. Built using HTML, CSS, and JavaScript, this app allows users to apply the concepts of prompt engineering, context setting, and handling AI limitations (hallucinations) learned in GenAI 101.

Purpose
This app was designed as a capstone project for the GenAI 101 workshop, allowing participants to:

Understand prompt engineering and context setting.
Recognize and address potential hallucinations in AI-generated content.
Practice creating and customizing a simple, shareable web application using Pieces Copilot and basic web technologies.
Key Features
Random Fun Fact Generation: Displays a random, user-defined fun fact each time you click the button.
Facts Generated using GenAI: Users can personalize the app by adding their own unique facts.
Easy Hosting on GitHub Pages: With no additional setup, users can deploy their app online to share with others.
Live Demo
You can view a sample app hosted on GitHub Pages here: https://ialimustufa.github.io/genai101-project/

Step-by-Step Project Guide
This project is designed to be completed in 15 minutes. Each step incorporates key concepts from GenAI 101.

Step 1: Define the Project Goal
Objective: Create a fun, shareable app with "fun facts" about a topic you love, generated and customized using Pieces Copilot.
GenAI Concept: Setting a clear project goal and prompt focus.
Step 2: Generate Initial Fun Facts with Pieces Copilot
Open Pieces Copilot and input a prompt like, “Generate 10 fun facts about the Planet Earth.”
Experiment with variations, adjusting the prompt to include specific details and see how different prompt styles affect the generated text.
GenAI Concept: Practice prompt engineering and adjusting context to create accurate outputs.
Step 3: Identify and Correct Hallucinations
Review the Generated Output: Check for any unrealistic or fabricated details in the fun facts.
Refine the Prompt: Modify the prompt in Pieces Copilot if you notice hallucinations, ensuring the facts are realistic and accurate.
GenAI Concept: Learn to identify hallucinations and handle inaccuracies in AI-generated content.
Step 4: Build and Customize the App
Use Pieces Copilot to generate code snippets for HTML, CSS, and JavaScript to create a simple single-page app.
index.html: Provides the basic HTML structure.
style.css: Adds styling for a personalized look and feel.
script.js: Contains JavaScript to handle random fact generation and user interactions.
Customize the fun facts by modifying the facts array in script.js.
Example:

const facts = [
            "Cats are crepuscular, which means they are most active during dawn and dusk.",
            "A cat's nose print is unique, just like a human fingerprint.",
            "Cats can jump up to six times their height.",
            "The average cat sleeps for about 12-16 hours a day.",
            "Cats have a third eyelid, called a nictitating membrane, that helps protect their eyes.",
            "A group of cats is called a clowder.",
            "Cats can make over 100 different vocalizations, while dogs can only make about 10.",
            "The oldest known cat lived to be 38 years old.",
            "Cats use their whiskers to help them navigate and sense their environment.",
            "Cats have a specialized 'purr box' in their throat that can vibrate at a variety of frequencies, and its believed this can promote healing."
        ];
Combine all these 3 code files into the index.html file by giving another prompt.
GenAI Concept: Document prompt adjustments and observe how context changes impact code accuracy.
Step 5: Host on GitHub Pages and Share
Go to your GitHub repository and navigate to Settings > Pages.

Under Source, select the main branch and set the folder to /root and click Save.

Click Save. Your app will be live at a link like https://yourusername.github.io/genai101/.

Share the link to let others explore and enjoy your fun facts generator app.

GenAI Concept: Share a practical AI-powered creation, reinforcing the importance of presentation and sharing.
How to Use the App
Open the app in a browser using your GitHub Pages link.
Click the Generate Another Fun Fact button.
A new random fun fact will appear each time you click the button.
Share the link with friends or on social media to let others enjoy the small project you build with GenAI and Pieces!
Troubleshooting Tips
Fun facts not displaying?
Check that script is correct in index.html.
Ensure each fun fact in the facts array is enclosed in quotes and separated by commas.
Site not loading on GitHub Pages?
Confirm you’ve set the source to the main branch in GitHub Pages settings.
Make sure your GitHub Pages URL is correctly formatted as https://yourusername.github.io/genai101/.
License
This project is open-source and available under the MIT License. Feel free to use, modify, and distribute it as you like.
