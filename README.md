Pinokio Homepage Dashboards

Welcome to my collection of custom Pinokio Homepage dashboards! I’ve created these templates to enhance your Pinokio experience with visually appealing, interactive homepages. These dashboards are free for anyone to use, modify, and enjoy.

About

These dashboards are designed to replace the default Pinokio homepage with different themes. Feel free to use them as-is or tweak them to suit your style!

Quick Installation Guide


Follow these steps to install one of my dashboards into your Pinokio setup:


Choose a Dashboard: 

Browse the repository and pick the dashboard template you like (e.g., cosmic-dashboard.ejs or others provided).


Locate the Target File: In your Pinokio installation, navigate to the web/views/ folder. The file you need to replace is index.ejs.


Backup Your Existing File: Before making changes, save a copy of your current index.ejs file somewhere safe (e.g., rename it to index.ejs.bak). This ensures you can revert back if needed.

Replace the File:


Open the index.ejs file in the web/views/ folder with a text editor (e.g., VS Code, Notepad++).
Copy the entire contents of your chosen dashboard template from this repository (e.g., cosmic-dashboard.ejs).
Paste it into index.ejs, overwriting the existing content.
Save the file.

Add Background Images or GIFs (Optional):


If the dashboard uses custom background images or GIFs (like Universe-bg.jpg or a starfield GIF), place these files in the web/public/ folder of your Pinokio installation.

Update the file paths in the template’s CSS to point to your files. For example:


css
background: url("/Universe-bg.jpg") no-repeat center center fixed;


Here, /Universe-bg.jpg assumes the file is in web/public/.
Test Your Dashboard: Restart Pinokio or refresh the homepage in your browser to see your new dashboard in action!

Credits


Created by TheAwaken1 for the Pinokio community. Enjoy, and happy coding!
