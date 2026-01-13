# Lib4RI RDM Services Sunburst Visualization

This is an interactive D3.js sunburst diagram showcasing the Research Data Management (RDM) services offered by Lib4RI and the four research institutes within the ETH Domain: Eawag, Empa, PSI, and WSL.

This radial space-filling visualization was originally created by [John Stasko](https://sites.cc.gatech.edu/gvu/ii/sunburst/) and traditionally shows the [cumulative values of subtrees](https://eurostat.github.io/d3.sunburst/). It is commonly used to visualize nested objects, in large part becuase it shows the mass of hidden things in each subsection.

## Overview
This visualization provides a hierarchical view of the RDM services and tools available across the institutes, aligned with the research data lifecycle phases:

* **Plan**: Data Management Plans (DMPs), FAIR principles
* **Collect**: Data acquisition, formats, and metadata
* **Process & Analyze**: Data processing, analysis tools
* **Preserve & Share**: Data storage, repositories, publication
* **Find & Reuse**: Data discovery, reuse, and citation.

Each segment of the sunburst represents a specific service or tool, allowing users to explore the interconnectedness and offerings within each phase.
There is quite a bit of overlap with the website erit large, so some trimming is clearly going to be necessary. 

## Getting Started

1. hosted version can be found here: 

https://pages.gitlab.eawag.ch/rdm-nav-b7b63b/


2. code was developed here: 

https://gitlab.eawag.ch/chase.nunez/rdm_sunburst

3. D3.js inspiration can be found here:
https://observablehq.com/@d3
https://observablehq.com/@d3/zoomable-sunburst


## For testing before deployment
## in terminal window:
python3 -m http.server 8000

## in browser window
http://localhost:8000/index.html

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.