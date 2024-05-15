<script type="module">
    import { TableauViz } from "https://public.tableau.com/javascripts/api/tableau.embedding.3.latest.js";
    const viz = new TableauViz();
    viz.src = "https://public.tableau.com/views/EQIPVisuals/EQIP2014-2023";
    viz.toolbar = "hidden";
    document.getElementById("tableauViz").appendChild(viz);
</script>
