# aside

Antraštės (ang. headers) ir poraštės (ang. footers) yra būdai, kaip prie straipsnio (ang. article) pridėti papildomos informacijos, tačiau kartais norime iškelti tam tikrą informaciją iš straipsnio. Pavyzdžiui, remiamame tinklaraščio įraše gali būti skelbimas apie remiančią įmonę; tačiau tikriausiai nenorime, kad tai būtų straipsnio teksto dalis. Tam skirtas `<aside>` elementas. Paprastai tariant tai yra blokinis elementas skirtas tam tikrai reklamai :D

---

```html
<article>
    <header>
        <h2>Semantic HTML</h2>
        <p>By Troy McClure. Published January 3rd</p> </header>
            <!-- advertisement -->
            <aside class='advert'>
                <img src='some-ad.png'/>
            </aside>
        <p>This is an example web page explaining HTML5 semantic markup.</p>
</article>
```