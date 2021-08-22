---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

Welcome to the course website for MUSA 550, **Geospatial Data Science in
Python**, taught at the University of Pennsylvania in fall 2020.

## Course Description

This course will provide students with the knowledge and tools to turn data into
meaningful insights, with a focus on real-world case studies in the urban
planning and public policy realm. Focusing on the latest Python software tools,
the course will outline the “pipeline” approach to data science. It will teach
students the tools to gather, visualize, and analyze datasets, providing the
skills to effectively explore large datasets and transform results into
understandable and compelling narratives. The course is organized into five main
sections:

1. **Exploratory Data Science**: Students will be introduced to the main tools
   needed to get started analyzing and visualizing data using Python.
2. **Introduction to Geospatial Data Science**: Building on the previous set of
   tools, this module will teach students how to work with geospatial datasets
   using a range of modern Python toolkits.
3. **Data Ingestion & Big Data**: Students will learn how to collect new data
   through web scraping and APIs, as well as how to work effectively with the
   large datasets often encountered in real-world applications.
4. **Geospatial Data Science in the Wild**: Armed with the necessary data
   science tools, students will be introduced to a range of advanced analytic
   and machine learning techniques using a number of innovative examples from
   modern researchers.
5. **From Exploration to Storytelling**: The final module will teach students to
   present their analysis results using web-based formats to transform their
   insights into interactive stories.

## Schedule & Course Materials

- Schedule is tentative; lectures & assignment dates are subject to change.
- Weekly course materials are stored in individual repositories on Github — available via the <img height="20" width="20" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" /> icons below.
- Lecture slides are distributed as <a href="https://jupyter.org/" target='blank_'>Jupyter notebooks</a>, which are self-contained, executable Python documents.
- Fully interactive and executable versions of the lecture slides are available via the <img src="https://mybinder.org/badge_logo.svg"> buttons. This will launch the notebooks in a _temporary_ cloud environment. Note that because the computing platform is temporary (and provided for free!), the cloud environment will be deleted and you will need to create a fresh version after an extended time of inactivity (~20 minutes or so).
- Static, non-interactive versions of the lecture slides are available via the <img height="36" width="36" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" /> buttons.

<style>
.dark-border-bottom {
   border-bottom: 3px solid #666 !important;
}
.dark-border {
   border: 3px solid #666 !important;
}
.dark-border-right {
   border-right: 3px solid #666 !important;
}
.center {
   text-align: center !important;
}
.wrapper {
   max-width: 850px !important;
}
a.disabled {
  pointer-events: none;
  cursor: default;
  opacity: 0.4
}

</style>

