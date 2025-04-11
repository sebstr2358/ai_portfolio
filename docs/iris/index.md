<header style="margin-bottom: 2rem">
    <h1 style="margin-bottom: 0">Analiza Danych EDA Irysów: Eksploracja Domenowa</h1>
    <p>Zapraszam do zapoznania się z projektem analizy. Projekt miał za zadanie
    zbadać podobieństwa i różnice 3 gatunków irysów i odpowiedzieć na 
    arcyważne pytanie - jak określić gatunek napotkanego irysa mając
    do dyspozycji jedynie metrówkę?
    Czy cel został zrealizowany? Sprawdź sam!</p>
</header>

<a href="iris.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="iris.html"
    width="100%"
    style="border:1px solid black;overflow:hidden;"
></iframe>
<script>
function resizeIframeToFitContent(iframe) {
    iframe.style.height = (iframe.contentWindow.document.documentElement.scrollHeight + 50) + "px";
    iframe.contentDocument.body.style["overflow"] = 'hidden';
}
window.addEventListener('load', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
window.addEventListener('resize', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
</script>