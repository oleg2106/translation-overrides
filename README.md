# Kursitet's edX translation overrides

В некоторых случаях, локализация edX может и верна, но проекту Kursitet требуется другая. В этом репозитарии хранятся *.po содержащие *только* переведенные строки, которые будут использованы для забивания штатных, полученных из официального Transifex-проекта edX, или для перевода строк, которые там отсутствуют вместе с кусками кода, в которых встречаются. Формат хранения всегда следующий:

    <repository name>/<path as in repository>/<name that will be overridden>.po

Здесь не должно быть строк, которые есть в Transifex, но не переведены вовсе -- в этом случае, переводы должны попадать в непосредственно туда в первую очередь.
