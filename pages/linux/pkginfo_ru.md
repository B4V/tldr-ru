# pkginfo

> Запросить базу данных пакетов в системе CRUX.

- Список установленных пакетов и их версий:

`pkginfo -i`

- Список файлов, принадлежащих пакету:

`pkginfo -l {{package_name}}`

- Список владельца(ов) файлов, соответствующих шаблону:

`pkginfo -o {{pattern}}`

- Вывести отпечаток файла:

`pkginfo -f {{file}}`
