# wc

> Zlicza linie, słowa, i bajty.
> Więcej informacji: <https://www.gnu.org/software/coreutils/manual/html_node/wc-invocation.html>.

- Policz linie w pliku:

`wc --lines {{plik}}`

- Policz słowa w pliku:

`wc --words {{plik}}`

- Policz znaki (bajty) w pliku:

`wc --bytes {{plik}}`

- Policz znaki w pliku (uwzględniając znaki zapisane więcej niż jednym bajtem):

`wc --chars {{plik}}`

- Użyj standardowego wejścia aby policzyć po kolei linie, słowa, i znaki (bajty):

`{{find .}} | wc`

- Policz długość najdłuższej linii w pliku:

`wc --max-line-length {{plik}}`
