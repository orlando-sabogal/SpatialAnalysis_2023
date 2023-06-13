<style>
@import url('https://fonts.googleapis.com/css2?family=Optima&display=swap');
</style>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');
</style>

<h1 style="text-align: center; font-family: 'Montserrat', sans-serif; font-weight: bold;">Spatial Analysis</h1>

<h2 style="font-family: 'Montserrat', sans-serif; font-weight: bold;">Introduction:</h2>
<p style="font-family: 'Optima', sans-serif;">
Throughout this course, we will delve into a diverse array of spatial analysis techniques, equipping you with the theoretical foundation and practical skills necessary to navigate spatial data challenges. Our journey will encompass essential topics, including geo-spatial operations, spatial autocorrelation, Moran's I, Local Indicators of Spatial Association (LISA), spatial regression, and Geographically Weighted Regression (GWR).
</p>

<p style="font-family: 'Optima', sans-serif;">
By immersing yourself in this course, you will cultivate a deep understanding of the underlying principles that drive these spatial analysis methodologies. Furthermore, you will gain proficiency in implementing these techniques using R, enabling you to effectively manipulate, analyze, and interpret spatial datasets. Through hands-on exercises, project work, and code examples, you will hone your practical abilities and develop the confidence to apply spatial analysis in diverse domains.
</p>


<table style="margin-left:auto; margin-right:auto;">
  <tr>
    <th style="text-align:center;">Presentations</th>
    <th style="text-align:center;">Tutorials</th>
  </tr>
  <tr>
    <td style="text-align:center;">
      <a href="https://github.com/orlando-sabogal/SpatialAnalysis_2023/blob/gh-pages/Presentations/00_Introduction.pdf" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Introductory Session</strong></a>
    </td>
    <td style="text-align:center;">
      <a href="https://orlando-sabogal.github.io/SpatialAnalysis_2023/Tutorials/02_R_Spatial/SpatialAnalysWithR.nb.html" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Spatial analysis with R</strong></a>
    </td>
  </tr>
  <tr>
    <td style="text-align:center;">
      <a href="https://github.com/orlando-sabogal/SpatialAnalysis_2023/blob/gh-pages/Presentations/01_SpatialAutocorrelation_Part_A.pdf" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Spatial Autocorrelation - Part A</strong></a>
    </td>
    <td style="text-align:center;">
      <a href="https://orlando-sabogal.github.io/SpatialAnalysis_2023/Tutorials/03_MapMaking/Tutorial_tmaps.nb.html" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Map Making - tmap</strong></a>
    </td>
  </tr>
  <tr>
    <td style="text-align:center;">
      <a href="https://github.com/orlando-sabogal/SpatialAnalysis_2023/blob/gh-pages/Presentations/01_SpatialAutocorrelation_Part_B.pdf" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Spatial Autocorrelation - Part B</strong></a>
    </td>
    <td style="text-align:center;">
      <a href="https://orlando-sabogal.github.io/SpatialAnalysis_2023/Tutorials/03_MapMaking/Tutorial_leaflet.nb.html" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Map Making - leaflet</strong></a>
    </td>
  </tr>
  <tr>
    <td style="text-align:center;">
      <a href="https://github.com/orlando-sabogal/SpatialAnalysis_2023/blob/gh-pages/Presentations/02_LISA.pdf" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>LISA</strong></a>
    </td>
    <td style="text-align:center;">
      <a href="https://orlando-sabogal.github.io/SpatialAnalysis_2023/Tutorials/04_MexicoCity_HTS/Data%20Wrangling.nb.html" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Case study: Mexico HTS</strong></a>
    </td>
  </tr>
  <tr>
    <td style="text-align:center;">
      <a href="https://github.com/orlando-sabogal/SpatialAnalysis_2023/blob/gh-pages/Presentations/03_LinearRegression.pdf" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Linear Regression</strong></a>
    </td>
    <td style="text-align:center;">
      <a href="#" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Linear Regression</strong></a>
    </td>
  </tr>
  <tr>
    <td style="text-align:center;">
      <a href="https://github.com/orlando-sabogal/SpatialAnalysis_2023/blob/gh-pages/Presentations/04_SpatialRegression.pdf" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Spatial Regression</strong></a>
    </td>
    <td style="text-align:center;">
      <a href="https://orlando-sabogal.github.io/SpatialAnalysis_2023/Tutorials/07_SpatialRegression/SpatialRegression.nb.html" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Spatial Regression</strong></a>
    </td>
  </tr>
  <tr>
    <td style="text-align:center;">
      <a href="https://github.com/orlando-sabogal/SpatialAnalysis_2023/blob/gh-pages/Presentations/05_GWR.pdf" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>GWR</strong></a>
    </td>
    <td style="text-align:center;">
      <a href="https://orlando-sabogal.github.io/SpatialAnalysis_2023/Tutorials/08_GWR/GWR.nb.html" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>GWR</strong></a>
    </td>
  </tr>
  <tr>
    <td style="text-align:center;">
      <a href="https://github.com/orlando-sabogal/SpatialAnalysis_2023/blob/gh-pages/Presentations/06_SpatialPaneModels.pdf" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Spatial Panel Models</strong></a>
    </td>
  </tr>
