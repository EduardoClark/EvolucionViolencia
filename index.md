---
title       : Evolución de la Violencia
subtitle    : Reporte Primer Trimestre 2013
author      : Instituto Mexicano para la Competitividad A.C.
job         : 
logo        : IMCO
biglogo     : IMCOBIG
license     : by-nc-sa
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax, bootstrap, quiz]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
github:
  user: EduardoClark
  repo: EvolucionViolencia
  
  
---


## Enero 2013

<div class='source4'>
<a rel="tooltip" data-original-title="La serie ajustada por estacionalidad representa el numero de averiguaciones previas por homicidio doloso descontando los efectos estacionales propios de cada mes. Es decir ajusta para poder hacer una comparación directa entre meses. <br> La serie tendencia utiliza un promedio movil ponderado de 10 meses. ">Descripción</a>
</div>


<!-- BarChart generated in R 2.15.3 by googleVis 0.4.2 package -->
<!-- Wed Apr  3 16:28:36 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataBarChartID6c1b1ccab3cd () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 "Enero 2013",
1544,
1579,
1591 
] 
];
data.addColumn('string','Mes');
data.addColumn('number','Original');
data.addColumn('number','Ajustada');
data.addColumn('number','Tendencial');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartBarChartID6c1b1ccab3cd() {
  var data = gvisDataBarChartID6c1b1ccab3cd();
  var options = {};
options["allowHtml"] = true;
options["width"] =    900;
options["height"] =    300;
options["colors"] = ['#E64343', '#999999', '#585454'];
options["hAxis"] = {
 "viewWindowMode": "explicit",
"viewWindow": {
 "max":   1800,
"min":      0 
} 
};


     var chart = new google.visualization.BarChart(
       document.getElementById('BarChartID6c1b1ccab3cd')
     );
     chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  var chartid = "corechart";

  // Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
  var i, newPackage = true;
  for (i = 0; newPackage && i < pkgs.length; i++) {
    if (pkgs[i] === chartid)
      newPackage = false;
  }
  if (newPackage)
    pkgs.push(chartid);

  // Add the drawChart function to the global list of callbacks
  callbacks.push(drawChartBarChartID6c1b1ccab3cd);
})();
function displayChartBarChartID6c1b1ccab3cd() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
    var pkgCount = pkgs.length;
    google.load("visualization", "1", { packages:pkgs, callback: function() {
      if (pkgCount != pkgs.length) {
        // Race condition where another setTimeout call snuck in after us; if
        // that call added a package, we must not shift its callback
        return;
      }
      while (callbacks.length > 0)
        callbacks.shift()();
    } });
  }, 100);
}
 
// jsFooter
 </script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartBarChartID6c1b1ccab3cd"></script>
 
<!-- divChart -->
  
<div id="BarChartID6c1b1ccab3cd"
  style="width: 900px; height: 300px;">
</div>


<div style="float: left; width: 50%;">
<body>
<basefont color="black" face="Open Sans Bold" size="8">
Homicidios Dolosos(SNSP)*:<br><br>
<font color="black" face="Open Sans" size="5">
<ul>
<li>Totales: 1,544</li>
<li>Con arma de fuego: 788</li>
</ul>
</font>
</div>
<div style="float: right; width: 50%;">
<body>
<basefont color="black" face="Open Sans Bold" size="8">
Variación Diciembre-Enero: <br><br>
<font color="black" face="Open Sans Bold" size="5">
<ul>
<li> Serie SNSP: -1.6% </li>
<li> Ajustado por Estacionalidad**: -2.4% </li>
<li> Tendencial**: -0.8% </li>
</ul>
</font>
<br><br>
</div>

<div class='source'>
  *Fuente: <a href='http://www.secretariadoejecutivosnsp.gob.mx/work/models/SecretariadoEjecutivo/Resource/131/1/images/CIEISP2013_260313.pdf'>Secretariado Ejecutivo del Sistema Nacional de Seguridad Pública</a>
</div>

<div class='source1'>
  **Ver Nota Metodologica: <a href=http://dl.dropbox.com/s/gn4e5rbck0orw7x/Nota%20t%C3%A9cnica.pdf?token_hash=AAHX4D8XJb8-OA7Ompt4HVH8EnfhqCgr84IVOv21bLVA_w&dl=1'>Ajuste Estacional de Base de Datos de Homicidios SESNSP</a>
</div>




---

## Febrero 2013


<!-- BarChart generated in R 2.15.3 by googleVis 0.4.2 package -->
<!-- Wed Apr  3 16:29:59 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataBarChartID6c5932779ca5 () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 "Febrero 2013",
1432,
1568,
1591 
] 
];
data.addColumn('string','Mes');
data.addColumn('number','Original');
data.addColumn('number','Ajustada');
data.addColumn('number','Tendencial');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartBarChartID6c5932779ca5() {
  var data = gvisDataBarChartID6c5932779ca5();
  var options = {};
options["allowHtml"] = true;
options["width"] =    900;
options["height"] =    300;
options["colors"] = ['#E64343', '#999999', '#585454'];
options["hAxis"] = {
 "viewWindowMode": "explicit",
"viewWindow": {
 "max":   1800,
"min":      0 
} 
};

     var chart = new google.visualization.BarChart(
       document.getElementById('BarChartID6c5932779ca5')
     );
     chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  var chartid = "corechart";

  // Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
  var i, newPackage = true;
  for (i = 0; newPackage && i < pkgs.length; i++) {
    if (pkgs[i] === chartid)
      newPackage = false;
  }
  if (newPackage)
    pkgs.push(chartid);

  // Add the drawChart function to the global list of callbacks
  callbacks.push(drawChartBarChartID6c5932779ca5);
})();
function displayChartBarChartID6c5932779ca5() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
    var pkgCount = pkgs.length;
    google.load("visualization", "1", { packages:pkgs, callback: function() {
      if (pkgCount != pkgs.length) {
        // Race condition where another setTimeout call snuck in after us; if
        // that call added a package, we must not shift its callback
        return;
      }
      while (callbacks.length > 0)
        callbacks.shift()();
    } });
  }, 100);
}
 
// jsFooter
 </script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartBarChartID6c5932779ca5"></script>
 
<!-- divChart -->
  
<div id="BarChartID6c5932779ca5"
  style="width: 900px; height: 300px;">
</div>


<div style="float: left; width: 50%;">
<body>
<basefont color="black" face="Open Sans Bold" size="8">
Homicidios Dolosos (SNSP):<br><br>
<font color="black" face="Open Sans" size="5">
<ul>
<li>Totales: 1,432</li>
<li>Con arma de fuego: 729</li>
</ul>
</font>
</div>
<div style="float: right; width: 50%;">
<body>
<basefont color="black" face="Open Sans Bold" size="8">
Variación Enero-Febrero: <br><br>
<font color="black" face="Open Sans Bold" size="5">
<ul>
<li> Serie SNSP: -7.3% </li>
<li> Ajustado por Estacionalidad: -0.6% </li>
<li> Tendencial: 0% </li>
</ul>
</font>
<br><br>
</div>

<div class='source4'>
<a rel="tooltip" data-original-title="La serie Ajustada por Estacionalidad representa el numero de averiguaciones previas por homicidio doloso descontando los efectos estacionales propios de cada mes. Es decir ajusta para poder hacer una comparación directa entre meses. <br> La serie tendencia utiliza un promedio movil ponderado de 10 meses. ">Descripción</a>
</div>


---

## Marzo 2013

<!-- BarChart generated in R 2.15.3 by googleVis 0.4.2 package -->
<!-- Wed Apr  3 16:29:59 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataBarChartID6c5932779ca6 () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 "Marzo 2013",
1432,
1568,
1591 
] 
];
data.addColumn('string','Mes');
data.addColumn('number','Original');
data.addColumn('number','Ajustada');
data.addColumn('number','Tendencial');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartBarChartID6c5932779ca6() {
  var data = gvisDataBarChartID6c5932779ca6();
  var options = {};
options["allowHtml"] = true;
options["width"] =    900;
options["height"] =    300;
options["colors"] = ['#E64343', '#999999', '#585454'];
options["hAxis"] = {
 "viewWindowMode": "explicit",
"viewWindow": {
 "max":   1800,
"min":      0 
} 
};

     var chart = new google.visualization.BarChart(
       document.getElementById('BarChartID6c5932779ca6')
     );
     chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  var chartid = "corechart";

  // Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
  var i, newPackage = true;
  for (i = 0; newPackage && i < pkgs.length; i++) {
    if (pkgs[i] === chartid)
      newPackage = false;
  }
  if (newPackage)
    pkgs.push(chartid);

  // Add the drawChart function to the global list of callbacks
  callbacks.push(drawChartBarChartID6c5932779ca6);
})();
function displayChartBarChartID6c5932779ca6() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
    var pkgCount = pkgs.length;
    google.load("visualization", "1", { packages:pkgs, callback: function() {
      if (pkgCount != pkgs.length) {
        // Race condition where another setTimeout call snuck in after us; if
        // that call added a package, we must not shift its callback
        return;
      }
      while (callbacks.length > 0)
        callbacks.shift()();
    } });
  }, 100);
}
 
// jsFooter
 </script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartBarChartID6c5932779ca6"></script>
 
<!-- divChart -->
  
<div id="BarChartID6c5932779ca6"
  style="width: 900px; height: 300px;">
</div>





<div style="float: left; width: 50%;">
<body>
<basefont color="black" face="Open Sans Bold" size="8">
Homicidios Dolosos (SNSP):<br><br>
<font color="black" face="Open Sans" size="5">
<ul>
<li>Totales: 1,432</li>
<li>Con arma de fuego: 729</li>
</ul>
</font>
</div>
<div style="float: right; width: 50%;">
<body>
<basefont color="black" face="Open Sans Bold" size="8">
Variación Febrero-Marzo: <br><br>
<font color="black" face="Open Sans Bold" size="5">
<ul>
<li> Serie SNSP: -7.3% </li>
<li> Ajustado por Estacionalidad: -0.6% </li>
<li> Tendencial: 0% </li>
</ul>
</font>
<br><br>
</div>

