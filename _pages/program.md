---
layout: default
title: Program
---

# Program

**Monday, October 25, 2021**
(US Central Time)

<table class="program">
  <tr>
    <td>8:00am &ndash; 8:10am</td>
    <td>
      Opening Remarks (Julien Tierny)<br/>
      <!--       (<a href="https://youtu.be/egXjNGyYHlQ" target="new">Youtube live stream</a>) -->
    </td>
  </tr>
  <tr>
    <td>8:10am &ndash; 9:00am</td>
    <td>
      <h4>Keynote Presentation
      <!--       (<a href="https://youtu.be/egXjNGyYHlQ" target="new">Youtube live stream</a>) -->
      </h4>
      <i>Professor Alex Telea, Utrecht University</i><br>
      <b>Image-Based Graph Drawing:<br> From a Million Nodes and Edges to a Million Pixels and Back</b><br/>
      <a style="font-size: smaller; display: block; margin-top: .5em;" href="#keynote">Details</a>
    </td>
  </tr>
  <tr>
    <td>9:00am &ndash; 9:30am</td>
    <td>
      <h4>Best Paper
<!--       (<a href="https://youtu.be/egXjNGyYHlQ" target="new">Youtube live stream</a>) -->
      </h4>
      (Session Chair: Julien Tierny)
      <ul>
        <li>
           Data-Aware Predictive Scheduling for Distributed-Memory Ray Tracing
           <br><i>Hyungman Park, Donald Fussell, Paul Navratil</i>
           <br/>
<!--           <i>Florian Frieß, Matthias Braun, Valentin Bruder, Steffen Frey, Guido Reina,Thomas Ertl</i> -->
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>9:30am &ndash; 10:00am</td>
    <td>Break</td>
  </tr>
  <tr>
    <td>10:00am &ndash; 11:30am</td>
    <td>
      <h4>Session: Algorithms
<!--       (<a href="https://youtu.be/skM-gluIXzU" target="new">Youtube live stream</a>) -->
      </h4>
      (Session Chair: Filip Sadlo)
      <ul>
        <li>
          Fast Approximation of Persistence Diagrams with Guarantees
          <br><i>Jules Vidal, Julien Tierny</i>
        </li>
        <li>
          IExchange: Asynchronous Communication and Termination Detection for Iterative Algorithms
          <br><i>Dmitriy Morozov, Tom Peterka,
          Hanqi Guo,
          Mukund Raj,
          Jiayi Xu,
          Han-Wei Shen
          </i>
        </li>
        <li>
          Trigger Happy: Assessing the Viability of Trigger-Based In Situ Analysis
          <br><i>
          Matthew Larsen,
          Cyrus		Harrison,
          Terece	Turton,
          Sudhanshu		Sane,
          Stephanie		Brink,
          Hank		Childs
          </i>
        </li>
        <li>
          High-quality and Low-memory-footprint Progressive Decoding of Large-scale Particle Data <i>(Best Paper Honorable Mention)</i>
          <br><i>
          Duong		Hoang,
          Harsh		Bhatia,
          Peter		Lindstrom,
          Valerio		Pascucci
          </i>
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>11:30am &ndash; 12:00 pm</td>
    <td>Break</td>
  </tr>
  <tr>
    <td>12:00pm &ndash; 1:30pm</td>
    <td>
      <h4>Session: Render/Display
<!--       (<a href="https://youtu.be/skM-gluIXzU" target="new">Youtube live stream</a>) -->
      </h4>
      (Session Chair: Kelly Gaither)
      <ul>
        <li>
          GPU-based Image Compression for Efficient Compositing in Distributed Rendering Applications
          <br><i>Riley Lipinski, Kenneth Moreland, Michael Papka, Thomas Marrinan
