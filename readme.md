# Threads Share - TailwindCSS

![Hasil](src\result.jpg)

### Jika ingin customisasi

1. Pastikan teman teman punya `NodeJS` di laptop.
2. Jika tidak punya `NodeJS`, teman teman harus mengganti code dibawah ini :

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Threads Share</title>

    <!-- Ganti Code dibawah ini 👇 -->
    <link rel="stylesheet" href="dist/output.css" />

    <!-- Dengan ini 👇 -->
    <script src="https://cdn.tailwindcss.com"></script>

    <script src="https://unpkg.com/@phosphor-icons/web"></script>
  </head>
</html>
```

3. Jika memiliki `NodeJS`, silahkan jalankan code berikut di terminal :

```bash
    npm install
```

4. Jika sudah selesai, jalankan lagi code berikut di terminal untuk generate css yang teman teman tulis :

```bash
npx tailwindcss -i ./src/style.css -o ./dist/output.css --watch
```

5. Tetap biarkan code nya jalan seperti dibawah ini :
   ![terminal](src\ss.png)

### Happy Coding 👋