<div class='source4'>
<a rel="tooltip" data-original-title="La serie Ajustada por Estacionalidad representa el numero de averiguaciones previas por homicidio doloso descontando los efectos estacionales propios de cada mes. Es decir ajusta para poder hacer una comparación directa entre meses. <br> La serie tendencia utiliza un promedio movil ponderado de 10 meses. ">Descripción</a>
</div>

---

## Primer Trimestre 2013

<div class='source4'>
<a rel="tooltip" data-original-title="La serie Ajustada por Estacionalidad representa el numero de averiguaciones previas por homicidio doloso descontando los efectos estacionales propios de cada mes. Es decir ajusta para poder hacer una comparación directa entre meses. <br> La serie tendencia utiliza un promedio movil ponderado de 10 meses. ">Descripción</a>
</div>


<!-- BarChart generated in R 2.15.3 by googleVis 0.4.2 package -->
<!-- Wed Apr  3 16:29:59 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataBarChartID6c5932779ca7 () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 "1er Trimestre 2013",
1432,
1568,
1591 
] 
];
data.addColumn('string','Mes');
data.addColumn('number','Original');
data.addColumn('number','Ajustada');
data.addColumn('number','Tendencial');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartBarChartID6c5932779ca7() {
  var data = gvisDataBarChartID6c5932779ca7();
  var options = {};
options["allowHtml"] = true;
options["width"] =    900;
options["height"] =    300;
options["colors"] = ['#E64343', '#999999', '#585454'];
options["hAxis"] = {
 "viewWindowMode": "explicit",
"viewWindow": {
 "max":   1800,
"min":      0 
} 
};

     var chart = new google.visualization.BarChart(
       document.getElementById('BarChartID6c5932779ca7')
     );
     chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  var chartid = "corechart";

  // Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
  var i, newPackage = true;
  for (i = 0; newPackage && i < pkgs.length; i++) {
    if (pkgs[i] === chartid)
      newPackage = false;
  }
  if (newPackage)
    pkgs.push(chartid);

  // Add the drawChart function to the global list of callbacks
  callbacks.push(drawChartBarChartID6c5932779ca7);
})();
function displayChartBarChartID6c5932779ca7() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
    var pkgCount = pkgs.length;
    google.load("visualization", "1", { packages:pkgs, callback: function() {
      if (pkgCount != pkgs.length) {
        // Race condition where another setTimeout call snuck in after us; if
        // that call added a package, we must not shift its callback
        return;
      }
      while (callbacks.length > 0)
        callbacks.shift()();
    } });
  }, 100);
}
 
// jsFooter
 </script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartBarChartID6c5932779ca7"></script>
 
<!-- divChart -->
  
<div id="BarChartID6c5932779ca7"
  style="width: 900px; height: 300px;">
</div>



<div style="float: left; width: 50%;">
<body>
<basefont color="black" face="Open Sans Bold" size="8">
Homicidios Dolosos (SNSP):<br><br>
<font color="black" face="Open Sans" size="5">
<ul>
<li>Totales: 1,432</li>
<li>Con arma de fuego: 729</li>
</ul>
</font>
</div>
<div style="float: right; width: 50%;">
<body>
<basefont color="black" face="Open Sans Bold" size="8">
Variación 4to Trimestre 2012- 1er Trimestre 2013: <br><br>
<font color="black" face="Open Sans Bold" size="5">
<ul>
<li> Serie SNSP: -7.3% </li>
<li> Ajustado por Estacionalidad: -0.6% </li>
<li> Tendencial: 0% </li>
</ul>
</font>
<br><br>
</div>



---

## Situación Estatal
# Marzo: 2012 vs. 2013

<div class='source4'>
<a rel="tooltip" data-original-title="El mapa compara el numero de APs por homicidio doloso por estado para los meses de Marzo 2012 y Marzo 2013. Aquellos estados en azul presentaron un menor numero de APs en Marzo 2013 que en Marzo 2012, mientras que los estados en rojo lo opuesto. Ademas se proporciona el cambio porcentual entre estos dos meses y el numero de APs por estado para el periodo Marzo 2013.">Descripción</a>
</div>

<!-- GeoChart generated in R 2.15.3 by googleVis 0.4.2 package -->
<!-- Wed Apr  3 17:06:30 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataGeoChartID6ef827871b77 () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 "Aguascalientes",
-40,
7 
],
[
 "Baja California",
17,
114 
],
[
 "Baja California Sur",
0,
6 
],
[
 "Campeche",
0,
5 
],
[
 "Chiapas",
29,
96 
],
[
 "Chihuahua",
-40.7,
229 
],
[
 "Coahuila",
-11.8,
119 
],
[
 "Colima",
9.1,
58 
],
[
 "Distrito Federal",
-16.8,
131 
],
[
 "Durango",
-36.5,
92 
],
[
 "Guanajuato",
-8.5,
80 
],
[
 "Guerrero",
27.3,
329 
],
[
 "Hidalgo",
16.7,
7 
],
[
 "Jalisco",
15.3,
113 
],
[
 "México",
17.2,
136 
],
[
 "Michoacán",
11.1,
50 
],
[
 "Morelos",
25.5,
59 
],
[
 "Nayarit",
-47.6,
11 
],
[
 "Nuevo León",
-63.8,
71 
],
[
 "Oaxaca",
-3,
32 
],
[
 "Puebla",
1.8,
56 
],
[
 "Querétaro",
83.3,
11 
],
[
 "Quintana Roo",
-43.5,
13 
],
[
 "San Luis Potosí",
114.3,
30 
],
[
 "Sinaloa",
-37.5,
75 
],
[
 "Sonora",
27.3,
42 
],
[
 "Tabasco",
40,
7 
],
[
 "Tamaulipas",
-31.1,
42 
],
[
 "Tlaxcala",
75,
7 
],
[
 "Veracruz",
-1.9,
51 
],
[
 "Yucatán",
0,
2
],
[
 "Zacatecas",
14.3,
8
] 
];
data.addColumn('string','Entidad');
data.addColumn('number','Cambio Marzo 2012 Vs Marzo 2013 (%)');
data.addColumn('number', 'Homicidios Febrero 2013');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartGeoChartID6ef827871b77() {
  var data = gvisDataGeoChartID6ef827871b77();
  var options = {};
options["width"] =   1000;
options["height"] =    450;
options["region"] = "MX";
options["displayMode"] = "regions";
options["resolution"] = "provinces";
options["colorAxis"] = {minValue: -100, maxValue: 100,  colors: ['royalblue', "white",  '#E64343']};
options["legend"] = {numberFormat: "#.#'%"};

     var chart = new google.visualization.GeoChart(
       document.getElementById('GeoChartID6ef827871b77')
     );
     chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  var chartid = "geochart";

  // Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
  var i, newPackage = true;
  for (i = 0; newPackage && i < pkgs.length; i++) {
    if (pkgs[i] === chartid)
      newPackage = false;
  }
  if (newPackage)
    pkgs.push(chartid);

  // Add the drawChart function to the global list of callbacks
  callbacks.push(drawChartGeoChartID6ef827871b77);
})();
function displayChartGeoChartID6ef827871b77() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
    var pkgCount = pkgs.length;
    google.load("visualization", "1", { packages:pkgs, callback: function() {
      if (pkgCount != pkgs.length) {
        // Race condition where another setTimeout call snuck in after us; if
        // that call added a package, we must not shift its callback
        return;
      }
      while (callbacks.length > 0)
        callbacks.shift()();
    } });
  }, 100);
}
 
// jsFooter
 </script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartGeoChartID6ef827871b77"></script>
 
<!-- divChart -->
  
<div id="GeoChartID6ef827871b77"
  style="width: 800px; height: 450px;">
</div>




---

## Situación Estatal
# Primer Trimestre: 2012 vs. 2013


<!-- GeoChart generated in R 2.15.3 by googleVis 0.4.2 package -->
<!-- Wed Apr  3 17:13:18 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataGeoChartID6f7b8361559 () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 "Aguascalientes",
0,
7 
],
[
 "Baja California",
4.6,
114 
],
[
 "Baja California Sur",
-14.3,
6 
],
[
 "Campeche",
-50,
5 
],
[
 "Chiapas",
23.1,
96 
],
[
 "Chihuahua",
-40.7,
229 
],
[
 "Coahuila",
14.4,
119 
],
[
 "Colima",
38.1,
58 
],
[
 "Distrito Federal",
0,
131 
],
[
 "Durango",
-23.3,
92 
],
[
 "Guanajuato",
-7,
80 
],
[
 "Guerrero",
12.7,
329 
],
[
 "Hidalgo",
225,
25 
],
[
 "Jalisco",
15.2,
212 
],
[
 "México",
28.1,
287 
],
[
 "Michoacán",
3,
103 
],
[
 "Morelos",
11.1,
110 
],
[
 "Nayarit",
-43.2,
25 
],
[
 "Nuevo León",
-47.8,
180 
],
[
 "Oaxaca",
-37,
58 
],
[
 "Puebla",
-20.8,
95 
],
[
 "Querétaro",
23.1,
16 
],
[
 "Quintana Roo",
-32.7,
33 
],
[
 "San Luis Potosí",
28.9,
49 
],
[
 "Sinaloa",
-17.9,
184 
],
[
 "Sonora",
3.9,
79 
],
[
 "Tabasco",
-20,
16 
],
[
 "Tamaulipas",
-23.6,
110 
],
[
 "Tlaxcala",
160,
13 
],
[
 "Veracruz",
-1.1,
91 
],
[
 "Yucatán",
-40,
3 
],
[
 "Zacatecas",
-8.3,
22 
] 
];
data.addColumn('string','Entidad');
data.addColumn('number','Cambio 2012 vs 2013 (%)');
data.addColumn('number','Homicidios Enero Y Febrero 2013');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartGeoChartID6f7b8361559() {
  var data = gvisDataGeoChartID6f7b8361559();
  var options = {};
options["width"] =    1000;
options["height"] =    450;
options["region"] = "MX";
options["displayMode"] = "regions";
options["resolution"] = "provinces";
options["colorAxis"] = {minValue: -50, maxValue: 50,  colors: ['royalblue', "white",  '#E64343']};
options["legend"] = {numberFormat: "#.#'%"};

     var chart = new google.visualization.GeoChart(
       document.getElementById('GeoChartID6f7b8361559')
     );
     chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  var chartid = "geochart";

  // Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
  var i, newPackage = true;
  for (i = 0; newPackage && i < pkgs.length; i++) {
    if (pkgs[i] === chartid)
      newPackage = false;
  }
  if (newPackage)
    pkgs.push(chartid);

  // Add the drawChart function to the global list of callbacks
  callbacks.push(drawChartGeoChartID6f7b8361559);
})();
function displayChartGeoChartID6f7b8361559() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
    var pkgCount = pkgs.length;
    google.load("visualization", "1", { packages:pkgs, callback: function() {
      if (pkgCount != pkgs.length) {
        // Race condition where another setTimeout call snuck in after us; if
        // that call added a package, we must not shift its callback
        return;
      }
      while (callbacks.length > 0)
        callbacks.shift()();
    } });
  }, 100);
}
 
