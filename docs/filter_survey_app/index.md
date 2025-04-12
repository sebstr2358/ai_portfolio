<header style="margin-bottom: 1rem">
    <h1 style="margin-bottom: 0">Interaktywna analiza danych z ankiety</h1>
    <p>Zapraszam do zapoznania się z projektem interaktywnej analizy danych
    dotyczących uczestników kursu tworzenia sztucznej inteligencji. Ankieta pozwoli sprawdzić, czy istnieje cecha, która charakteryzuje wszystkich uczestników kursu, czy może jednak prowadzącym udało się zgromadzić zupełnie różnych ludzi.
    Kliknij w link poniżej i sprawdź!</p>
</header>

<a href="https://filtersurveyapp.streamlit.app/" style="margin-bottom: 2rem" class="md-button md-button--primary" target='_blank'>FilterSurvey</a>

<h3>Spoilery do wyników ankiety</h3>
<div style="display: flex'">
    <div style="
            background-color: #f8f9fa;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 0 16px 16px 16px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            max-width: 300px;
            margin: 20px auto;">
        <h2>Wiek</h2>
        <button id="show-button-age" class="md-button md-button--primary" onclick="toggleVisibilityAge()">Pokaż spoiler</button>
        <button id="hide-button-age" class="md-button md-button--primary" style="display: none;" onclick="toggleVisibilityAge()">Ukryj spoiler</button>
        <div id="hidden-text-age" style="display: none; margin-top: 10px;">
            <p>Najstarsza osoba ma powyżej 65 lat!</p>
        </div>
    </div>
    <div style="
                background-color: #f8f9fa;
                display: flex;
                flex-direction: column;
                justify-content: center;
                align-items: center;
                border: 1px solid #ddd;
                border-radius: 8px;
                padding: 0 16px 16px 16px;
                box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
                max-width: 300px;
                margin: 20px auto;">
        <h2>Płeć</h2>
        <button id="show-button-gender" class="md-button md-button--primary" onclick="toggleVisibilityGender()">Pokaż spoiler</button>
        <button id="hide-button-gender" class="md-button md-button--primary" style="display: none;" onclick="toggleVisibilityGender()">Ukryj spoiler</button>
        <div id="hidden-text-gender" style="display: none; margin-top: 10px;">
            <p>Kobiety stanowią zaledwie ok. 23% ankietowanych!</p>
        </div>
    </div>
    <div style="
                background-color: #f8f9fa;
                display: flex;
                flex-direction: column;
                justify-content: center;
                align-items: center;
                border: 1px solid #ddd;
                border-radius: 8px;
                padding: 0 16px 16px 16px;
                box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
                max-width: 300px;
                margin: 20px auto;">
        <h2>Ulubione zwierze</h2>
        <button id="show-button-animal" class="md-button md-button--primary" onclick="toggleVisibilityAnimal()">Pokaż spoiler</button>
        <button id="hide-button-animal" class="md-button md-button--primary" style="display: none;" onclick="toggleVisibilityAnimal()">Ukryj spoiler</button>
        <div id="hidden-text-animal" style="display: none; margin-top: 10px;">
            <p>Zdecydowanie psy!</p>
        </div>
    </div>
</div>
<script>
function toggleVisibilityAge() {

    var hiddenTextAge = document.getElementById("hidden-text-age");
    var showButtonAge = document.getElementById("show-button-age");
    var hideButtonAge = document.getElementById("hide-button-age");

    if (hiddenTextAge.style.display === "none") {
        hiddenTextAge.style.display = "block";
        showButtonAge.style.display = "none";
        hideButtonAge.style.display = "inline";
    } else {
        hiddenTextAge.style.display = "none";
        showButtonAge.style.display = "inline";
        hideButtonAge.style.display = "none";
    }
}
function toggleVisibilityGender() {

    var hiddenTextGender = document.getElementById("hidden-text-gender");
    var showButtonGender = document.getElementById("show-button-gender");
    var hideButtonGender = document.getElementById("hide-button-gender");

    if (hiddenTextGender.style.display === "none") {
        hiddenTextGender.style.display = "block";
        showButtonGender.style.display = "none";
        hideButtonGender.style.display = "inline";
    } else {
        hiddenTextGender.style.display = "none";
        showButtonGender.style.display = "inline";
        hideButtonGender.style.display = "none";
    }
}
function toggleVisibilityAnimal() {

    var hiddenTextAnimal = document.getElementById("hidden-text-animal");
    var showButtonAnimal = document.getElementById("show-button-animal");
    var hideButtonAnimal = document.getElementById("hide-button-animal");

    if (hiddenTextAnimal.style.display === "none") {
        hiddenTextAnimal.style.display = "block";
        showButtonAnimal.style.display = "none";
        hideButtonAnimal.style.display = "inline";
    } else {
        hiddenTextAnimal.style.display = "none";
        showButtonAnimal.style.display = "inline";
        hideButtonAnimal.style.display = "none";
    }
}
</script>



