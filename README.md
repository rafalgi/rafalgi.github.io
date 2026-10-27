# rafalgibala.github.io


## Struktura
```
index.html   treść strony
style.css    wygląd
img/photo.jpg   Twoje zdjęcie (dodaj)
cv.pdf       Twoje CV (dodaj)
```

## Publikacja na GitHub Pages
1. Na GitHubie utwórz publiczne repo o nazwie **`<twoj-login>.github.io`** (dokładnie tak).
2. Wrzuć do niego te pliki (+ `img/photo.jpg`, `cv.pdf`):
   ```bash
   git init
   git add .
   git commit -m "Personal website"
   git branch -M main
   git remote add origin https://github.com/<twoj-login>/<twoj-login>.github.io.git
   git push -u origin main
   ```
3. Settings → Pages → Source: *Deploy from a branch*, branch `main`, folder `/ (root)`.
4. Po 1-2 minutach strona działa pod `https://<twoj-login>.github.io`.

## Do uzupełnienia
Wyszukaj `TODO` w `index.html`: linki (Scholar, GitHub, LinkedIn), mail, tytuły i współautorzy publikacji, daty, studia I stopnia.