// jsFooter
 </script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartGeoChartID6f7b8361559"></script>
 
<!-- divChart -->
  
<div id="GeoChartID6f7b8361559"
  style="width: 1000px; height: 600px;">
</div>

<div class='source4'>
<a rel="tooltip" data-original-title="El mapa compara el numero de APs de Homicidio Doloso por estado para el primer trimestre de 2012 y el primer trimestre de 2013. Aquellos estados en azul presentaron un menor numero de APs en 2013 que en 2012, mientras que los estados en rojo lo opuesto. Ademas se proporciona el cambio porcentual entre estos dos trimestres y el numero de APs por estado para el primer trimestre de 2013.">Descripción</a>
</div>

---

## Proyecciones

<!-- ColumnChart generated in R 2.15.3 by googleVis 0.4.2 package -->
<!-- Tue Apr  9 16:05:10 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataColumnChartID24e7724c982 () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 "Abril 2013",
1657,
1604,
1551 
],
[
 "Mayo 2013",
1667,
1605,
1543 
] 
];
data.addColumn('string','Mes');
data.addColumn('number','Estimado Alto');
data.addColumn('number','Mejor Estimado');
data.addColumn('number','Estimado Bajo');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartColumnChartID24e7724c982() {
  var data = gvisDataColumnChartID24e7724c982();
  var options = {};
options["allowHtml"] = true;
options["width"] =    950;
options["height"] =    300;
options["colors"] = ['#585454', '#E64343', '#999999'];
options["vAxis"] = {
 "viewWindowMode": "explicit",
 "title" : "Homicidios Dolosos",
"viewWindow": {
 "max":   1800,
"min":      0 
} 
};


     var chart = new google.visualization.ColumnChart(
       document.getElementById('ColumnChartID24e7724c982')
     );
     chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  var chartid = "corechart";

  // Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
  var i, newPackage = true;
  for (i = 0; newPackage && i < pkgs.length; i++) {
    if (pkgs[i] === chartid)
      newPackage = false;
  }
  if (newPackage)
    pkgs.push(chartid);

  // Add the drawChart function to the global list of callbacks
  callbacks.push(drawChartColumnChartID24e7724c982);
})();
function displayChartColumnChartID24e7724c982() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
    var pkgCount = pkgs.length;
    google.load("visualization", "1", { packages:pkgs, callback: function() {
      if (pkgCount != pkgs.length) {
        // Race condition where another setTimeout call snuck in after us; if
        // that call added a package, we must not shift its callback
        return;
      }
      while (callbacks.length > 0)
        callbacks.shift()();
    } });
  }, 100);
}
 
// jsFooter
 </script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartColumnChartID24e7724c982"></script>
 
<!-- divChart -->
  
<div id="ColumnChartID24e7724c982"
  style="width: 650px; height: 300px;">
</div>

<div style="float: left; width: 50%;">
<body>
<basefont color="black" face="Open Sans Bold" size="8">
Estimación Abril 2013:<br><br>
<font color="black" face="Open Sans" size="5">
<ul>
<li> Homicidios Dolosos: 1,604</li>
</ul>
</font>
</div>

<div style="float: right; width: 50%;">
<body>
<basefont color="black" face="Open Sans Bold" size="8">
Proyección Mayo 2013:<br><br>
<font color="black" face="Open Sans" size="5">
<ul>
<li> Averiguaciones Previas de Homicidios Dolosos: 1,605 </li>
</ul>
</font>
</div>



---

## Serie Ajustada por Estacionalidad
# 1997-2013


<!-- AreaChart generated in R 2.15.3 by googleVis 0.4.2 package -->
<!-- Tue Apr  9 14:47:02 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataAreaChartID7c02224e1bba () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 "Diciembre 2006",
1021 
],
[
 "2007-01-01",
798 
],
[
 "2007-02-01",
720 
],
[
 "2007-03-01",
911 
],
[
 "2007-04-01",
912 
],
[
 "2007-05-01",
1010 
],
[
 "2007-06-01",
894 
],
[
 "2007-07-01",
795 
],
[
 "2007-08-01",
795 
],
[
 "2007-09-01",
830 
],
[
 "2007-10-01",
865 
],
[
 "2007-11-01",
885 
],
[
 "Diciembre 2007",
838 
],
[
 "2008-01-01",
932 
],
[
 "2008-02-01",
866 
],
[
 "2008-03-01",
987 
],
[
 "2008-04-01",
961 
],
[
 "2008-05-01",
1159 
],
[
 "2008-06-01",
1118 
],
[
 "2008-07-01",
1154 
],
[
 "2008-08-01",
1120 
],
[
 "2008-09-01",
1074 
],
[
 "2008-10-01",
1275 
],
[
 "2008-11-01",
1330 
],
[
 "Diciembre 2008",
1179 
],
[
 "2009-01-01",
1184 
],
[
 "2009-02-01",
1266 
],
[
 "2009-03-01",
1193 
],
[
 "2009-04-01",
1232 
],
[
 "2009-05-01",
1268 
],
[
 "2009-06-01",
1400 
],
[
 "2009-07-01",
1375 
],
[
 "2009-08-01",
1439 
],
[
 "2009-09-01",
1478 
],
[
 "2009-10-01",
1358 
],
[
 "2009-11-01",
1349 
],
[
 "Diciembre 2009",
1576 
],
[
 "2010-01-01",
1610 
],
[
 "2010-02-01",
1368 
],
[
 "2010-03-01",
1674 
],
[
 "2010-04-01",
1715 
],
[
 "2010-05-01",
1883 
],
[
 "2010-06-01",
1878 
],
[
 "2010-07-01",
1817 
],
[
 "2010-08-01",
1875 
],
[
 "2010-09-01",
1689 
],
[
 "2010-10-01",
1947 
],
[
 "2010-11-01",
1546 
],
[
 "Diciembre 2010",
1679 
],
[
 "2011-01-01",
1850 
],
[
 "2011-02-01",
1661 
],
[
 "2011-03-01",
1875 
],
[
 "2011-04-01",
1882 
],
[
 "2011-05-01",
2101 
],
[
 "2011-06-01",
2027 
],
[
 "2011-07-01",
1971 
],
[
 "2011-08-01",
1964 
],
[
 "2011-09-01",
1809 
],
[
 "2011-10-01",
1904 
],
[
 "2011-11-01",
1739 
],
[
 "Diciembre 2011",
1697 
],
[
 "2012-01-01",
1657 
],
[
 "2012-02-01",
1621 
],
[
 "2012-03-01",
1762 
],
[
 "2012-04-01",
1783 
],
[
 "2012-05-01",
1938 
],
[
 "2012-06-01",
1787 
],
[
 "2012-07-01",
1727 
],
[
 "2012-08-01",
1851 
],
[
 "2012-09-01",
1812 
],
[
 "2012-10-01",
1549 
],
[
 "2012-11-01",
1512 
],
[
 "Diciembre 2012",
1569 
],
[
 "2013-01-01",
1544 
],
[
 "2013-02-01",
1432 
] 
];
data.addColumn('string','Date');
data.addColumn('number','Serie Original');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartAreaChartID7c02224e1bba() {
  var data = gvisDataAreaChartID7c02224e1bba();
  var options = {};
options["allowHtml"] = true;
options["width"] =   1050;
options["height"] =    500;
options["colors"] = ['green', ];
options["focusTarget"] = "category";
options["legend.position"] = "none";
options["areaOpacity"] =      0;
options["legend.position"] = "none";
options["hAxis"] = {
 "textPosition": "out",
  "showTextEvery" : 12
};
options["vAxis"] = {
  "title" : "Homicidios Dolosos por Mes",
 };

     var chart = new google.visualization.AreaChart(
       document.getElementById('AreaChartID7c02224e1bba')
     );
     chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  var chartid = "corechart";

  // Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
  var i, newPackage = true;
  for (i = 0; newPackage && i < pkgs.length; i++) {
    if (pkgs[i] === chartid)
      newPackage = false;
  }
  if (newPackage)
    pkgs.push(chartid);

  // Add the drawChart function to the global list of callbacks
  callbacks.push(drawChartAreaChartID7c02224e1bba);
})();
function displayChartAreaChartID7c02224e1bba() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
    var pkgCount = pkgs.length;
    google.load("visualization", "1", { packages:pkgs, callback: function() {
      if (pkgCount != pkgs.length) {
        // Race condition where another setTimeout call snuck in after us; if
        // that call added a package, we must not shift its callback
        return;
      }
      while (callbacks.length > 0)
        callbacks.shift()();
    } });
  }, 100);
}
 
// jsFooter
 </script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartAreaChartID7c02224e1bba"></script>
 
<!-- divChart -->
  
<div id="AreaChartID7c02224e1bba"
  style="width: 1000px; height: 700px;">
</div>

<div class='source1'>
  Descarga: <a href=http://dl.dropbox.com/s/2c4e73poxyd9fof/SerieFinal.csv?token_hash=AAFWSoR4JIyqFR-Kf0CWVKpIAuN5sMgN9jjKBNtrS-HBRg&dl=1'>Base de Datos de Homicidios SESNSP (Ajustada por Estacionalidad) </a>
</div>

<div class='source4'>
<a rel="tooltip" data-original-title="El siguiente gráfico presenta la serie de tiempo de Averiguaciones Previas por Homicidio Doloso entre Diciembre 2006 y Marzo 2013.">Descripción</a>
</div>


