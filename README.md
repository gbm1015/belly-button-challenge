# JavaScript Challenge - Building an Interactive Dashboard

## Background

In this assignment, we were asked to build an interactive dashboard to explore the Belly Button Biodiversity dataset at http://robdunnlab.com/projects/belly-button-biodiversity/, which catalogs the microbes that colonize human navels.

The dataset revealed that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

### Before opening the starterCode folder

1. I created a new repository in GitHub for this project called `belly-button-challenge`. 
2. Inside the new repository I cloned the new repository to my computer.
3. Inside my local Git repository, I added the files from the StarterCode folder that was within the Module 14 Challenge zip file.  The folder included the following files: index.html, sample.json (the dataset that was provided for reference; we were required to access the samples.json file locally from the website), and the static folder which included the app.js file within the js folder.
4. I copied the starter code that was provided by our class instructor, to help us get started with the assignment, to the app.js.

## Steps for Building the Interactive Dashboard

1. Used the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.
2. Created a horizontal bar chart with a dropdown menu that displayed the top 10 OTUs found in that individual.
  - Used sample_values as the values for the bar chart.
  - Used otu_ids as the labels for the bar chart.
  - Used otu_labels as the hovertext for the chart.
3. Created a bubble chart that displayed each sample.
  - Used otu_ids for the x values.
  - Used sample_values for the y values.
  - Used sample_values for the marker size.
  - Used otu_ids for the marker colors.
  - Used otu_labels for the text values.
4. Displayed the sample metadata, i.e., an individual's demographic information.
5. Displayed each key-value pair from the metadata JSON object on the page.
6. Updated all the plots when a new sample is selected.
7. Deployed the app to a free static page hosting service, GitHub Pages.  It is posted at https://gbm1015.github.io/belly-button-challenge.github.io/
8. Submitted the links to the deployment and the GitHub repository, while ensuring that the repository had regular commits and a thorough README.md file.

## References

Hulcr, J. et al. (2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/Links to an external site.
homeworkOutline14.js, javascript starter code provided by our bootcamp instructor.
https://www.w3schools.com/git/git_remote_pages.asp?remote=github, provided instructions for how to deploy an app to GitHub Pages.