</table>



<h2 style="font-family: 'Montserrat', sans-serif; font-weight: bold;">Presentations:</h2>

<ul>
  <li>
    <a href="https://github.com/orlando-sabogal/SpatialAnalysis_2023/blob/gh-pages/Presentations/00_Introduction.pdf" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Introductory Session</strong></a>
  </li>
  <li>
    <a href="https://github.com/orlando-sabogal/SpatialAnalysis_2023/blob/gh-pages/Presentations/01_SpatialAutocorrelation_Part_A.pdf" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Spatial Autocorrelation - Part A</strong></a>
  </li>
  <li>
    <a href="https://github.com/orlando-sabogal/SpatialAnalysis_2023/blob/gh-pages/Presentations/01_SpatialAutocorrelation_Part_B.pdf" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Spatial Autocorrelation - Part B</strong></a>
  </li>
  <li>
    <a href="https://github.com/orlando-sabogal/SpatialAnalysis_2023/blob/gh-pages/Presentations/02_LISA.pdf" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>LISA</strong></a>
  </li>
  <li>
    <a href="https://github.com/orlando-sabogal/SpatialAnalysis_2023/blob/gh-pages/Presentations/03_LinearRegression.pdf" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Linear Regression</strong></a>
  </li>
  <li>
    <a href="https://github.com/orlando-sabogal/SpatialAnalysis_2023/blob/gh-pages/Presentations/04_SpatialRegression.pdf" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Spatial Regression</strong></a>
  </li>
  <li>
    <a href="https://github.com/orlando-sabogal/SpatialAnalysis_2023/blob/gh-pages/Presentations/05_GWR.pdf" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>GWR</strong></a>
  </li>
  <li>
    <a href="https://github.com/orlando-sabogal/SpatialAnalysis_2023/blob/gh-pages/Presentations/06_SpatialPaneModels.pdf" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Spatial Panel Models</strong></a>
  </li>
</ul>


<h2 style="font-family: 'Montserrat', sans-serif; font-weight: bold;">Tutorials:</h2>

<ul>
  <li>
    <a href="https://orlando-sabogal.github.io/SpatialAnalysis_2023/Tutorials/02_R_Spatial/SpatialAnalysWithR.nb.html" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Spatial analysis with R</strong></a>
  </li>
  <li>
    <a href="https://orlando-sabogal.github.io/SpatialAnalysis_2023/Tutorials/03_MapMaking/Tutorial_tmaps.nb.html" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Map Making - tmap</strong></a>
  </li>
  <li>
    <a href="https://orlando-sabogal.github.io/SpatialAnalysis_2023/Tutorials/03_MapMaking/Tutorial_leaflet.nb.html" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Map Making - leaflet</strong></a>
  </li>
  <li>
    <a href="https://orlando-sabogal.github.io/SpatialAnalysis_2023/Tutorials/04_MexicoCity_HTS/Data%20Wrangling.nb.html" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Case study: Mexico HTS</strong></a>
  </li>
  <li>
    <a href="https://orlando-sabogal.github.io/SpatialAnalysis_2023/Tutorials/05_MoransI/MoransI.nb.html" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Moran's I</strong></a>
  </li>
  <li>
    <a href="#" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Linear Regression</strong></a>
  </li>
  <li>
    <a href="https://orlando-sabogal.github.io/SpatialAnalysis_2023/Tutorials/07_SpatialRegression/SpatialRegression.nb.html" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>Spatial Regression</strong></a>
  </li>
  <li>
    <a href="https://orlando-sabogal.github.io/SpatialAnalysis_2023/Tutorials/08_GWR/GWR.nb.html" style="font-family: 'Optima', sans-serif; color: #0000ff; text-decoration: none;" onmouseover="this.style.fontSize='110%'; this.style.color='#00008b';" onmouseout="this.style.fontSize='100%'; this.style.color='#0000ff';"><strong>GWR</strong></a>
  </li>
</ul>
