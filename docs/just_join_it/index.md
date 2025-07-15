<header style="margin-bottom: 2rem">
    <h1 style="margin-bottom: 0">Analiza Danych EDA ofert z justjoinit</h1>
    <p>Analiza dotyczy ofert pracy publikowanych na platformie Just Join IT w okresie od września 2021r. do września 2023r. Głowny jej cel to identyfikacjia trendów w zatrudnieniu w branży IT i porównanie ich z trendami obecnymi. Jeśli interesują Cię zmiany w wymaganych przez pracodawców umiejętnościach, poziomie doświadczenia oraz oferowanych widełkach płacowych, to zapraszam to poniższej prezentacji.</p>
</header>

<a href="eda_old_data_justjoinit.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="eda_old_data_justjoinit.html"
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