<div style="overflow-x:auto;">
<table class="my-table dark-border">
    <thead class="dark-border-bottom">
        <tr>
            <th class='dark-border-right'>Week</th>
            <th class='dark-border-right'>Github</th>
            <th class='dark-border-right'>Topic</th>
            <th class='dark-border-right'>Date</th>
            <th class='dark-border-right'>Interactive Slides</th>
            <th class='dark-border-right'>Static Slides</th>
            <th>Homework</th>
        </tr>
    </thead>
    <tbody>
         <!-- Week 1A -->
         <tr>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">1</td>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">
               <a href="https://github.com/MUSA-550-Fall-2020/week-1" target='blank_'>
                  <img height="24" width="24" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" />
               </a>
            </td>
            <td rowspan=2 class='dark-border-bottom dark-border-right'>Exploratory Data Science in Python</td>
            <td class='dark-border-right'>09/01 (Tu)</td>
            <td class='dark-border-right' style="min-width: 110px">    
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-1/master?filepath=lecture-1A.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-right center">
               <a href="/slides/lecture-1A.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td></td>
         </tr>
         <!-- Week 1B -->
         <tr class="dark-border-bottom">
            <td class='dark-border-right'>09/03 (Th)</td>
            <td class='dark-border-bottom dark-border-right' style="min-width: 110px">    
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-1/master?filepath=lecture-1B.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-bottom dark-border-right center">
               <a href="/slides/lecture-1B.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td class='dark-border-bottom'>
               <a href="https://github.com/MUSA-550-Fall-2020/assignment-1" target="blank_">Assign HW #1</a> (required)
            </td>
         </tr>
         <!-- Week 2A -->
         <tr>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">2</td>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">
               <a href="https://github.com/MUSA-550-Fall-2020/week-2" target='blank_'>
                  <img height="24" width="24" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" />
               </a>
            </td>
            <td rowspan=2 class='dark-border-bottom dark-border-right'>Data Visualization Fundamentals</td>
            <td class='dark-border-right'>09/08 (Tu)</td>
            <td class='dark-border-right' style="min-width: 110px">
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-2/master?filepath=lecture-2A.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-right center">
               <a href="/slides/lecture-2A.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td></td>
        </tr>
        <!-- Week 2B -->
         <tr class="dark-border-bottom">
            <td class='dark-border-right'>09/10 (Th)</td>
            <td class='dark-border-bottom dark-border-right' style="min-width: 110px">    
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-2/master?filepath=lecture-2B.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-bottom dark-border-right center">
               <a href="/slides/lecture-2B.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td class='dark-border-bottom'>
               <a href="https://github.com/MUSA-550-Fall-2020/assignment-2" target="blank_">Assign HW #2</a> (required)
            </td>
         </tr>
        <!-- Week 3A -->
        <tr>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">3</td>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">
               <a href="https://github.com/MUSA-550-Fall-2020/week-3" target='blank_'>
                  <img height="24" width="24" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" />
               </a>
            </td>
            <td rowspan=2 class='dark-border-bottom dark-border-right'>Geospatial Data Analysis and GeoPandas</td>
            <td class='dark-border-right'>09/15 (Tu)</td>
            <td class='dark-border-right' style="min-width: 110px">
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-3/master?filepath=lecture-3A.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-right center">
               <a  href="/slides/lecture-3A.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td></td>
        </tr>
        <!-- Week 3B -->
         <tr class="dark-border-bottom">
            <td class='dark-border-right'>09/17 (Th)</td>
            <td class='dark-border-bottom dark-border-right' style="min-width: 110px">    
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-3/master?filepath=lecture-3B.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-bottom dark-border-right center">
               <a  href="/slides/lecture-3B.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td></td>
         </tr>
         <!-- Week 4A -->
         <tr>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">4</td>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">
               <a href="https://github.com/MUSA-550-Fall-2020/week-4" target='blank_'>
                  <img height="24" width="24" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" />
               </a>
            </td>
            <td rowspan=2 class='dark-border-bottom dark-border-right'>More Interactive Data Viz, Working with Raster Datasets</td>
            <td class='dark-border-right'>09/22 (Tu)</td>
            <td class='dark-border-right' style="min-width: 110px">
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-4/master?filepath=lecture-4A.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-right center">
               <a href="/slides/lecture-4A.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td></td>
        </tr>
        <!-- Week 4B -->
         <tr class="dark-border-bottom">
            <td class='dark-border-right'>09/24 (Th)</td>
            <td class='dark-border-bottom dark-border-right' style="min-width: 110px">    
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-4/master?filepath=lecture-4B.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-bottom dark-border-right center">
               <a href="/slides/lecture-4B.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td class='dark-border-bottom'><a href="https://github.com/MUSA-550-Fall-2020/assignment-3" target="blank_">Assign HW #3</a> (required)</td>
         </tr>
         <!-- Week 5A -->
        <tr>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">5</td>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">
               <a href="https://github.com/MUSA-550-Fall-2020/week-5" target='blank_'>
                  <img height="24" width="24" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" />
               </a>
            </td>
            <td rowspan=2 class='dark-border-bottom dark-border-right'>Getting Data Part 1: Working with APIs</td>
            <td class='dark-border-right'>09/29 (Tu)</td>
            <td class='dark-border-right' style="min-width: 110px">
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-5/master?filepath=lecture-5A.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-right center">
               <a  href="/slides/lecture-5A.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td></td>
        </tr>
        <!-- Week 5B -->
         <tr class="dark-border-bottom">
            <td class='dark-border-right'>10/01 (Th)</td>
            <td class='dark-border-bottom dark-border-right' style="min-width: 110px">    
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-5/master?filepath=lecture-5B.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-bottom dark-border-right center">
               <a href="/slides/lecture-5B.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td class='dark-border-bottom'></td>
         </tr>
         <!-- Week 6A -->
         <tr>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">6</td>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">
               <a href="https://github.com/MUSA-550-Fall-2020/week-6" target='blank_'>
                  <img height="24" width="24" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" />
               </a>
            </td>
            <td rowspan=2 class='dark-border-bottom dark-border-right'>Getting Data Part 2: Web Scraping</td>
            <td class='dark-border-right'>10/06 (Tu)</td>
            <td class='dark-border-right' style="min-width: 110px">
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-6/master?filepath=lecture-6A.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-right center">
               <a href="/slides/lecture-6A.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td></td>
        </tr>
        <!-- Week 6B -->
         <tr class="dark-border-bottom">
            <td class='dark-border-right'>10/08 (Th)</td>
            <td class='dark-border-bottom dark-border-right' style="min-width: 110px">
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-6/master?filepath=lecture-6B.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-bottom dark-border-right center">
               <a href="/slides/lecture-6B.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td class='dark-border-bottom'><a href="https://github.com/MUSA-550-Fall-2020/assignment-4" target="blank_">Assign HW #4</a> (optional)</td>
         </tr>
         <!-- Week 7A -->
        <tr>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">7</td>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">
               <a href="https://github.com/MUSA-550-Fall-2020/week-7" target='blank_'>
                  <img height="24" width="24" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" />
               </a>
            </td>
            <td rowspan=2 class='dark-border-bottom dark-border-right'>Analyzing and Visualizing Large Datasets</td>
            <td class='dark-border-right'>10/13 (Tu)</td>
            <td class='dark-border-right' style="min-width: 110px">
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-7/master?filepath=lecture-7A.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-right center">
               <a href="/slides/lecture-7A.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td></td>
        </tr>
        <!-- Week 7B -->
         <tr class="dark-border-bottom">
            <td class='dark-border-right'>10/15 (Th)</td>
            <td class='dark-border-bottom dark-border-right' style="min-width: 110px">
            </td>
            <td class="dark-border-bottom dark-border-right center">
               <a href="/slides/lecture-7B.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td class='dark-border-bottom'></td>
         </tr>
         <!-- Week 8A -->
         <tr>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">8</td>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">
               <a  href="https://github.com/MUSA-550-Fall-2020/week-8" target='blank_'>
                  <img height="24" width="24" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" />
               </a>
            </td>
            <td rowspan=2 class='dark-border-bottom dark-border-right'>Case Study: Advanced Raster Analysis</td>
            <td class='dark-border-right'>10/20 (Tu)</td>
            <td class='dark-border-right' style="min-width: 110px">
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-8/master?filepath=lecture-8A.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-right center">
               <a  href="/slides/lecture-8A.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td></td>
        </tr>
        <!-- Week 8B -->
         <tr class="dark-border-bottom">
            <td class='dark-border-right'>10/22 (Th)</td>
            <td class='dark-border-bottom dark-border-right' style="min-width: 110px">
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-8/master?filepath=lecture-8B.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-bottom dark-border-right center">
               <a href="/slides/lecture-8B.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td class='dark-border-bottom'><a href="https://github.com/MUSA-550-Fall-2020/assignment-5" target="blank_">Assign HW #5</a> (optional)</td>
         </tr>
         <!-- Week 9A -->
        <tr>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">9</td>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">
               <a href="https://github.com/MUSA-550-Fall-2020/week-9" target='blank_'>
                  <img height="24" width="24" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" />
               </a>
            </td>
            <td rowspan=2 class='dark-border-bottom dark-border-right'>Case Study: OpenStreetMap, Urban Networks, and Interactive Web Maps	</td>
            <td class='dark-border-right'>10/27 (Tu)</td>
            <td class='dark-border-right' style="min-width: 110px">
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-9/master?filepath=lecture-9A.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-right center">
               <a href="/slides/lecture-9A.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td></td>
        </tr>
        <!-- Week 9B -->
         <tr class="dark-border-bottom">
            <td class='dark-border-right'>10/29 (Th)</td>
            <td class='dark-border-bottom dark-border-right' style="min-width: 110px">
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-9/master?filepath=lecture-9B.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-bottom dark-border-right center">
               <a href="/slides/lecture-9B.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td></td>
         </tr>
         <!-- Week 10A -->
         <tr>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">10</td>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">
               <a href="https://github.com/MUSA-550-Fall-2020/week-10" target='blank_'>
                  <img height="24" width="24" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" />
               </a>
            </td>
            <td rowspan=2 class='dark-border-bottom dark-border-right'>Case Study: Clustering Analysis in Python</td>
            <td class='dark-border-right'>11/03 (Tu)</td>
            <td class='dark-border-right' style="min-width: 110px">
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-10/master?filepath=lecture-10A.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-right center">
               <a href="/slides/lecture-10A.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td></td>
        </tr>
        <!-- Week 10B -->
         <tr class="dark-border-bottom">
            <td class='dark-border-right'>11/05 (Th)</td>
            <td class='dark-border-bottom dark-border-right' style="min-width: 110px">
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-10/master?filepath=lecture-10B.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-bottom dark-border-right center">
               <a href="/slides/lecture-10B.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td class='dark-border-bottom'><a href="https://github.com/MUSA-550-Fall-2020/assignment-6" target="blank_">Assign HW #6</a> (optional)</td>
         </tr>
         <!-- Week 11A -->
        <tr>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">11</td>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">
               <a href="https://github.com/MUSA-550-Fall-2020/week-11" target='blank_'>
                  <img height="24" width="24" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" />
               </a>
            </td>
            <td rowspan=2 class='dark-border-bottom dark-border-right'>Predictive Modeling Part 1: Home Prices in Philadelphia</td>
            <td class='dark-border-right'>11/10 (Tu)</td>
            <td class='dark-border-right' style="min-width: 110px">
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-11/master?filepath=lecture-11A.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-right center">
               <a href="/slides/lecture-11A.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td></td>
        </tr>
        <!-- Week 11B -->
         <tr class="dark-border-bottom">
            <td class='dark-border-right'>11/12 (Th)</td>
            <td class='dark-border-bottom dark-border-right' style="min-width: 110px">
               <a  href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-11/master?filepath=lecture-11B.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-bottom dark-border-right center">
               <a href="/slides/lecture-11B.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td></td>
         </tr>
         <!-- Week 12A -->
         <tr>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">12</td>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">
               <a href="https://github.com/MUSA-550-Fall-2020/week-12" target='blank_'>
                  <img height="24" width="24" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" />
               </a>
            </td>
            <td rowspan=2 class='dark-border-bottom dark-border-right'>Predictive Modeling Part 2: Space/time Rideshare Demand</td>
            <td class='dark-border-right'>11/17 (Tu)</td>
            <td class='dark-border-right' style="min-width: 110px">
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-12/master?filepath=lecture-12A.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-right center">
               <a href="/slides/lecture-12A.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td></td>
        </tr>
        <!-- Week 12B -->
         <tr class="dark-border-bottom">
            <td class='dark-border-right'>11/19 (Th)</td>
            <td class='dark-border-bottom dark-border-right' style="min-width: 110px">
               <a  href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-12/master?filepath=lecture-12B.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-bottom dark-border-right center">
               <a href="/slides/lecture-12B.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td class='dark-border-bottom'><a href="https://github.com/MUSA-550-Fall-2020/assignment-7" target="blank_">Assign HW #7</a> (required)</td>
         </tr>
         <!-- Week 13A -->
         <tr>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">13</td>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">
               <a href="https://github.com/MUSA-550-Fall-2020/week-13" target='blank_'>
                  <img height="24" width="24" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" />
               </a>
            </td>
            <td rowspan=2 class='dark-border-bottom dark-border-right'>From Notebooks to the Web: Github Pages, Web Servers, and Dash</td>
            <td class='dark-border-right'>11/24 (Tu)</td>
            <td class='dark-border-right' style="min-width: 110px">
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-13/master?filepath=lecture-13A.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-right center">
               <a href="/slides/lecture-13A.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td></td>
        </tr>
        <!-- Week 13B -->
         <tr class="dark-border-bottom">
            <td class='dark-border-right'>12/01 (Tu)</td>
            <td class='dark-border-bottom dark-border-right' style="min-width: 110px">
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-13/master?filepath=lecture-13B.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-bottom dark-border-right center">
               <a href="/slides/lecture-13B.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td class='dark-border-bottom'></td>
         </tr>
        <!-- Week 14A -->
         <tr>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">14</td>
            <td rowspan=2 class="dark-border-bottom dark-border-right center">
               <a href="https://github.com/MUSA-550-Fall-2020/week-14" target='blank_'>
                  <img height="24" width="24" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" />
               </a>
            </td>
            <td rowspan=2 class='dark-border-bottom dark-border-right'>From Notebooks to the Web: Dashboarding with Panel and the HoloViz Ecosystem</td>
            <td class='dark-border-right'>12/03 (Th)</td>
            <td class='dark-border-right' style="min-width: 110px">
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-14/master?filepath=lecture-14A.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-right center">
               <a href="/slides/lecture-14A.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td>Final project proposal due</td>
        </tr>
        <!-- Week 14B -->
         <tr class="dark-border-bottom">
            <td class='dark-border-right'>12/08 (Tu)</td>
            <td class='dark-border-bottom dark-border-right' style="min-width: 110px">
               <a href="https://mybinder.org/v2/gh/MUSA-550-Fall-2020/week-14/master?filepath=lecture-14B.ipynb" target='blank_'>
                  <img src="https://mybinder.org/badge_logo.svg">
               </a>
            </td>
            <td class="dark-border-bottom dark-border-right center">
               <a href="/slides/lecture-14B.html" target='blank_'>
                  <img height="48" width="48" src="https://upload.wikimedia.org/wikipedia/commons/3/38/Jupyter_logo.svg" />
               </a>
            </td>
            <td></td>
         </tr>
    </tbody>

</table>
</div>
