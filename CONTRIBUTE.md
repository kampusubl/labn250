# Berkontribusi ke Dokumentasi

Dokumen ini disusun menggunakan [ReadTheDocs](http://readthedocs.io) dengan format reStructuredText. Silakan rujuk dokumentasi ReadTheDocs untuk informasi lengkap.

## Crash Course

1. `git clone` repository ini: (disarankan menggunakan [TortoiseGit](https://tortoisegit.org/))

        git clone https://github.com/kampusubl/laboratorium-n250.git

2. Install [Python 3](http://python.org). Untuk Windows, Anda bisa gunakan [Anaconda3](https://www.continuum.io/downloads).
3. Install Sphinx

        pip install sphinx sphinx-autobuild

4. Untuk menjalankan sphinx-autobuild dan meng-_generate_ dokumentasi terformat secara terus menerus:

        sphinx-autobuild . _build/html

5. Buka http://127.0.0.1:8000/ (yang menampilkan folder `_build/html`) di peramban web.
6. Silakan menyunting, disarankan menggunakan [Visual Studio Code](https://code.visualstudio.com/). Sambil mengedit, dokumentasi terformat akan terus diperbarui oleh sphinx-autobuild.
7. Git Commit dan Push perubahan Anda, maka situs http://crayonpedia.readthedocs.io/ juga akan otomatis terupdate.
