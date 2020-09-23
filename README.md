## Vscode-extensions

Мой конфиг для работы с python, django, flask, html, css

### Сохранение плагинов vscode

code --list-extensions >> vs_code_extensions_list.txt

### Установка плагинов vscode из файла

cat vs_code_extensions_list.txt | xargs -n 1 code --install-extension

### Удаление всех плагинов vscode

code --list-extensions | xargs -n 1 code --uninstall-extension

### Текущая тема

bluloco-dark-italic
