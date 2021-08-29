# section

Galvokite apie `<section>` kaip aiškų būdą apibrėžti dokumento daliai. Dažnai mums reikia turėti kontainerį kuris galėtų buti panaudotas dokumento dalims išdestyti pagal tam tikrą išsidėstymą (ang. layout). Pagal semantikos taisykles yra prasmingiau naudoti
`<section>` elementą, o ne bendrąjį `<div>`.

---

```html
<section>
    <article>...</article>
    <article>
        <section>...</section>
        <section>...</section>
    </article>
</section>
```