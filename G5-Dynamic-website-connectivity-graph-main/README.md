<h1>Dynamic Website Connectivity Graph</h1>
A graph made in python to show connections between sites based on preloaded data

## Table of Contents
- [Table of Contents](#table-of-contents)
- [Objectives](#objectives)
- [Objectives completed](#objectives-completed)
- [Usage](#usage)
  - [Installation](#installation)
  - [Navigation](#navigation)
- [Team](#team)
  - [Mentors:](#mentors)
  - [Members:](#members)

## Objectives
* Crawler was used to collect ~ 1.16L entries from various sites, organized into excel sheets with various
attributes and was further sorted using pandas in python. An interactive web page containing a zoomable
network map connecting all the nodes was made, and time constraints were kept in mind. The graph was
then further furbished using BOKEH for an appealing and aesthetic visualization making it easier to be
analyzed.

## Objectives completed 
 Firstly, a webpage is displayed offering the general information about the graph and contains a button.
Upon clicking the button, the webpage proceeds to the graph along with its title.
 The data for the graph rendered by using the ids and the origin ids by importing them directly from
the csv using pandas module.
 The graph can be zoomed in and zoomed out using the scroll of the mouse as well as the box tool
wherein a particular region of the graph can be zoomed into.
 The graph can also be panned via the panning tool.
 Upon hovering on any of the nodes of the graph, its index position in the dataset is seen and that
node along with the other nodes connected to it are highlighted.
 The graph can even be saved as a png at a particular position.
 There is also a reset option that has been provided to go back to the stage where the graph was
originally rendered.


## Usage

Web Page:
We have made 2 html pages namely for the front introductory page called index.html and the innerpage
where graph is seen. The previously rendered NetworkX has been instilled as an iframe in the innerpage.
The styling for the webpage has been done in the css file.

### Installation 

Install Bokeh and the NetworkX module along with other modules to be used as shown in the source code.

Next, import pandas module and access the column data using it.

Then the network graph is rendered by correlating the id to the origin id.

A title is given to the graph and the hover tooltips are also added. The theme has been set to a dark background.

Different functionalities are added to the graph like pan, wheel_zoom, box_zoom, save and reset have been added to the previously formed network graph.

Add attributes like scale thickness of edge lines size and color of nodes to the graph. 

We have also used the network’s graphs selection and inspection policy to highlight 
the nodes which are connected to a particular node when hovered on it and also display its index.

<details>
    <summary><b>Windows</b></summary>

   1. Clone the repository
   2. Continue steps
</details>

<details>
    <summary><b>Ubuntu</b></summary>

   1. Clone the repository
   2. Continue steps
</details>

### Navigation

Various components that exist in the navigation

<details>
    <summary><b>Show instructions</b></summary>

   1. Make Admin account
   2. Login?
</details>


## Team

Chintan Shukla

Alekhya Gorugantu

Niyati Mehta

Paarth Kapur

Vaishnavi Vergulekar

Himanshu Nimonkar


### Mentors:
Irfan Siddavatam ( irfansiddavatam@somaiya.edu )<br>
Ashwini Dalvi ( ashwinidalvi@somaiya.edu )

### Members:
| Sr No. | Name     | e-mail                   | git-profile |
| ------ | -------- | ------------------------ | ----------- |
| 1.     | Chintan Shukla | c.shukla@somaiya.edu | https://github.com/Chintan2209    |
| 2.     | Alekhya Gorugantu | alekhya.g@somaiya.edu | https://github.com/AlekhyaG-02    |
| 3.     | Niyati Mehta | mehta.nb@somaiya.edu |    |
| 4.     | Paarth Kapur | paarth.kapur@somaiya.edu | https://github.com/PaarthKapur    |
| 5.     | Vaishnavi Vergulekar | vaishnavi.vv@somaiya.edu | https://github.com/Vaishnavi-2207 |
| 6.     | Himanshu Nimonkar | h.nimonkar@somaiya.edu | https://github.com/BoomHimanshu   |
