<header style="margin-bottom: 2rem">
    <h1 style="margin-bottom: 0">Analiza Danych EDA ofert z justjoinit</h1>
    <p>Analiza dotyczy pasażerów rejsu z 1912r. Dla części z nich
    była to ostatnia przygoda życia, dla innych zaś, większych 
    szczęściarzy, jedynie kolejna lekcja. Czy na pewno o przetrwaniu
    zadecydował jedynie łut szczęścia, czy może można było temu
    szczęściu w sposób świadomy pomóc? Czy którykolwiek pasażer miał
    pewność przeżycia?
    Na te i inne pytania postaram się
    odpowiedzieć w oparciu o załączone dane.
    Zapraszam do analizy!</p>
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