---

## Serie Ajustada por Estacionalidad
# 1997-2013

<div class='source4'>
<a rel="tooltip" data-original-title="">Descripción</a>
</div>

<!-- AreaChart generated in R 2.15.3 by googleVis 0.4.2 package -->
<!-- Tue Apr  9 14:50:26 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataAreaChartID7c5e64f6746d () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 "Diciembre 2006",
1021,
1031 
],
[
 "2007-01-01",
798,
803 
],
[
 "2007-02-01",
720,
774 
],
[
 "2007-03-01",
911,
886 
],
[
 "2007-04-01",
912,
899 
],
[
 "2007-05-01",
1010,
934 
],
[
 "2007-06-01",
894,
862 
],
[
 "2007-07-01",
795,
798 
],
[
 "2007-08-01",
795,
803 
],
[
 "2007-09-01",
830,
853 
],
[
 "2007-10-01",
865,
862 
],
[
 "2007-11-01",
885,
911 
],
[
 "Diciembre 2007",
838,
851 
],
[
 "2008-01-01",
932,
941 
],
[
 "2008-02-01",
866,
935 
],
[
 "2008-03-01",
987,
965 
],
[
 "2008-04-01",
961,
951 
],
[
 "2008-05-01",
1159,
1071 
],
[
 "2008-06-01",
1118,
1073 
],
[
 "2008-07-01",
1154,
1152 
],
[
 "2008-08-01",
1120,
1121 
],
[
 "2008-09-01",
1074,
1099 
],
[
 "2008-10-01",
1275,
1269 
],
[
 "2008-11-01",
1330,
1375 
],
[
 "Diciembre 2008",
1179,
1202 
],
[
 "2009-01-01",
1184,
1198 
],
[
 "2009-02-01",
1266,
1372 
],
[
 "2009-03-01",
1193,
1172 
],
[
 "2009-04-01",
1232,
1222 
],
[
 "2009-05-01",
1268,
1172 
],
[
 "2009-06-01",
1400,
1340 
],
[
 "2009-07-01",
1375,
1366 
],
[
 "2009-08-01",
1439,
1427 
],
[
 "2009-09-01",
1478,
1507 
],
[
 "2009-10-01",
1358,
1352 
],
[
 "2009-11-01",
1349,
1406 
],
[
 "Diciembre 2009",
1576,
1612 
],
[
 "2010-01-01",
1610,
1632 
],
[
 "2010-02-01",
1368,
1489 
],
[
 "2010-03-01",
1674,
1649 
],
[
 "2010-04-01",
1715,
1699 
],
[
 "2010-05-01",
1883,
1735 
],
[
 "2010-06-01",
1878,
1791 
],
[
 "2010-07-01",
1817,
1798 
],
[
 "2010-08-01",
1875,
1846 
],
[
 "2010-09-01",
1689,
1716 
],
[
 "2010-10-01",
1947,
1938 
],
[
 "2010-11-01",
1546,
1622 
],
[
 "Diciembre 2010",
1679,
1725 
],
[
 "2011-01-01",
1850,
1882 
],
[
 "2011-02-01",
1661,
1815 
],
[
 "2011-03-01",
1875,
1850 
],
[
 "2011-04-01",
1882,
1864 
],
[
 "2011-05-01",
2101,
1931 
],
[
 "2011-06-01",
2027,
1930 
],
[
 "2011-07-01",
1971,
1946 
],
[
 "2011-08-01",
1964,
1922 
],
[
 "2011-09-01",
1809,
1831 
],
[
 "2011-10-01",
1904,
1897 
],
[
 "Diciembre 2011",
1739,
1830 
],
[
 "Diciembre 2011",
1697,
1748 
],
[
 "2012-01-01",
1657,
1691 
],
[
 "2012-02-01",
1621,
1775 
],
[
 "2012-03-01",
1762,
1741 
],
[
 "2012-04-01",
1783,
1766 
],
[
 "2012-05-01",
1938,
1779 
],
[
 "2012-06-01",
1787,
1702 
],
[
 "2012-07-01",
1727,
1704 
],
[
 "2012-08-01",
1851,
1805 
],
[
 "2012-09-01",
1812,
1827 
],
[
 "2012-10-01",
1549,
1547 
],
[
 "2012-11-01",
1512,
1593 
],
[
 "Diciembre 2012",
1569,
1617 
],
[
 "2013-01-01",
1544,
1579 
],
[
 "2013-02-01",
1432,
1569 
] 
];
data.addColumn('string','Date');
data.addColumn('number','Serie Original');
data.addColumn('number','Serie Ajustada');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartAreaChartID7c5e64f6746d() {
  var data = gvisDataAreaChartID7c5e64f6746d();
  var options = {};
options["allowHtml"] = true;
options["width"] =   1050;
options["height"] =    500;
options["colors"] = ['green', 'blue'];
options["focusTarget"] = "category";
options["legend.position"] = "none";
options["areaOpacity"] =      .1;
options["legend.position"] = "none";
options["hAxis"] = {
 "textPosition": "out",
 "showTextEvery" : 12
};
options["vAxis"] = {
  "title" : "Homicidios Dolosos por Mes",
 };

     var chart = new google.visualization.AreaChart(
       document.getElementById('AreaChartID7c5e64f6746d')
     );
     chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  var chartid = "corechart";

  // Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
  var i, newPackage = true;
  for (i = 0; newPackage && i < pkgs.length; i++) {
    if (pkgs[i] === chartid)
      newPackage = false;
  }
  if (newPackage)
    pkgs.push(chartid);

  // Add the drawChart function to the global list of callbacks
  callbacks.push(drawChartAreaChartID7c5e64f6746d);
})();
function displayChartAreaChartID7c5e64f6746d() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
    var pkgCount = pkgs.length;
    google.load("visualization", "1", { packages:pkgs, callback: function() {
      if (pkgCount != pkgs.length) {
        // Race condition where another setTimeout call snuck in after us; if
        // that call added a package, we must not shift its callback
        return;
      }
      while (callbacks.length > 0)
        callbacks.shift()();
    } });
  }, 100);
}
 
// jsFooter
 </script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartAreaChartID7c5e64f6746d"></script>
 
<!-- divChart -->
  
<div id="AreaChartID7c5e64f6746d"
  style="width: 1000px; height: 700px;">
</div>

<div class='source1'>
  Descarga: <a href=http://dl.dropbox.com/s/2c4e73poxyd9fof/SerieFinal.csv?token_hash=AAFWSoR4JIyqFR-Kf0CWVKpIAuN5sMgN9jjKBNtrS-HBRg&dl=1'>Base de Datos de Homicidios SESNSP (Ajustada por Estacionalidad) </a>
</div>

<div class='source4'>
<a rel="tooltip" data-original-title="El siguiente gráfico presenta la serie de tiempo de Averiguaciones Previas por Homicidio Doloso y la cifra ajustada por estacionalidad entre Diciembre 2006 y Marzo 2013.">Descripción</a>
</div>


---

## Serie Ajustada por Estacionalidad
# 1997-2013

