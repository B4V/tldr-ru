# csvgrep

> Фильтрует строки CSV-файла в соответствии с шаблоном.
> Входит в csvkit.

- Ищет строки, в которых первая колонка содержит определенное значение:

`csvgrep -c {{1}} -m {{string_to_match}} {{data.csv}}`

- Ищет строки, в которых 3 или 4 колонка соотвествует заданному регулярному выражению:

`csvgrep -c {{3,4}} -r {{regex_pattern}} {{data.csv}}`

- Ищет строки, в которых колонка "name" не содержит "John Doe":

`csvgrep -i -c {{name}} -m {{"John Doe"}} {{data.csv}}`
