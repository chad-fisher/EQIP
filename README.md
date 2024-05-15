<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Basic Embedding via Web Component</title>
    <script type="module" src='https://public.tableau.com/javascripts/api/tableau.embedding.3.latest.js'></script>
</head>

<body>
    <div style="width:800px; height:700px;">
        <tableau-viz id="tableauViz" src="https://public.tableau.com/views/RegionalSampleWorkbook/Storms"
            toolbar="bottom" hide-tabs>
        </tableau-viz>
    </div>
</body>
</html>