</i>
        </li>
        <li>
          Amortised Encoding for Large High-Resolution Displays
          <br>
          <i>
          Florian		Friess,
          Michael		Becher,
          Guido		Reina,
          Thomas		Ertl
          </i>
        </li>
        <li>
          Portable and Composable Flow Graphs for In Situ Analytics
          <br><i>
          Sergei		Shudler,
          Steve		Petruzza,
          Valerio		Pascucci,
          Peer-Timo		Bremer
          </i>
        </li>
        <li>
          An Entropy-Based Approach for Identifying User-Preferred  Camera Positions
          <br><i>
          Nicole	J	Marsaglia,
          Yuya		Kawakami,
          Samuel	David	Schwartz,
          Stefan		Fields,
          Hank		Childs
          </i>
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>1:30pm &ndash; 2:00pm</td>
    <td>Break</td>
  </tr>
  <tr>
    <td>2:00pm &ndash; 3:20pm</td>
    <td>
      <h4>Early Career Researcher Lightning Talks</h4>
      (Session Chair: Chaoli Wang)
      <ul>
        <li>James Kress: <i>In-Line vs. In-Transit In Situ: Which Technique to Use at Scale?</i>
        </li>
        <li> Jun Han: <i>Deep Learning for Scientific Data Representation and Generation</i><br></li>
        <li> Sam Molnar: <i>Metropolitan-Scale Power Grid Analysis: Geospatial Networked Time Series Data with Hierarchical Structure</i><br></li>
        <li> Takanori Fujiwara: <i>Approaches and Challenges in Visual Analytics of Streaming High-dimensional Data</i><br></li>
        <li> Victor Mateevitsi: <i>SENSEI, Scalable in situ analysis and visualization</i><br></li>
        <li> Sudhanshu Sane: <i>Exploratory Time-Varying Flow Visualization via Lagrangian Representations</i></li>
        </ul>
    </td>
  </tr>
  <tr>
    <td>3:20pm &ndash; 3:30pm</td>
    <td>
      Best Paper Awards (Johanna Beyer)<br/>
      Closing Remarks (Kristi Potter)
    </td>
  </tr>
</table>

---

# Keynote

**Image-Based Graph Drawing: From a Million Nodes and Edges to a Million Pixels and Back**<br/>
_Professor Alex Telea, Utrecht University, Netherlands_

Visualizing large, multivariate, and time-dependent graphs is one of the grand challenges of information visualization. In recent years, image-based techniques have emerged as a powerful instrument to handle the visualization of big datasets. Yet, how these techniques, well proven for exploring data in scientific visualization and imaging, can be adapted to handle graph data, is still an open point. In this talk, I aim to provide the missing link between scivis, imaging, and graph visualization. I will explore the characteristics of scivis and imaging data that make it inherently amenable to multiscale visualization approaches, and next outline several directions by which graph data can be brought to the same form, thereby inheriting the desired scalable visualization options. Next, I will propose a taxonomy of multiscale graph visualization methods centered around the image-based approach. Examples will illustrate the added-value of image-based visualization of graphs from several domains. Finally, I will outline the open challenges of image-based methods for visualizing high-variate and time-dependent graphs.

#### Speaker

<img style="padding: 0; margin: 0 0 1em 1em; float: right; width: 20%" src="assets/telea.jpg" />
Alexandru C. Telea received his PhD (2000) in Computer Science from the Eindhoven University of Technology, the Netherlands. He was assistant professor in visualization and computer graphics at the same university (until 2007) and then full professor of visualization at the University of Groningen, the Netherlands. Since 2019 he is full professor of visual data analytics at Utrecht University, the Netherlands. His interests include high-dimensional visualization, visual analytics, and image-based information visualization. He is the author of the textbook "Data Visualization - Principles and Practice" (CRC Press, 2014).

<br>

---

# Posters
TBA.

<!--The LDAV posters session will take place virtually with IEEE VIS Poster Session via iPosters.

  * <a href="https://doi.org/10.1109/LDAV51489.2020.00013" target="new">A Distributed Algorithm for Force Directed Edge Bundling</a><br />
   _Yves Tuyishime, Yu Pan, Hongfeng Yu_
  
 -->