<!-- AreaChart generated in R 2.15.3 by googleVis 0.4.2 package -->
<!-- Tue Apr  9 14:53:49 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataAreaChartID7cc2d60687d () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 "Diciembre 2006",
1021,
1031,
1031 
],
[
 "Enero 2007",
798,
803,
810 
],
[
 "Febrero 2007",
720,
774,
825 
],
[
 "Marzo 2007",
911,
886,
853 
],
[
 "Abril 2007",
912,
899,
876 
],
[
 "Mayo 2007",
1010,
934,
879 
],
[
 "Junio 2007",
894,
862,
859 
],
[
 "Julio 2007",
795,
798,
838 
],
[
 "Agosto 2007",
795,
803,
835 
],
[
 "Septiembre 2007",
830,
853,
849 
],
[
 "Octubre 2007",
865,
862,
867 
],
[
 "Noviembre 2007",
885,
911,
882 
],
[
 "Diciembre 2007",
838,
851,
897 
],
[
 "Enero 2008",
932,
941,
919 
],
[
 "Febrero 2008",
866,
935,
942 
],
[
 "Marzo 2008",
987,
965,
965 
],
[
 "Abril 2008",
961,
951,
996 
],
[
 "Mayo 2008",
1159,
1071,
1038 
],
[
 "Junio 2008",
1118,
1073,
1079 
],
[
 "Julio 2008",
1154,
1152,
1112 
],
[
 "Agosto 2008",
1120,
1121,
1135 
],
[
 "Septiembre 2008",
1074,
1099,
1168 
],
[
 "Octubre 2008",
1275,
1269,
1221 
],
[
 "Noviembre 2008",
1330,
1375,
1253 
],
[
 "Diciembre 2008",
1179,
1202,
1248 
],
[
 "Enero 2009",
1184,
1198,
1248 
],
[
 "Febrero 2009",
1266,
1372,
1253 
],
[
 "Marzo 2009",
1193,
1172,
1240 
],
[
 "Abril 2009",
1232,
1222,
1234 
],
[
 "Mayo 2009",
1268,
1172,
1257 
],
[
 "Junio 2009",
1400,
1340,
1306 
],
[
 "Julio 2009",
1375,
1366,
1360 
],
[
 "Agosto 2009",
1439,
1427,
1404 
],
[
 "Septiembre 2009",
1478,
1507,
1428 
],
[
 "Octubre 2009",
1358,
1352,
1437 
],
[
 "Noviembre 2009",
1349,
1406,
1472 
],
[
 "Diciembre 2009",
1576,
1612,
1532 
],
[
 "Enero 2010",
1610,
1632,
1569 
],
[
 "Febrero 2010",
1368,
1489,
1590 
],
[
 "Marzo 2010",
1674,
1649,
1632 
],
[
 "Abril 2010",
1715,
1699,
1684 
],
[
 "Mayo 2010",
1883,
1735,
1728 
],
[
 "Junio 2010",
1878,
1791,
1764 
],
[
 "Julio 2010",
1817,
1798,
1787 
],
[
 "Agosto 2010",
1875,
1846,
1793 
],
[
 "Septiembre 2010",
1689,
1716,
1792 
],
[
 "Octubre 2010",
1947,
1938,
1784 
],
[
 "Noviembre 2010",
1546,
1622,
1763 
],
[
 "Diciembre 2010",
1679,
1725,
1772 
],
[
 "Enero 2011",
1850,
1882,
1809 
],
[
 "Febrero 2011",
1661,
1815,
1834 
],
[
 "Marzo 2011",
1875,
1850,
1853 
],
[
 "Abril 2011",
1882,
1864,
1878 
],
[
 "Mayo 2011",
2101,
1931,
1902 
],
[
 "Junio 2011",
2027,
1930,
1916 
],
[
 "Julio 2011",
1971,
1946,
1915 
],
[
 "Agosto 2011",
1964,
1922,
1897 
],
[
 "Septiembre 2011",
1809,
1831,
1873 
],
[
 "Octubre 2011",
1904,
1897,
1850 
],
[
 "Noviembre 2011",
1739,
1830,
1817 
],
[
 "Diciembre 2011",
1697,
1748,
1777 
],
[
 "Enero 2012",
1657,
1691,
1754 
],
[
 "Febrero 2012",
1621,
1775,
1752 
],
[
 "Marzo 2012",
1762,
1741,
1754 
],
[
 "Abril 2012",
1783,
1766,
1755 
],
[
 "Mayo 2012",
1938,
1779,
1749 
],
[
 "Junio 2012",
1787,
1702,
1737 
],
[
 "Julio 2012",
1727,
1704,
1736 
],
[
 "Agosto 2012",
1851,
1805,
1740 
],
[
 "Septiembre 2012",
1812,
1827,
1710 
],
[
 "Octubre 2012",
1549,
1547,
1652 
],
[
 "Noviembre 2012",
1512,
1593,
1616 
],
[
 "Diciembre 2012",
1569,
1617,
1603 
],
[
 "Enero 2013",
1544,
1579,
1591 
],
[
 "Febrero 2013",
1425,
1562,
1584 
] 
];
data.addColumn('string','Date');
data.addColumn('number','Serie Original');
data.addColumn('number','Serie Ajustada');
data.addColumn('number','Serie Tendencial');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartAreaChartID7cc2d60687d() {
  var data = gvisDataAreaChartID7cc2d60687d();
  var options = {};
options["allowHtml"] = true;
options["width"] =   1050;
options["height"] =    500;
options["colors"] = ['green', 'blue', 'red'];
options["focusTarget"] = "category";
options["legend.position"] = "none";
options["hAxis"] = {
 "textPosition": "out",
  "showTextEvery" : 12,
 };
options["vAxis"] = {
  "title" : "Homicidios Dolosos por Mes",
 };

     var chart = new google.visualization.AreaChart(
       document.getElementById('AreaChartID7cc2d60687d')
     );
     chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  var chartid = "corechart";

  // Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
  var i, newPackage = true;
  for (i = 0; newPackage && i < pkgs.length; i++) {
    if (pkgs[i] === chartid)
      newPackage = false;
  }
  if (newPackage)
    pkgs.push(chartid);

  // Add the drawChart function to the global list of callbacks
  callbacks.push(drawChartAreaChartID7cc2d60687d);
})();
function displayChartAreaChartID7cc2d60687d() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
    var pkgCount = pkgs.length;
    google.load("visualization", "1", { packages:pkgs, callback: function() {
      if (pkgCount != pkgs.length) {
        // Race condition where another setTimeout call snuck in after us; if
        // that call added a package, we must not shift its callback
        return;
      }
      while (callbacks.length > 0)
        callbacks.shift()();
    } });
  }, 100);
}
 
// jsFooter
 </script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartAreaChartID7cc2d60687d"></script>
 
<!-- divChart -->
  
<div id="AreaChartID7cc2d60687d"
  style="width: 1000px; height: 700px;">
</div>


<div class='source1'>
  Descarga: <a href=http://dl.dropbox.com/s/2c4e73poxyd9fof/SerieFinal.csv?token_hash=AAFWSoR4JIyqFR-Kf0CWVKpIAuN5sMgN9jjKBNtrS-HBRg&dl=1'>Base de Datos de Homicidios SESNSP (Ajustada por Estacionalidad) </a>
</div>

<div class='source4'>
<a rel="tooltip" data-original-title="El siguiente gráfico presenta la serie de tiempo de Averiguaciones Previas por Homicidio Doloso, la cifra ajustada por estacionalidad y la evolución tendencial de la serie entre Diciembre 2006 y Marzo 2013.">Descripción</a>
</div>



---

## Escenarios 2013-2018

<iframe src="http://glimmer.rstudio.com/eduardoclark/homicidios/" height=400 width=1000 ></iframe>

<div class='source2'>
<a rel="tooltip" data-original-title="La siguiente calculadora proporciona el numero mensual de averiguaciones previas para Homicidios Dolosos que se tendria dada la reducción porcentual en el numero mensual de homicidios al llegar el final de presente sexenio. Adicionalmente se calcula el numero total de APs en el sexenio y la diferencia con respecto al sexenio 2006-2012. Esta calculadora asume una caida lineal constante ">Descripción</a>
</div>

<div class='source3'>
Si no puedes ver la calculadora, refresca tu explorador
</div>

---

## Si México fuera...



