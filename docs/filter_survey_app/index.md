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
            height: 100%;
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
<button id="show-button" onclick="toggleVisibility()">Pokaż informację</button>
<button id="hide-button" style="display: none;" onclick="toggleVisibility()">Ukryj informację</button>

<div id="hidden-text" style="display: none; margin-top: 10px;">
    <p>Najstarsza osoba powyżej 65 lat!</p>
</div>

<script>
function toggleVisibility() {
    var hiddenText = document.getElementById("hidden-text");
    var showButton = document.getElementById("show-button");
    var hideButton = document.getElementById("hide-button");

    if (hiddenText.style.display === "none") {
        hiddenText.style.display = "block";
        showButton.style.display = "none";
        hideButton.style.display = "inline";
    } else {
        hiddenText.style.display = "none";
        showButton.style.display = "inline";
        hideButton.style.display = "none";
    }
}
</script>



