<html>
<head>
    <title>Week 9 Homework</title>
    <meta charset="utf-8" />

  <!-- Import Vega & Vega-Lite (does not have to be from CDN) -->
  <script src="https://cdn.jsdelivr.net/npm/vega@5.4.0"></script>
  <script src="https://cdn.jsdelivr.net/npm/vega-lite@4.0.0-beta.1"></script>
  <script src="https://cdn.jsdelivr.net/npm/vega-embed@5"></script>
  
  <!-- CSS file -->
  <link rel="stylesheet" type="text/css" href="css/style.css" media="all">

</head>
<body>
<div id="choropleth"></div>

<script type="text/javascript">

  var spec2 = "https://raw.githubusercontent.com/imiirasolii/Homework4/main/Homework4/js/Chloropeth_Final.json";
  vegaEmbed('#choropleth', spec2).then(function(result) {
    // Access the Vega view instance (https://vega.github.io/vega/docs/api/view/) as result.view

  }).catch(console.error);
</script>

</body>
</html>
