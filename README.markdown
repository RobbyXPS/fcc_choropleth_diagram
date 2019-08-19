# Data Visualization Projects - Choropleth Map

### _User stories_

1. My choropleth should have a title with a corresponding id="title".
2. My choropleth should have a description element with a corresponding id="description".
3. My choropleth should have counties with a corresponding class="county" that represent the data.
4. There should be at least 4 different fill colors used for the counties.
5. My counties should each have data-fips and data-education properties containing their corresponding fips and education values.
6. My choropleth should have a county for each provided data point.
7. The counties should have data-fips and data-education values that match the sample data.
8. My choropleth should have a legend with a corresponding id="legend".
9. There should be at least 4 different fill colors used for the legend.
10. I can mouse over an area and see a tooltip with a corresponding id="tooltip" which displays more information about the area.
11. My tooltip should have a data-education property that corresponds to the data-education of the active area.

  <br>
  <br>
  <br>
  <br>

### _Technology and how it was used_

#### Front-End features (HTML + CSS + D3.js)
    - Draw graph on svg html element leveraging D3.js data visualization library.
    - Import fonts from CDN.
    - Fetch JSON data from multiple sources and leverage await before rendering.
     - US Education Data: https://raw.githubusercontent.com/no-stack-dub-sack/testable-projects-fcc/master/src/data/choropleth_map/for_user_education.json
     - US County Data: https://raw.githubusercontent.com/no-stack-dub-sack/testable-projects-fcc/master/src/data/choropleth_map/counties.json
    - Use topojson library to project location data onto a visual map
    - Create monocromatic color scale via D3 Quantile scale.
    - Simple legend UI.
    - Mouseover/Mouseout interactive functionality to display overlay with more info.
    
  <br>
  <br>
  <br>
  <br>

#### The following links were used as help/inspiration for this project:
    - https://codepen.io/j-todd/pen/dQMwQa
    - https://codepen.io/freeCodeCamp/pen/EZKqza?editors=1010
