<script src="https://public.tableau.com/javascripts/api/tableau-2.js"></script>
<div id="tableauViz"></div>
function initializeViz() {
  var placeholderDiv = document.getElementById("tableauViz");
  var url = ["http://public.tableau.com/views/WorldIndicators/GDPpercapita"](https://public.tableau.com/app/profile/chad.fisher5536/viz/EQIPVisuals/EQIP2014-2023);
  var options = {
    width: '600px',
    height: '600px',
    hideTabs: true,
    hideToolbar: true,
  };
  viz = new tableau.Viz(placeholderDiv, url, options);
}
