# Zadanie 2 - CLI c.d

1. Stwórz katalog errors

2. W katalogu errors stówrz nowy plik 404.html z taką zawartością:
```
<html lang="pl-PL">
<head>
    <meta charset="UTF-8" />
    <title>404 - Nie znaleziono</title>
    <link rel="stylesheet" href="./css/style.css" />
</head>
<body>

<header>
    <h1>Smaczne Przepisy Kulinarne</h1>
    <img src="./images/logo.png" alt="Smaczne Przepisy Kulinarne - logo" />
</header>

<nav>
    <ul>
        <li><a href="index.html">Strona Główna</a></li>
        <li><a href="./dish/list.html">Dania</a></li>
    </ul>
</nav>

<main>
    <h2>404 - Nie znaleziono</h2>
    <p>Niestety nie udało nam się znaleźć tego, czego szukałeś :(</p>
</main>

<footer>
    Zrobione przez Oskara Kupskiego
</footer>
</body>
</html>
```

3. Zmodyfikuj plik index.html w taki sposób, aby usunąć elementy menu: "Składniki Dań" oraz "Składniki". 

4. Wykonaj analogiczne zmiany w plikach list.html oraz details.html w katalogu dish.

5. * Popraw ściezke do pliku style.css w details.html. Powinna być taka sama jak w pliku list.html