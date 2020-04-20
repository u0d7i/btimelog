# btimelog
basic time tracker in bash

Heavily influenced by the [concepts](https://gtimelog.org/docs.html) of lovelly [gtimelog](https://github.com/gtimelog/gtimelog).

Source the file directly or from within some login rc script:

```
$ source timelog
```

Enjoy:
```
$ t
t - timetracker
usage: t                      # show this help
usage: t <activity>           # log new activity
usage: t h|-h|--help          # show this help
usage: t e|-e|--edit          # edit timelog
usage: t l|-l|--last [nr]     # show last activity(-ies), 10 by default
usage: t r|-r|--report [<r>]  # generate report
                 t - today    #default
                 a - all
                 y - yesterday
usage: t t|-t|--time          # report time since last activity
```
