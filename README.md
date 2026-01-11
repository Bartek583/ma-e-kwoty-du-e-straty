# ma-e-kwoty-du-e-straty[małe_kwoty_duże_straty.html](https://github.com/user-attachments/files/24552156/male_kwoty_duze_straty.html)
<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <title>Małe kwoty – duże straty</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        :root {
            --primary: #2c3e50;
            --secondary: #27ae60;
            --accent: #e74c3c;
            --light: #f4f6f7;
            --dark: #1c2833;
        }

        body {
            margin: 0;
            font-family: "Segoe UI", Tahoma, sans-serif;
            background-color: var(--light);
            color: #333;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(135deg, var(--primary), var(--dark));
            color: white;
            padding: 60px 20px;
            text-align: center;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2rem;
            max-width: 800px;
            margin: auto;
        }

        section {
            padding: 60px 20px;
            max-width: 1100px;
            margin: auto;
        }

        h2 {
            color: var(--primary);
            margin-bottom: 20px;
            font-size: 2rem;
        }

        .cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .card {
            background: white;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.08);
            transition: transform 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card h3 {
            color: var(--secondary);
        }

        .highlight {
            background-color: white;
            border-left: 8px solid var(--accent);
            padding: 20px;
            margin: 30px 0;
            border-radius: 8px;
        }

        .calculator {
            background: var(--primary);
            color: white;
            padding: 40px;
            border-radius: 15px;
        }

        .calculator input {
            width: 100%;
            padding: 12px;
            font-size: 1rem;
            margin: 10px 0 20px 0;
            border-radius: 8px;
            border: none;
        }

        .calculator button {
            background: var(--secondary);
            color: white;
            border: none;
            padding: 15px;
            font-size: 1rem;
            border-radius: 8px;
            cursor: pointer;
        }

        .calculator button:hover {
            background: #219150;
        }

        .result {
            margin-top: 20px;
            font-size: 1.2rem;
        }

        footer {
            background: var(--dark);
            color: white;
            text-align: center;
            padding: 30px 20px;
            margin-top: 60px;
        }

        footer p {
            margin: 5px 0;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

<header>
    <h1>Małe kwoty – duże straty</h1>
    <p>
        Codzienne drobne wydatki często wydają się nieistotne.
        Jednak z czasem potrafią zamienić się w ogromne sumy,
        które mogłyby zostać przeznaczone na ważniejsze cele.
    </p>
</header>

<section>
    <h2>Dlaczego małe wydatki są niebezpieczne?</h2>
    <p>
        Kupno lodów za 10 zł, kawa „na szybko” za 15 zł czy drobna przekąska
        wydają się niewinnymi decyzjami. Problem polega na tym, że
        <strong>powtarzamy je niemal codziennie</strong>, często bez refleksji.
    </p>

    <div class="cards">
        <div class="card">
            <h3>Efekt przyzwyczajenia</h3>
            <p>
                Małe kwoty przestają być zauważalne. Mózg nie traktuje ich
                jako realnego wydatku, przez co łatwo tracimy kontrolę.
            </p>
        </div>
        <div class="card">
            <h3>Brak planowania</h3>
            <p>
                Wydatki spontaniczne rzadko są uwzględnione w budżecie,
                a to właśnie one najczęściej „zjadają” nasze oszczędności.
            </p>
        </div>
        <div class="card">
            <h3>Skala czasu</h3>
            <p>
                10 zł dziennie to niewiele… ale w skali roku to już kilka
                tysięcy złotych, które znikają niepostrzeżenie.
            </p>
        </div>
    </div>
</section>

<section>
    <h2>Przykład z życia</h2>

    <div class="highlight">
        <p>
            Jeśli codziennie wydajesz <strong>10 zł</strong>:
        </p>
        <ul>
            <li>Po tygodniu: <strong>70 zł</strong></li>
            <li>Po miesiącu: <strong>ok. 300 zł</strong></li>
            <li>Po roku: <strong>ponad 3600 zł</strong></li>
        </ul>
        <p>
            To równowartość wakacji, nowego sprzętu elektronicznego
            lub solidnej poduszki finansowej.
        </p>
    </div>
</section>

<section>
    <h2>Policz swoje straty</h2>

    <div class="calculator">
        <label for="amount">Ile złotych wydajesz dziennie na drobne rzeczy?</label>
        <input type="number" id="amount" placeholder="np. 10">

        <button onclick="calculate()">Oblicz</button>

        <div class="result" id="result"></div>
    </div>
</section>

<section>
    <h2>Jak ograniczyć małe wydatki?</h2>

    <div class="cards">
        <div class="card">
            <h3>Świadomość</h3>
            <p>
                Zapisuj wszystkie wydatki, nawet te najmniejsze.
                Już sama świadomość często prowadzi do zmian.
            </p>
        </div>
        <div class="card">
            <h3>Alternatywy</h3>
            <p>
                Zamiast kupować kawę na mieście – przygotuj ją w domu.
                Małe zmiany dają duże efekty.
            </p>
        </div>
        <div class="card">
            <h3>Cel finansowy</h3>
            <p>
                Konkretna motywacja (np. wakacje, oszczędności)
                pomaga oprzeć się impulsywnym zakupom.
            </p>
        </div>
    </div>
</section>

<footer>
    <p>© 2026 Małe kwoty – duże straty</p>
    <p>Strona edukacyjna o finansach osobistych</p>
</footer>

<script>
    function calculate() {
        const amount = document.getElementById("amount").value;
        const result = document.getElementById("result");

        if (amount <= 0) {
            result.innerHTML = "Podaj poprawną kwotę.";
            return;
        }

        const month = amount * 30;
        const year = amount * 365;

        result.innerHTML = `
            <p>📅 Miesięcznie: <strong>${month.toFixed(2)} zł</strong></p>
            <p>📆 Rocznie: <strong>${year.toFixed(2)} zł</strong></p>
        `;
    }
</script>

</body>
</html>
