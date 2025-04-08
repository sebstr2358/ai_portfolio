# Interaktywna analiza danych z ankiety

Zapraszam do zapoznania się z projektem interaktywnej analizy danych
dotyczących uczestników kursu tworzenia sztucznej inteligencji. Ankieta pozwoli sprawdzić, czy istnieje cecha, która charakteryzuje wszystkich uczestników kursu, czy może jednak prowadzącym udało się zgromadzić zupełnie różnych ludzi.
Kliknij w link poniżej i sprawdź!


<a href="https://filtersurveyapp.streamlit.app/" class="md-button md-button--primary" target='_blank'>FilterSurvey</a>

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