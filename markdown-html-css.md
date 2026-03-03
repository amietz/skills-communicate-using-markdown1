# Markdown z HTML i CSS

Markdown umożliwia wstawianie surowego kodu HTML bezpośrednio w treści pliku `.md`.
Dzięki temu można korzystać z możliwości HTML i CSS tam, gdzie sama składnia Markdown nie wystarcza.

---

## 1. Nagłówki (Markdown)

```md
# Nagłówek H1
## Nagłówek H2
### Nagłówek H3
```

---

## 2. Formatowanie tekstu (Markdown)

```md
**pogrubienie**   _kursywa_   ~~przekreślenie~~
```

---

## 3. Inline HTML — zmiana koloru tekstu (CSS inline)

Markdown nie obsługuje kolorów, ale możemy użyć HTML:

```html
<span style="color: red;">Czerwony tekst</span>
<span style="color: blue; font-weight: bold;">Niebieski pogrubiony tekst</span>
```

Wynik:

<span style="color: red;">Czerwony tekst</span>  
<span style="color: blue; font-weight: bold;">Niebieski pogrubiony tekst</span>

---

## 4. Wyśrodkowanie i wyrównanie (HTML + CSS inline)

```html
<p style="text-align: center;">Tekst wyśrodkowany</p>
<p style="text-align: right;">Tekst wyrównany do prawej</p>
```

<p style="text-align: center;">Tekst wyśrodkowany</p>
<p style="text-align: right;">Tekst wyrównany do prawej</p>

---

## 5. Obrazek z kontrolą rozmiaru i pozycji (HTML w Markdown)

Zwykła składnia Markdown:

```md
![Logo GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```

HTML z rozmiarem i pozycją:

```html
<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png"
     alt="Logo GitHub" style="width: 80px; float: right;">
```

<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png"
     alt="Logo GitHub" style="width: 80px; float: right;">

---

## 6. Tabela ze stylowaniem (HTML + CSS inline)

Markdown tworzy tabele składnią `|`, ale HTML daje więcej kontroli:

```html
<table>
  <thead>
    <tr style="background-color: #f0f0f0;">
      <th>Technologia</th>
      <th>Opis</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Markdown</strong></td>
      <td>Lekki język formatowania tekstu</td>
    </tr>
    <tr>
      <td><strong>HTML</strong></td>
      <td>Język znaczników do budowy stron</td>
    </tr>
    <tr>
      <td><strong>CSS</strong></td>
      <td>Język stylowania elementów HTML</td>
    </tr>
  </tbody>
</table>
```

<table>
  <thead>
    <tr style="background-color: #f0f0f0;">
      <th>Technologia</th>
      <th>Opis</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Markdown</strong></td>
      <td>Lekki język formatowania tekstu</td>
    </tr>
    <tr>
      <td><strong>HTML</strong></td>
      <td>Język znaczników do budowy stron</td>
    </tr>
    <tr>
      <td><strong>CSS</strong></td>
      <td>Język stylowania elementów HTML</td>
    </tr>
  </tbody>
</table>

---

## 7. Blok ze stylem (HTML + CSS inline)

```html
<div style="border: 2px solid #1f883d; border-radius: 8px; padding: 12px; background-color: #e6f4ea;">
  💡 <strong>Wskazówka:</strong> Łącząc Markdown z HTML i CSS możesz tworzyć
  estetyczne dokumenty bezpośrednio w plikach <code>.md</code>.
</div>
```

<div style="border: 2px solid #1f883d; border-radius: 8px; padding: 12px; background-color: #e6f4ea;">
  💡 <strong>Wskazówka:</strong> Łącząc Markdown z HTML i CSS możesz tworzyć
  estetyczne dokumenty bezpośrednio w plikach <code>.md</code>.
</div>

---

## Podsumowanie

| Możliwość | Markdown | HTML+CSS |
|---|---|---|
| Nagłówki | ✅ | ✅ |
| Pogrubienie / kursywa | ✅ | ✅ |
| Kolor tekstu | ❌ | ✅ |
| Kontrola rozmiaru obrazka | ❌ | ✅ |
| Wyrównanie elementów | ❌ | ✅ |
| Stylowanie tabel | ❌ | ✅ |
