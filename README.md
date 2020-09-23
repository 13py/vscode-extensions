## vscode-extensions

Мой конфиг для работы с python, django, flask, html, css

### сохранине плагинов vscode

code --list-extensions >> vs_code_extensions_list.txt

### установка плагинов vscode из файла

cat vs_code_extensions_list.txt | xargs -n 1 code --install-extension

### удаление всех плагинов vscode

code --list-extensions | xargs -n 1 code --uninstall-extension

### текущая тема

bluloco-dark-italic