<!-- GeoChart generated in R 2.15.3 by googleVis 0.4.2 package -->
<!-- Fri Apr 19 11:45:48 2013 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataGeoChartID1a2b753b8e00 () {
  var data = new google.visualization.DataTable();
  var datajson =
[
 [
 " Honduras",
85412,
"Hubiéramos tenido 105,966 homicidios. 85,412 homicidios más que los ocurridos en 2012." 
],
[
 " El Salvador",
59499,
"Hubiéramos tenido  80,053 homicidios. 59,499 homicidios más que los ocurridos en 2012." 
],
[
 " Côte d'Ivoire",
45270,
"Hubiéramos tenido  65,824 homicidios. 45,270 homicidios más que los ocurridos en 2012." 
],
[
 " Jamaica",
39832,
"Hubiéramos tenido  60,386 homicidios. 39,832 homicidios más que los ocurridos en 2012." 
],
[
 " Venezuela",
31619,
"Hubiéramos tenido  52,173 homicidios. 31,619 homicidios más que los ocurridos en 2012." 
],
[
 " Belize",
27339,
"Hubiéramos tenido  47,893 homicidios. 27,339 homicidios más que los ocurridos en 2012." 
],
[
 " U.S. Virgin Islands",
24794,
"Hubiéramos tenido  45,348 homicidios. 24,794 homicidios más que los ocurridos en 2012." 
],
[
 " Guatemala",
23984,
"Hubiéramos tenido  44,538 homicidios. 23,984 homicidios más que los ocurridos en 2012." 
],
[
 " Saint Kitts and Nevis",
23637,
"Hubiéramos tenido  44,191 homicidios. 23,637 homicidios más que los ocurridos en 2012." 
],
[
 " Zambia",
23405,
"Hubiéramos tenido  43,959 homicidios. 23,405 homicidios más que los ocurridos en 2012." 
],
[
 " Uganda",
21439,
"Hubiéramos tenido  41,993 homicidios. 21,439 homicidios más que los ocurridos en 2012." 
],
[
 " Malawi",
21092,
"Hubiéramos tenido  41,646 homicidios. 21,092 homicidios más que los ocurridos en 2012." 
],
[
 " Lesotho",
20166,
"Hubiéramos tenido  40,720 homicidios. 20,166 homicidios más que los ocurridos en 2012." 
],
[
 " Trinidad and Tobago",
20166,
"Hubiéramos tenido  40,720 homicidios. 20,166 homicidios más que los ocurridos en 2012." 
],
[
 " South Africa",
16233,
"Hubiéramos tenido  36,787 homicidios. 16,233 homicidios más que los ocurridos en 2012." 
],
[
 " Colombia",
15770,
"Hubiéramos tenido  36,324 homicidios. 15,770 homicidios más que los ocurridos en 2012." 
],
[
 " Congo",
15076,
"Hubiéramos tenido  35,630 homicidios. 15,076 homicidios más que los ocurridos en 2012." 
],
[
 " Central African Republic",
13341,
"Hubiéramos tenido  33,895 homicidios. 13,341 homicidios más que los ocurridos en 2012." 
],
[
 " Bahamas",
11143,
"Hubiéramos tenido  31,697 homicidios. 11,143 homicidios más que los ocurridos en 2012." 
],
[
 " Puerto Rico",
9755,
"Hubiéramos tenido  30,309 homicidios.  9,755 homicidios más que los ocurridos en 2012." 
],
[
 " Saint Lucia",
8598,
"Hubiéramos tenido  29,152 homicidios.  8,598 homicidios más que los ocurridos en 2012." 
],
[
 " Dominican Republic",
8367,
"Hubiéramos tenido  28,921 homicidios.  8,367 homicidios más que los ocurridos en 2012." 
],
[
 " Tanzania",
7788,
"Hubiéramos tenido  28,342 homicidios.  7,788 homicidios más que los ocurridos en 2012." 
],
[
 " Sudan",
7441,
"Hubiéramos tenido  27,995 homicidios.  7,441 homicidios más que los ocurridos en 2012." 
],
[
 " Saint Vincent and the Grenadines",
5937,
"Hubiéramos tenido  26,491 homicidios.  5,937 homicidios más que los ocurridos en 2012." 
],
[
 " Mexico",
5706,
"Hubiéramos tenido  26,260 homicidios.  5,706 homicidios más que los ocurridos en 2012." 
],
[
 " Ethiopia",
5475,
"Hubiéramos tenido  26,029 homicidios.  5,475 homicidios más que los ocurridos en 2012." 
],
[
 " Guinea",
5475,
"Hubiéramos tenido  26,029 homicidios.  5,475 homicidios más que los ocurridos en 2012." 
],
[
 " Dominica",
5012,
"Hubiéramos tenido  25,566 homicidios.  5,012 homicidios más que los ocurridos en 2012." 
],
[
 " Burundi",
4549,
"Hubiéramos tenido  25,103 homicidios.  4,549 homicidios más que los ocurridos en 2012." 
],
[
 " Democratic Republic of the Congo",
4549,
"Hubiéramos tenido  25,103 homicidios.  4,549 homicidios más que los ocurridos en 2012." 
],
[
 " Panama",
4433,
"Hubiéramos tenido  24,987 homicidios.  4,433 homicidios más que los ocurridos en 2012." 
],
[
 " Brazil",
3739,
"Hubiéramos tenido  24,293 homicidios.  3,739 homicidios más que los ocurridos en 2012." 
],
[
 " Equatorial Guinea",
3392,
"Hubiéramos tenido  23,946 homicidios.  3,392 homicidios más que los ocurridos en 2012." 
],
[
 " Guinea-Bissau",
2814,
"Hubiéramos tenido  23,368 homicidios.  2,814 homicidios más que los ocurridos en 2012." 
],
[
 " Kenya",
2698,
"Hubiéramos tenido  23,252 homicidios.  2,698 homicidios más que los ocurridos en 2012." 
],
[
 " Kyrgyzstan",
2698,
"Hubiéramos tenido  23,252 homicidios.  2,698 homicidios más que los ocurridos en 2012." 
],
[
 " Cameroon",
2236,
"Hubiéramos tenido  22,790 homicidios.  2,236 homicidios más que los ocurridos en 2012." 
],
[
 " Montserrat",
2236,
"Hubiéramos tenido  22,790 homicidios.  2,236 homicidios más que los ocurridos en 2012." 
],
[
 " Greenland",
1657,
"Hubiéramos tenido  22,211 homicidios.  1,657 homicidios más que los ocurridos en 2012." 
],
[
 " Angola",
1426,
"Hubiéramos tenido  21,980 homicidios.  1,426 homicidios más que los ocurridos en 2012." 
],
[
 " Guyana",
963,
"Hubiéramos tenido  21,517 homicidios.    963 homicidios más que los ocurridos en 2012." 
],
[
 " Ecuador",
500,
"Hubiéramos tenido  21,054 homicidios.    500 homicidios más que los ocurridos en 2012." 
],
[
 " Burkina Faso",
269,
"Hubiéramos tenido  20,823 homicidios.    269 homicidios más que los ocurridos en 2012." 
],
[
 " Eritrea",
38,
"Hubiéramos tenido  20,592 homicidios.     38 homicidios más que los ocurridos en 2012." 
],
[
 " Namibia",
-657,
"Hubiéramos tenido  19,897 homicidios.    657 homicidios menos que los ocurridos en 2012." 
],
[
 " Rwanda",
-772,
"Hubiéramos tenido  19,782 homicidios.    772 homicidios menos que los ocurridos en 2012." 
],
[
 " Chad",
-2276,
"Hubiéramos tenido  18,278 homicidios.  2,276 homicidios menos que los ocurridos en 2012." 
],
[
 " Ghana",
-2392,
"Hubiéramos tenido  18,162 homicidios.  2,392 homicidios menos que los ocurridos en 2012." 
],
[
 " North Korea",
-2970,
"Hubiéramos tenido  17,584 homicidios.  2,970 homicidios menos que los ocurridos en 2012." 
],
[
 " Benin",
-3086,
"Hubiéramos tenido  17,468 homicidios.  3,086 homicidios menos que los ocurridos en 2012." 
],
[
 " Sierra Leone",
-3317,
"Hubiéramos tenido  17,237 homicidios.  3,317 homicidios menos que los ocurridos en 2012." 
],
[
 " Mauritania",
-3549,
"Hubiéramos tenido  17,005 homicidios.  3,549 homicidios menos que los ocurridos en 2012." 
],
[
 " Botswana",
-3780,
"Hubiéramos tenido  16,774 homicidios.  3,780 homicidios menos que los ocurridos en 2012." 
],
[
 " Zimbabwe",
-4011,
"Hubiéramos tenido  16,543 homicidios.  4,011 homicidios menos que los ocurridos en 2012." 
],
[
 " Gabon",
-4590,
"Hubiéramos tenido  15,964 homicidios.  4,590 homicidios menos que los ocurridos en 2012." 
],
[
 " Nicaragua",
-4821,
"Hubiéramos tenido  15,733 homicidios.  4,821 homicidios menos que los ocurridos en 2012." 
],
[
 " French Guiana",
-5168,
"Hubiéramos tenido  15,386 homicidios.  5,168 homicidios menos que los ocurridos en 2012." 
],
[
 " Papua New Guinea",
-5515,
"Hubiéramos tenido  15,039 homicidios.  5,515 homicidios menos que los ocurridos en 2012." 
],
[
 " Swaziland",
-5631,
"Hubiéramos tenido  14,923 homicidios.  5,631 homicidios menos que los ocurridos en 2012." 
],
[
 " Bermuda",
-6325,
"Hubiéramos tenido  14,229 homicidios.  6,325 homicidios menos que los ocurridos en 2012." 
],
[
 " Comoros",
-6441,
"Hubiéramos tenido  14,113 homicidios.  6,441 homicidios menos que los ocurridos en 2012." 
],
[
 " Nigeria",
-6441,
"Hubiéramos tenido  14,113 homicidios.  6,441 homicidios menos que los ocurridos en 2012." 
],
[
 " Cape Verde",
-7135,
"Hubiéramos tenido  13,419 homicidios.  7,135 homicidios menos que los ocurridos en 2012." 
],
[
 " Grenada",
-7250,
"Hubiéramos tenido  13,304 homicidios.  7,250 homicidios menos que los ocurridos en 2012." 
],
[
 " Paraguay",
-7250,
"Hubiéramos tenido  13,304 homicidios.  7,250 homicidios menos que los ocurridos en 2012." 
],
[
 " Barbados",
-7482,
"Hubiéramos tenido  13,072 homicidios.  7,482 homicidios menos que los ocurridos en 2012." 
],
[
 " Togo",
-7945,
"Hubiéramos tenido  12,609 homicidios.  7,945 homicidios menos que los ocurridos en 2012." 
],
[
 " Gambia",
-8060,
"Hubiéramos tenido  12,494 homicidios.  8,060 homicidios menos que los ocurridos en 2012." 
],
[
 " Peru",
-8639,
"Hubiéramos tenido  11,915 homicidios.  8,639 homicidios menos que los ocurridos en 2012." 
],
[
 " Myanmar",
-8754,
"Hubiéramos tenido  11,800 homicidios.  8,754 homicidios menos que los ocurridos en 2012." 
],
[
 " Russia",
-8754,
"Hubiéramos tenido  11,800 homicidios.  8,754 homicidios menos que los ocurridos en 2012." 
],
[
 " Liberia",
-8870,
"Hubiéramos tenido  11,684 homicidios.  8,870 homicidios menos que los ocurridos en 2012." 
],
[
 " Costa Rica",
-8986,
"Hubiéramos tenido  11,568 homicidios.  8,986 homicidios menos que los ocurridos en 2012." 
],
[
 " Nauru",
-9217,
"Hubiéramos tenido  11,337 homicidios.  9,217 homicidios menos que los ocurridos en 2012." 
],
[
 " Bolivia",
-10258,
"Hubiéramos tenido  10,296 homicidios. 10,258 homicidios menos que los ocurridos en 2012." 
],
[
 " Mozambique",
-10374,
"Hubiéramos tenido  10,180 homicidios. 10,374 homicidios menos que los ocurridos en 2012." 
],
[
 " Kazakhstan",
-10374,
"Hubiéramos tenido  10,180 homicidios. 10,374 homicidios menos que los ocurridos en 2012." 
],
[
 " Senegal",
-10490,
"Hubiéramos tenido  10,064 homicidios. 10,490 homicidios menos que los ocurridos en 2012." 
],
[
 " Turks and Caicos Islands",
-10490,
"Hubiéramos tenido  10,064 homicidios. 10,490 homicidios menos que los ocurridos en 2012." 
],
[
 " Mongolia",
-10490,
"Hubiéramos tenido  10,064 homicidios. 10,490 homicidios menos que los ocurridos en 2012." 
],
[
 " British Virgin Islands",
-10605,
"Hubiéramos tenido   9,949 homicidios. 10,605 homicidios menos que los ocurridos en 2012." 
],
[
 " Cayman Islands",
-10837,
"Hubiéramos tenido   9,717 homicidios. 10,837 homicidios menos que los ocurridos en 2012." 
],
[
 " Seychelles",
-10952,
"Hubiéramos tenido   9,602 homicidios. 10,952 homicidios menos que los ocurridos en 2012." 
],
[
 " Madagascar",
-11184,
"Hubiéramos tenido   9,370 homicidios. 11,184 homicidios menos que los ocurridos en 2012." 
],
[
 " Indonesia",
-11184,
"Hubiéramos tenido   9,370 homicidios. 11,184 homicidios menos que los ocurridos en 2012." 
],
[
 " Mali",
-11299,
"Hubiéramos tenido   9,255 homicidios. 11,299 homicidios menos que los ocurridos en 2012." 
],
[
 " Pakistan",
-11531,
"Hubiéramos tenido   9,023 homicidios. 11,531 homicidios menos que los ocurridos en 2012." 
],
[
 " Moldova",
-11878,
"Hubiéramos tenido   8,676 homicidios. 11,878 homicidios menos que los ocurridos en 2012." 
],
[
 " Kiribati",
-12109,
"Hubiéramos tenido   8,445 homicidios. 12,109 homicidios menos que los ocurridos en 2012." 
],
[
 " Guadeloupe",
-12456,
"Hubiéramos tenido   8,098 homicidios. 12,456 homicidios menos que los ocurridos en 2012." 
],
[
 " Haiti",
-12572,
"Hubiéramos tenido   7,982 homicidios. 12,572 homicidios menos que los ocurridos en 2012." 
],
[
 " Timor-Leste",
-12572,
"Hubiéramos tenido   7,982 homicidios. 12,572 homicidios menos que los ocurridos en 2012." 
],
[
 " Anguilla",
-12688,
"Hubiéramos tenido   7,866 homicidios. 12,688 homicidios menos que los ocurridos en 2012." 
],
[
 " Antigua and Barbuda",
-12688,
"Hubiéramos tenido   7,866 homicidios. 12,688 homicidios menos que los ocurridos en 2012." 
],
[
 " Lithuania",
-12919,
"Hubiéramos tenido   7,635 homicidios. 12,919 homicidios menos que los ocurridos en 2012." 
],
[
 " Uruguay",
-13729,
"Hubiéramos tenido   6,825 homicidios. 13,729 homicidios menos que los ocurridos en 2012." 
],
[
 " Argentina",
-13844,
"Hubiéramos tenido   6,710 homicidios. 13,844 homicidios menos que los ocurridos en 2012." 
],
[
 " Philippines",
-14307,
"Hubiéramos tenido   6,247 homicidios. 14,307 homicidios menos que los ocurridos en 2012." 
],
[
 " Ukraine",
-14538,
"Hubiéramos tenido   6,016 homicidios. 14,538 homicidios menos que los ocurridos en 2012." 
],
[
 " Estonia",
-14538,
"Hubiéramos tenido   6,016 homicidios. 14,538 homicidios menos que los ocurridos en 2012." 
],
[
 " Cuba",
-14770,
"Hubiéramos tenido   5,784 homicidios. 14,770 homicidios menos que los ocurridos en 2012." 
],
[
 " Belarus",
-14886,
"Hubiéramos tenido   5,668 homicidios. 14,886 homicidios menos que los ocurridos en 2012." 
],
[
 " United States",
-15001,
"Hubiéramos tenido   5,553 homicidios. 15,001 homicidios menos que los ocurridos en 2012." 
],
[
 " Thailand",
-15001,
"Hubiéramos tenido   5,553 homicidios. 15,001 homicidios menos que los ocurridos en 2012." 
],
[
 " Suriname",
-15233,
"Hubiéramos tenido   5,321 homicidios. 15,233 homicidios menos que los ocurridos en 2012." 
],
[
 " Laos",
-15233,
"Hubiéramos tenido   5,321 homicidios. 15,233 homicidios menos que los ocurridos en 2012." 
],
[
 " Georgia",
-15580,
"Hubiéramos tenido   4,974 homicidios. 15,580 homicidios menos que los ocurridos en 2012." 
],
[
 " Martinique",
-15695,
"Hubiéramos tenido   4,859 homicidios. 15,695 homicidios menos que los ocurridos en 2012." 
],
[
 " Turkmenistan",
-15695,
"Hubiéramos tenido   4,859 homicidios. 15,695 homicidios menos que los ocurridos en 2012." 
],
[
 " Yemen",
-15695,
"Hubiéramos tenido   4,859 homicidios. 15,695 homicidios menos que los ocurridos en 2012." 
],
[
 " Palestine",
-15811,
"Hubiéramos tenido   4,743 homicidios. 15,811 homicidios menos que los ocurridos en 2012." 
],
[
 " Albania",
-15927,
"Hubiéramos tenido   4,627 homicidios. 15,927 homicidios menos que los ocurridos en 2012." 
],
[
 " Niger",
-16158,
"Hubiéramos tenido   4,396 homicidios. 16,158 homicidios menos que los ocurridos en 2012." 
],
[
 " Solomon Islands",
-16274,
"Hubiéramos tenido   4,280 homicidios. 16,274 homicidios menos que los ocurridos en 2012." 
],
[
 " Sri Lanka",
-16389,
"Hubiéramos tenido   4,165 homicidios. 16,389 homicidios menos que los ocurridos en 2012." 
],
[
 " India",
-16505,
"Hubiéramos tenido   4,049 homicidios. 16,505 homicidios menos que los ocurridos en 2012." 
],
[
 " Montenegro",
-16505,
"Hubiéramos tenido   4,049 homicidios. 16,505 homicidios menos que los ocurridos en 2012." 
],
[
 " Djibouti",
-16621,
"Hubiéramos tenido   3,933 homicidios. 16,621 homicidios menos que los ocurridos en 2012." 
],
[
 " Cambodia",
-16621,
"Hubiéramos tenido   3,933 homicidios. 16,621 homicidios menos que los ocurridos en 2012." 
],
[
 " Turkey",
-16736,
"Hubiéramos tenido   3,818 homicidios. 16,736 homicidios menos que los ocurridos en 2012." 
],
[
 " Chile",
-16852,
"Hubiéramos tenido   3,702 homicidios. 16,852 homicidios menos que los ocurridos en 2012." 
],
[
 " Taiwan",
-16852,
"Hubiéramos tenido   3,702 homicidios. 16,852 homicidios menos que los ocurridos en 2012." 
],
[
 " Uzbekistan",
-16968,
"Hubiéramos tenido   3,586 homicidios. 16,968 homicidios menos que los ocurridos en 2012." 
],
[
 " Latvia",
-16968,
"Hubiéramos tenido   3,586 homicidios. 16,968 homicidios menos que los ocurridos en 2012." 
],
[
 " Iran",
-17084,
"Hubiéramos tenido   3,470 homicidios. 17,084 homicidios menos que los ocurridos en 2012." 
],
[
 " Libya",
-17199,
"Hubiéramos tenido   3,355 homicidios. 17,199 homicidios menos que los ocurridos en 2012." 
],
[
 " Nepal",
-17315,
"Hubiéramos tenido   3,239 homicidios. 17,315 homicidios menos que los ocurridos en 2012." 
],
[
 " Liechtenstein",
-17315,
"Hubiéramos tenido   3,239 homicidios. 17,315 homicidios menos que los ocurridos en 2012." 
],
[
 " Fiji",
-17315,
"Hubiéramos tenido   3,239 homicidios. 17,315 homicidios menos que los ocurridos en 2012." 
],
[
 " Bangladesh",
-17431,
"Hubiéramos tenido   3,123 homicidios. 17,431 homicidios menos que los ocurridos en 2012." 
],
[
 " South Korea",
-17546,
"Hubiéramos tenido   3,008 homicidios. 17,546 homicidios menos que los ocurridos en 2012." 
],
[
 " Mauritius",
-17662,
"Hubiéramos tenido   2,892 homicidios. 17,662 homicidios menos que los ocurridos en 2012." 
],
[
 " Luxembourg",
-17662,
"Hubiéramos tenido   2,892 homicidios. 17,662 homicidios menos que los ocurridos en 2012." 
],
[
 " Afghanistan",
-17778,
"Hubiéramos tenido   2,776 homicidios. 17,778 homicidios menos que los ocurridos en 2012." 
],
[
 " Malaysia",
-17893,
"Hubiéramos tenido   2,661 homicidios. 17,893 homicidios menos que los ocurridos en 2012." 
],
[
 " Syria",
-17893,
"Hubiéramos tenido   2,661 homicidios. 17,893 homicidios menos que los ocurridos en 2012." 
],
[
 " Azerbaijan",
-18009,
"Hubiéramos tenido   2,545 homicidios. 18,009 homicidios menos que los ocurridos en 2012." 
],
[
 " Kuwait",
-18009,
"Hubiéramos tenido   2,545 homicidios. 18,009 homicidios menos que los ocurridos en 2012." 
],
[
 " Lebanon",
-18009,
"Hubiéramos tenido   2,545 homicidios. 18,009 homicidios menos que los ocurridos en 2012." 
],
[
 " Finland",
-18009,
"Hubiéramos tenido   2,545 homicidios. 18,009 homicidios menos que los ocurridos en 2012." 
],
[
 " Tajikistan",
-18125,
"Hubiéramos tenido   2,429 homicidios. 18,125 homicidios menos que los ocurridos en 2012." 
],
[
 " Israel",
-18125,
"Hubiéramos tenido   2,429 homicidios. 18,125 homicidios menos que los ocurridos en 2012." 
],
[
 " Iraq",
-18240,
"Hubiéramos tenido   2,314 homicidios. 18,240 homicidios menos que los ocurridos en 2012." 
],
[
 " Bulgaria",
-18240,
"Hubiéramos tenido   2,314 homicidios. 18,240 homicidios menos que los ocurridos en 2012." 
],
[
 " Romania",
-18240,
"Hubiéramos tenido   2,314 homicidios. 18,240 homicidios menos que los ocurridos en 2012." 
],
[
 " São Tomé and Príncipe",
-18356,
"Hubiéramos tenido   2,198 homicidios. 18,356 homicidios menos que los ocurridos en 2012." 
],
[
 " Macedonia",
-18356,
"Hubiéramos tenido   2,198 homicidios. 18,356 homicidios menos que los ocurridos en 2012." 
],
[
 " Jordan",
-18472,
"Hubiéramos tenido   2,082 homicidios. 18,472 homicidios menos que los ocurridos en 2012." 
],
[
 " Cyprus",
-18587,
"Hubiéramos tenido   1,967 homicidios. 18,587 homicidios menos que los ocurridos en 2012." 
],
[
 " Czech Republic",
-18587,
"Hubiéramos tenido   1,967 homicidios. 18,587 homicidios menos que los ocurridos en 2012." 
],
[
 " Belgium",
-18587,
"Hubiéramos tenido   1,967 homicidios. 18,587 homicidios menos que los ocurridos en 2012." 
],
[
 " Canada",
-18703,
"Hubiéramos tenido   1,851 homicidios. 18,703 homicidios menos que los ocurridos en 2012." 
],
[
 " Vietnam",
-18703,
"Hubiéramos tenido   1,851 homicidios. 18,703 homicidios menos que los ocurridos en 2012." 
],
[
 " Maldives",
-18703,
"Hubiéramos tenido   1,851 homicidios. 18,703 homicidios menos que los ocurridos en 2012." 
],
[
 " Somalia",
-18819,
"Hubiéramos tenido   1,735 homicidios. 18,819 homicidios menos que los ocurridos en 2012." 
],
[
 " Algeria",
-18819,
"Hubiéramos tenido   1,735 homicidios. 18,819 homicidios menos que los ocurridos en 2012." 
],
[
 " Slovakia",
-18819,
"Hubiéramos tenido   1,735 homicidios. 18,819 homicidios menos que los ocurridos en 2012." 
],
[
 " Bosnia and Herzegovina",
-18819,
"Hubiéramos tenido   1,735 homicidios. 18,819 homicidios menos que los ocurridos en 2012." 
],
[
 " Greece",
-18819,
"Hubiéramos tenido   1,735 homicidios. 18,819 homicidios menos que los ocurridos en 2012." 
],
[
 " Morocco",
-18934,
"Hubiéramos tenido   1,620 homicidios. 18,934 homicidios menos que los ocurridos en 2012." 
],
[
 " Armenia",
-18934,
"Hubiéramos tenido   1,620 homicidios. 18,934 homicidios menos que los ocurridos en 2012." 
],
[
 " Croatia",
-18934,
"Hubiéramos tenido   1,620 homicidios. 18,934 homicidios menos que los ocurridos en 2012." 
],
[
 " Hungary",
-19050,
"Hubiéramos tenido   1,504 homicidios. 19,050 homicidios menos que los ocurridos en 2012." 
],
[
 " Andorra",
-19050,
"Hubiéramos tenido   1,504 homicidios. 19,050 homicidios menos que los ocurridos en 2012." 
],
[
 " Egypt",
-19166,
"Hubiéramos tenido   1,388 homicidios. 19,166 homicidios menos que los ocurridos en 2012." 
],
[
 " Ireland",
-19166,
"Hubiéramos tenido   1,388 homicidios. 19,166 homicidios menos que los ocurridos en 2012." 
],
[
 " United Kingdom",
-19166,
"Hubiéramos tenido   1,388 homicidios. 19,166 homicidios menos que los ocurridos en 2012." 
],
[
 " Portugal",
-19166,
"Hubiéramos tenido   1,388 homicidios. 19,166 homicidios menos que los ocurridos en 2012." 
],
[
 " Serbia",
-19166,
"Hubiéramos tenido   1,388 homicidios. 19,166 homicidios menos que los ocurridos en 2012." 
],
[
 " Tunisia",
-19281,
"Hubiéramos tenido   1,273 homicidios. 19,281 homicidios menos que los ocurridos en 2012." 
],
[
 " Poland",
-19281,
"Hubiéramos tenido   1,273 homicidios. 19,281 homicidios menos que los ocurridos en 2012." 
],
[
 " France",
-19281,
"Hubiéramos tenido   1,273 homicidios. 19,281 homicidios menos que los ocurridos en 2012." 
],
[
 " Netherlands",
-19281,
"Hubiéramos tenido   1,273 homicidios. 19,281 homicidios menos que los ocurridos en 2012." 
],
[
 " Samoa",
-19281,
"Hubiéramos tenido   1,273 homicidios. 19,281 homicidios menos que los ocurridos en 2012." 
],
[
 " China",
-19397,
"Hubiéramos tenido   1,157 homicidios. 19,397 homicidios menos que los ocurridos en 2012." 
],
[
 " Bhutan",
-19397,
"Hubiéramos tenido   1,157 homicidios. 19,397 homicidios menos que los ocurridos en 2012." 
],
[
 " Saudi Arabia",
-19397,
"Hubiéramos tenido   1,157 homicidios. 19,397 homicidios menos que los ocurridos en 2012." 
],
[
 " Sweden",
-19397,
"Hubiéramos tenido   1,157 homicidios. 19,397 homicidios menos que los ocurridos en 2012." 
],
[
 " Malta",
-19397,
"Hubiéramos tenido   1,157 homicidios. 19,397 homicidios menos que los ocurridos en 2012." 
],
[
 " Australia",
-19397,
"Hubiéramos tenido   1,157 homicidios. 19,397 homicidios menos que los ocurridos en 2012." 
],
[
 " Tonga",
-19397,
"Hubiéramos tenido   1,157 homicidios. 19,397 homicidios menos que los ocurridos en 2012." 
],
[
 " Qatar",
-19513,
"Hubiéramos tenido   1,041 homicidios. 19,513 homicidios menos que los ocurridos en 2012." 
],
[
 " Denmark",
-19513,
"Hubiéramos tenido   1,041 homicidios. 19,513 homicidios menos que los ocurridos en 2012." 
],
[
 " Italy",
-19513,
"Hubiéramos tenido   1,041 homicidios. 19,513 homicidios menos que los ocurridos en 2012." 
],
[
 " New Zealand",
-19513,
"Hubiéramos tenido   1,041 homicidios. 19,513 homicidios menos que los ocurridos en 2012." 
],
[
 " Vanuatu",
-19513,
"Hubiéramos tenido   1,041 homicidios. 19,513 homicidios menos que los ocurridos en 2012." 
],
[
 " Federated States of Micronesia",
-19513,
"Hubiéramos tenido   1,041 homicidios. 19,513 homicidios menos que los ocurridos en 2012." 
],
[
 " United Arab Emirates",
-19629,
"Hubiéramos tenido     925 homicidios. 19,629 homicidios menos que los ocurridos en 2012." 
],
[
 " Spain",
-19629,
"Hubiéramos tenido     925 homicidios. 19,629 homicidios menos que los ocurridos en 2012." 
],
[
 " Germany",
-19629,
"Hubiéramos tenido     925 homicidios. 19,629 homicidios menos que los ocurridos en 2012." 
],
[
 " Macau",
-19744,
"Hubiéramos tenido     810 homicidios. 19,744 homicidios menos que los ocurridos en 2012." 
],
[
 " Oman",
-19744,
"Hubiéramos tenido     810 homicidios. 19,744 homicidios menos que los ocurridos en 2012." 
],
[
 " Slovenia",
-19744,
"Hubiéramos tenido     810 homicidios. 19,744 homicidios menos que los ocurridos en 2012." 
],
[
 " Switzerland",
-19744,
"Hubiéramos tenido     810 homicidios. 19,744 homicidios menos que los ocurridos en 2012." 
],
[
 " Bahrain",
-19860,
"Hubiéramos tenido     694 homicidios. 19,860 homicidios menos que los ocurridos en 2012." 
],
[
 " Norway",
-19860,
"Hubiéramos tenido     694 homicidios. 19,860 homicidios menos que los ocurridos en 2012." 
],
[
 " Austria",
-19860,
"Hubiéramos tenido     694 homicidios. 19,860 homicidios menos que los ocurridos en 2012." 
],
[
 " Guam",
-19860,
"Hubiéramos tenido     694 homicidios. 19,860 homicidios menos que los ocurridos en 2012." 
],
[
 " Brunei",
-19976,
"Hubiéramos tenido     578 homicidios. 19,976 homicidios menos que los ocurridos en 2012." 
],
[
 " Japan",
-20091,
"Hubiéramos tenido     463 homicidios. 20,091 homicidios menos que los ocurridos en 2012." 
],
[
 " French Polynesia",
-20091,
"Hubiéramos tenido     463 homicidios. 20,091 homicidios menos que los ocurridos en 2012." 
],
[
 " Singapore",
-20207,
"Hubiéramos tenido     347 homicidios. 20,207 homicidios menos que los ocurridos en 2012." 
],
[
 " Iceland",
-20207,
"Hubiéramos tenido     347 homicidios. 20,207 homicidios menos que los ocurridos en 2012." 
],
[
 " Hong Kong",
-20323,
"Hubiéramos tenido     231 homicidios. 20,323 homicidios menos que los ocurridos en 2012." 
],
[
 " Monaco",
-20554,
"Hubiéramos tenido       0 homicidios. 20,554 homicidios menos que los ocurridos en 2012." 
],
[
 " Palau",
-20554,
"Hubiéramos tenido       0 homicidios. 20,554 homicidios menos que los ocurridos en 2012." 
] 
];
data.addColumn('string','country');
data.addColumn('number','Hubieramos tenido');
data.addColumn({
    type: 'string',
    role: 'tooltip'
});
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartGeoChartID1a2b753b8e00() {
  var data = gvisDataGeoChartID1a2b753b8e00();
  var options = {};
options["width"] =   1000;
options["height"] =    500;
options["colorAxis"] = {minValue: -20000, maxValue: 20000 ,  colors: ['royalblue' ,'white', 'red']};
options["legend"] = {numberFormat: "###,###'"};

     var chart = new google.visualization.GeoChart(
       document.getElementById('GeoChartID1a2b753b8e00')
     );
     chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  var chartid = "geochart";

  // Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
  var i, newPackage = true;
  for (i = 0; newPackage && i < pkgs.length; i++) {
    if (pkgs[i] === chartid)
      newPackage = false;
  }
  if (newPackage)
    pkgs.push(chartid);

  // Add the drawChart function to the global list of callbacks
  callbacks.push(drawChartGeoChartID1a2b753b8e00);
})();
function displayChartGeoChartID1a2b753b8e00() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
    var pkgCount = pkgs.length;
    google.load("visualization", "1", { packages:pkgs, callback: function() {
      if (pkgCount != pkgs.length) {
        // Race condition where another setTimeout call snuck in after us; if
        // that call added a package, we must not shift its callback
        return;
      }
      while (callbacks.length > 0)
        callbacks.shift()();
    } });
  }, 100);
}
 
