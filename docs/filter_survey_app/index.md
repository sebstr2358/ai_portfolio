<header style="margin-bottom: 2rem">
    <h1 style="margin-bottom: 0">Interaktywna analiza danych z ankiety</h1>
    <p>Zapraszam do zapoznania się z projektem interaktywnej analizy danych
    dotyczących uczestników kursu tworzenia sztucznej inteligencji. Ankieta pozwoli sprawdzić, czy istnieje cecha, która charakteryzuje wszystkich uczestników kursu, czy może jednak prowadzącym udało się zgromadzić zupełnie różnych ludzi.
    Kliknij w link poniżej i sprawdź!</p>
</header>


<a href="https://filtersurveyapp.streamlit.app/" class="md-button md-button--primary" target='_blank'>FilterSurvey</a>

<p>Mały spojler o ankietowanych:</p>

<h2>Wiek (1)!</h2>
<button onclick="toggleVisibility()">Pokaż informację</button>

<div id="hidden-text" style="display: none; margin-top: 10px;">
    <p>1. Najstarsza osoba powyżej 65 lat!</p>
</div>

<script>
function toggleVisibility() {
    var x = document.getElementById("hidden-text");
    if (x.style.display === "none") {
        x.style.display = "block";
    } else {
        x.style.display = "none";
    }
}
</script>



