# Coin Lab tutorial

A bilingual learning hub with a landing page and a separate interactive clicker-game tutorial.

## Open locally

Download the repository ZIP, extract it, and open `index.html` in a browser. Choose **Start the clicker tutorial** to open the content page. Keep `index.html` and `coin-lab-tutorial.html` in the same folder. No Node.js, npm, or build command is needed.

## Pages

| Page | Purpose |
| --- | --- |
| `index.html` | Bilingual landing page, course overview, and small coin-clicking demo |
| `coin-lab-tutorial.html` | Eight interactive lessons, playable game, source downloads, and testing checklist |

The landing page passes its selected language to the tutorial using `?lang=en` or `?lang=id`. The tutorial also has its own language switch.

## Publish with GitHub Pages

After merging the homepage changes:

1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Choose branch **main** and folder **/(root)**, then click **Save**.
4. Wait for the Pages deployment in the **Actions** tab to succeed.
5. Visit **https://fian-ab.github.io/tutorial/**.

The homepage is `index.html`; the content page is `coin-lab-tutorial.html`. The `.nojekyll` file tells GitHub Pages to serve the static files without Jekyll processing. Updates committed to `main` publish automatically after Pages is enabled.

## Bahasa Indonesia

Unduh ZIP repositori, ekstrak, lalu buka `index.html` di browser. Pilih **Mulai tutorial game klik** untuk membuka halaman konten. Simpan `index.html` dan `coin-lab-tutorial.html` dalam folder yang sama. Tidak perlu Node.js, npm, atau perintah build.

`index.html` adalah halaman pembuka dua bahasa dengan ringkasan pelajaran dan demo klik koin. `coin-lab-tutorial.html` berisi delapan pelajaran interaktif, game lengkap, unduhan sumber, dan daftar pengujian. Bahasa yang dipilih pada halaman pembuka diteruskan ke tutorial melalui `?lang=en` atau `?lang=id`.

Setelah perubahan digabungkan:

1. Buka **Settings → Pages** pada repositori.
2. Pilih **Deploy from a branch** pada bagian **Build and deployment**.
3. Pilih branch **main** dan folder **/(root)**, lalu klik **Save**.
4. Tunggu deployment Pages di tab **Actions** berhasil.
5. Buka **https://fian-ab.github.io/tutorial/**.

File `.nojekyll` membuat GitHub Pages menyajikan file statis tanpa pemrosesan Jekyll. Perubahan di `main` akan diterbitkan otomatis setelah Pages diaktifkan.