// jsFooter
 </script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartGeoChartID1a2b753b8e00"></script>
 
<!-- divChart -->
  
<div id="GeoChartID1a2b753b8e00"
  style="width: 1000px; height: 1000px;">
</div>

<div class='source4'>
<a rel="tooltip" data-original-title="El siguiente gráfico presenta el numero de homicidios que hubieran ocurrido en México en 2012 si se tuviera la tasa de homicidios del país seleccionado. <br> Adicionalmente se incluye la diferencia en el numero de homicidios en 2012 y los que se hubieran tenido bajo la tasa del país seleccionado.">Descripción</a>
</div>


---

## Contacto

<div class='Titulo1'>
  Alejandro Hope 
</div>

<div class='Titulo'>
  Director de Seguridad  
</div>

<div class='Titulo2'>
  Instituto Mexicano para la Competitividad A.C.
  </div>

<div class='Titulo3'>
  alejandro.hope@imco.org.mx
</div>

<div class='Titulo4'>
  5985-1017 ext. 100
</div>

<div class='Titulo5'>
  @ahope71
</div>

<div class='Titulo6'>
  Eduardo Clark
</div>

<div class='Titulo7'>
  Investigador
</div>

<div class='Titulo8'>
  Instituto Mexicano para la Competitividad A.C.
</div>

<div class='Titulo9'>
  eduardo.clark@imco.org.mx
</div>

<div class='Titulo10'>
  @EduardoClark <br>
</div>

