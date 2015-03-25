Gene Network
==============

Gene Network is based on D3.js( http://d3js.org/ ) plugin, a JavaScript library for manipulating documents based on data.

# Get Started

    $ git clone https://github.com/ch-daisy/GeneNetworkGraph.git
    $ cd GeneNetworkGraph
    $ npm install
	$ npm start

Then open your browser and visit `http://localhost:3000`

# About gene-network JSON

The gene network JSON requires the data format below:

	{
		nodes:[{
		  "index": 0, 
		  "links": [
			24, 
			56, 
			140, 
			7
		  ], 
		  "score": 7, 
		  "level": 3, 
		  "title": "a1", 
		  "cover": "a1.jpg", 
		  "label": "desc", 
		  "info1":"",
		  "info2":"",
		  "id": 1768448
		}],
		links:[{
		  "source": 1, 
		  "target": 2, 
		  "weight": 0.9
		}]
	}

# Platforms and Browsers Support

* Chrome, Firefox, Internet Explorer(>=9), Safari, Opera


Only **Chrome, Firefox, IE9** are tested in this project.
