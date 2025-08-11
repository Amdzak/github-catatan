# Catatan sih

- `.htaccess` untuk redirect defautl index
- `autopep8 -i -r .` untuk formatter berdasarkan standart autopep8
- `autoflake -i -r .` untuk menghapus unused import atau variable

# Laravel Install

- `sudo apt install php8.4-pdo php8.4-xml php8.4-mbstring php8.4-sqlite3 php8.4-curl`

> automation
- `sudo apt install $(php -v | grep -oP 'PHP \K[0-9]+\.[0-9]+' | sed "s/^/php/; s/$/-pdo php&-xml php&-mbstring php&-sqlite3 php&-curl/")`
