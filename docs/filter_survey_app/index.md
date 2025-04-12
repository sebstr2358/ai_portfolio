<header style="margin-bottom: 2rem">
    <h1 style="margin-bottom: 0">Interaktywna analiza danych z ankiety</h1>
    <p>Zapraszam do zapoznania się z projektem interaktywnej analizy danych
    dotyczących uczestników kursu tworzenia sztucznej inteligencji. Ankieta pozwoli sprawdzić, czy istnieje cecha, która charakteryzuje wszystkich uczestników kursu, czy może jednak prowadzącym udało się zgromadzić zupełnie różnych ludzi.
    Kliknij w link poniżej i sprawdź!</p>
</header>


<a href="https://filtersurveyapp.streamlit.app/" class="md-button md-button--primary" target='_blank'>FilterSurvey</a>

<p>Mały spojler o ankietowanych:</p>

<div style="
            display: flex;
            flex-direction: column;
            justify-content: center;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 16px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            max-width: 300px;
            margin: 20px auto;">
    <h2>Wiek</h2>
    <button class="md-button md-button--primary" onclick="toggleVisibility()">Pokaż informację </button>
    <div id="hidden-text" style="display: none; margin-top: 10px;">
    <p>Najstarsza osoba powyżej 65 lat!</p>
</div>
</div>
<h2>Wiek</h2>
<button id="visible-text" onclick="toggleVisibility()">Pokaż informację</button>
<div id="hidden-text" style="display: none; margin-top: 10px;">
    <p>Najstarsza osoba powyżej 65 lat!</p>
</div>

<script>
function toggleVisibility() {
    var x = document.getElementById("hidden-text");
    var y = document.getElementById("visible-text");
    if (x.style.display === "none") {
        x.style.display = "block";
        y.style.display = "none";
    } else {
        x.style.display = "none";
         
    }
}
</script>



