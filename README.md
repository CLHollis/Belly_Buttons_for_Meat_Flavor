# Overview

Discover & document bacteria that synthesize proteins that taste like beef. Partnered with beef company to research candidate species. Hypothesis: the ideal bacteria may be found in the bellybutton. Samples taken from the navels of many (anonymous) people. Build a dashboard that fellow research participant and fellow researchers can access, to see which bacteria species live in their navels. 

# Tools
-	VS Code, v1.63.0:  create and edit HTML and JavaScript files.
-	Chrome Web browser > Inspect & Console: view, inspect, and debug your visualizations.
-	Command-line interface to see website as it's being built, functioning:  
    - Anacond Prompt > activate my PythonData environment > path to Module folder > Run: python -m http.server > 
    - in Chrome, got to URL: localhost8000
-	Python v3.7.6
- JavaScript v1.7
- CSS Bootstrap style sheet, v4.0.0: https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css
- Plotly via CDN link, v1.58.5: https://cdn.plot.ly/plotly-latest.min.js
- D3 Library via CDN link, v5.5.0: https://cdnjs.cloudflare.com/ajax/libs/d3/5.5.0/d3.js
- GitHub: deploy your final data visualization on GitHub Pages

# Files
- Data Source [samples.json](samples.json)
- HTML file [index.html](index.html)
- JavaScript file [charts.js](static/js/charts.js)
- CSS Style file [style.css](static/css/style.css)
- Various images [Image Folder](static/images/)

# Challenge
Take the module code, where we built the webpage with the drop-down filter and dempgraphics table, and add the following:
1. Deliverable 1: Create a Horizontal Bar Chart :heavy_check_mark:
2. Deliverable 2: Create a Bubble Chart :heavy_check_mark:
3. Deliverable 3: Create a Gauge Chart :heavy_check_mark:
4. Deliverable 4: Customize the Dashboard
    - Added an image to the jumbotron. :heavy_check_mark:
    - Added colored text. :heavy_check_mark:
    - Added more information about the project as a paragraph on the page. :heavy_check_mark:
    - Added information about what each graph visualizes, either under or next to each graph. :heavy_check_mark:
    - Made the webpage mobile-responsive. :heavy_check_mark:
    - Changed the layout of the page. :heavy_check_mark:
    - Added a navigation bar that allows you to select the bar or bubble chart on the page. :heavy_check_mark:
5. Deploy your final data visualization on GitHub Pages. :heavy_check_mark:
    
    Steps:
    1) In Git Bash Run:  git add . > git commit -m "what was changed" > git commit origin main
    2) In Git Hub Repo: Settings > GitHub Pages menu drop-down:  "main branch" > Save 
    3) Refresh browser. "Your site is ready to be published {URL}" will become "Your site is published {URL}"
    4) Go to URL (in Chrome) to make sure it's working

# Results
Fully Functionsing Site: [Belly Button Biodiversity Dashboard](https://clhollis.github.io/Belly_Buttons_for_Meat_Flavor/)

1. Website starts on the first ID/person, No. 940, as ahown in this frst image.
2. Then when a different ID/person is chosen, all the charts update to that ID's results.

<image src="static/images/local_site_complete.jpg" width="700" height="860">
<image src="static/images/local_site_complete_working.jpg" width="700" height="870">








