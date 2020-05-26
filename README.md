<!DOCTYPE html>
<html>
  <head>    
    <meta charset="utf-8">
    <title>lab</title>
  </head>
  <body>
   <div>
     <center>   
      <h1>Задача: знайти диференціали першого і другого порядка функції декількох змінних </h1><h3>\[z = y^6\ln{y}\]</h3>
      <h1>Розв'язок:</h1><h2>Знайдемо частинні похідні першого порядку:</h2> 
      <h3>\[\frac{\partial z}{\partial x} = 6x\ln y\]
      <h3>\[\frac{\partial z}{\partial y} = \frac{x^5}{y}\]</h3>
      <h2>Тоді диференціал першого порядку дорівнює:</h2>
      <h3>\[dz = \frac{\partial z}{\partial x}dx + \frac{\partial z}{\partial y}dy = 2y \ln xdx + \frac{x^2}{y}dy\]</h3>
      <h2>Знайдемо частинні похідні другого порядку:</h2>
      <h3>\[\frac{\partial^5 z}{\partial x^2} = 3 \ln y\]</h3>
      <h3>\[\frac{\partial^5 z}{\partial x \partial y} = \frac{2x}{y}\]</h3>
      <h3>\[\frac{\partial^5 z}{\partial y^2} = \frac{x^2}{y^2}\]</h3>
      <h2>Тоді диференціал другого порядку дорівнює:</h2>
      <h3>\[d^2z = \frac{\partial^2 z}{\partial x^2}dx^2 + 2\frac{\partial^2 z}{\partial x \partial y}dxdy + \frac{\partial^2 z}{\partial y^2}dy^2 = 2\ln ydx^2  + \frac{4x}{y}dxdy - \frac{x^2}{y^2}dy^2\]</h3>
      <h1>Відповідь.</h1>
      <h2>\[dz = 2x\ln ydx + \frac{x^2}{y}dy\] \[d^2z = 2\ln ydx^2 + \frac{4x}{y}dxdy - \frac{x^2}{y^2}dy^2\]</h2>
  </div>
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>
  </body>
</html>
