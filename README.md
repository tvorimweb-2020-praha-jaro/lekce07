# [Tvořím web od A do Z](https://github.com/czechitas/tvorim-web-a-z): Podklady pro 7. lekci

Krátký odkaz na stažení: [bit.ly/webaz-lekce7](https://bit.ly/webaz-lekce7)

## Příklad

- [CSS Custom Properties](priklady/01-custom-properties)

```
:root {
    --button-size: 1rem;
}

header {
    --button-size: 2rem;
}

footer {
    --button-size: 0.75rem;
}

.btn {
    padding: calc(var(--button-size) / 2) var(--button-size)
    margin-bottom: var(--button-size);
    border-radius: calc(var(--button-size) / 5);
    font-size: var(--button-size);
}

p {
    font-size: var(--paragraph-size, 1.2rem); /* za čárkou výchozí hodnota */
}

```

## Odkazy

- [CSS proměnné (nebo také autorské či volitelné vlastnosti)](https://www.vzhurudolu.cz/prirucka/css-promenne) – zevrubný výklad pro pokročilé
