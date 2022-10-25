"# lesson-" 
devman@challenges:~$ help scrape_coupons
bash: help: no help topics match `scrape_coupons'.  Try `help help' or `man -k scrape_coupons' or `info scrape_coupons'.
devman@challenges:~$ man -k scrape_coupons
bash: man: command not found
devman@challenges:~$ man scrape_coupons
bash: man: command not found
devman@challenges:~$ info scrape_coupons
bash: info: command not found
devman@challenges:~$ scrape_coupons --help
usage: scrape_coupons [-h] [--category CATEGORY] [--store STORE] [--sort]
                      [--max MAX]

optional arguments:
  -h, --help           show this help message and exit
  --category CATEGORY  Название категории, которой стоит ограничиться
  --store STORE        Название магазина, которым стоит ограничиться
  --sort               Сортировать по убыванию скидки
  --max MAX            Число купонов, которое надо вывести
devman@challenges:~$ scrape_coupons -- store Фитнес-клуб
usage: scrape_coupons [-h] [--category CATEGORY] [--store STORE] [--sort]
                      [--max MAX]
scrape_coupons: error: unrecognized arguments: -- store Фитнес-клуб
devman@challenges:~$ scrape_coupons
ОЛИМП                    Фитнес-клуб                7%   321396
ЕвроСтройСервис          Строительные материалы     4%   C42169
Спортклуб "Cmon"         Фитнес-клуб               70%   ABDE44
Азалия                   Мебель                     4%   5E72A1
Ярмарка продуктов        Продукты                   4%   BFBF99
ОЛИМП                    Фитнес-клуб                4%   BE81ED
Азалия                   Мебель                     5%   A85C9D
Электроник               Электроника                4%   F8F768
Конструктор              Строительные материалы    40%   4FFF1D
Arena Fitness            Фитнес-клуб                7%   08544E
Царские хоромы           Мебель                     7%   1E3322
DreamHouse               Строительные материалы    30%   7A1AA0
е-маркет                 Электроника                4%   ACCA20
Мир спорта               Спортивные товары         70%   1BE75C
Азалия                   Мебель                     5%   318AAE
Korean Island            Электроника               30%   BBA366
Магазин "Titanlab"       Спортивные товары          7%   02454D
Korean Island            Электроника                4%   7343D0
Магазин "Titanlab"       Спортивные товары          4%   CCCDFE
Мясной пир               Продукты                  70%   3A5FA9
На связи                 Электроника                5%   066B43
Магазин "Titanlab"       Спортивные товары          7%   AE54F3
Самоделкин               Строительные материалы    30%   973630
Самоделкин               Строительные материалы    70%   880D67
Конструктор              Строительные материалы    40%   1AC0C9
Ярмарка продуктов        Продукты                  40%   B85CB5
Adibas                   Спортивные товары         70%   152E74
Электроник               Электроника               30%   C8EEFC
Обстановка               Мебель                    40%   07C0C2
На связи                 Электроника               70%   AA71AC
Jasmine                  Мебель                    40%   0E5853
Восемь бит               Электроника                7%   3FDA4C
Электроник               Электроника                4%   4A24E2
Belize                   Мебель                    40%   BEE586
Belize                   Мебель                    30%   819371
От прихожей до спальни   Мебель                     5%   F48F64
Спортклуб "Cmon"         Фитнес-клуб                7%   278D84
Обстановка               Мебель                     5%   FB3B3E
Обстановка               Мебель                    40%   C983B5
Зевс                     Фитнес-клуб               70%   87DD7F
ОЛИМП                    Фитнес-клуб                4%   932434
Обстановка               Мебель                     4%   4EF4E3
Азалия                   Мебель                     5%   F31DCF
Arena Fitness            Фитнес-клуб               70%   DEA087
Какаду                   Мебель                    70%   2BE35E
Мир спорта               Спортивные товары          4%   33FE4C
ЕвроСтройСервис          Строительные материалы     5%   F4C316
Инструментарий           Строительные материалы    70%   2CB9CC
На связи                 Электроника               70%   D062DB
Спортклуб "Cmon"         Фитнес-клуб                4%   E38BF1
Какаду                   Мебель                     4%   D04441
Korean Island            Электроника                4%   F8EF8E
Царские хоромы           Мебель                     7%   418B6A
Adibas                   Спортивные товары          4%   0B3AA4
Царские хоромы           Мебель                     4%   C88293
Зевс                     Фитнес-клуб               70%   A5B50F
Belize                   Мебель                     7%   1D6391
Happy Fitness            Фитнес-клуб                7%   87969E
е-маркет                 Электроника               70%   02501F
Nike                     Спортивные товары          7%   0EADC9
От прихожей до спальни   Мебель                    70%   AE902F
Конструктор              Строительные материалы    40%   C1078F
ЕвроСтройСервис          Строительные материалы     5%   B14332
Какаду                   Мебель                    30%   EA2A55
ОЛИМП                    Фитнес-клуб               30%   7B7D21
На связи                 Электроника               40%   269DDB
Ярмарка продуктов        Продукты                  70%   660A7F
Happy Fitness            Фитнес-клуб               30%   4FB389
Самоделкин               Строительные материалы    70%   C4CA53
Спортклуб "Cmon"         Фитнес-клуб               30%   B940CC
DreamHouse               Строительные материалы    30%   60142D
Конструктор              Строительные материалы     5%   F434B9
Ярмарка продуктов        Продукты                   4%   20B466
Nike                     Спортивные товары          4%   1CFEFB
Инструментарий           Строительные материалы    70%   1541AD
Мясной пир               Продукты                  30%   81AB05
Мир спорта               Спортивные товары         70%   8ECDC6
е-маркет                 Электроника               70%   E09402
Мир спорта               Спортивные товары         30%   72597A
Titanlab                 Строительные материалы     9%   123ZZ9
DreamHouse               Строительные материалы    40%   3E3471
Домашний                 Продукты                  30%   FCFBCC
Царские хоромы           Мебель                    30%   A9273C
ЕвроСтройСервис          Строительные материалы     4%   56A06B
Магазин "Titanlab"       Спортивные товары          5%   CCA603
Jasmine                  Мебель                    40%   F01513
Восемь бит               Электроника               40%   AB595F
Jasmine                  Мебель                    40%   1FF335
Домашний                 Продукты                  70%   114F58
Titanlab                 Строительные материалы     4%   114F59
Titanlab                 Строительные материалы     6%   115A69
devman@challenges:~$ scrape_coupons --^C
devman@challenges:~$ scrape_coupons --category ФИТНЕС-КЛУБ
devman@challenges:~$ scrape_coupons --category Фитнес-клуб
ОЛИМП                    Фитнес-клуб                7%   321396
Спортклуб "Cmon"         Фитнес-клуб               70%   ABDE44
ОЛИМП                    Фитнес-клуб                4%   BE81ED
Arena Fitness            Фитнес-клуб                7%   08544E
Спортклуб "Cmon"         Фитнес-клуб                7%   278D84
Зевс                     Фитнес-клуб               70%   87DD7F
ОЛИМП                    Фитнес-клуб                4%   932434
Arena Fitness            Фитнес-клуб               70%   DEA087
Спортклуб "Cmon"         Фитнес-клуб                4%   E38BF1
Зевс                     Фитнес-клуб               70%   A5B50F
Happy Fitness            Фитнес-клуб                7%   87969E
ОЛИМП                    Фитнес-клуб               30%   7B7D21
Happy Fitness            Фитнес-клуб               30%   4FB389
Спортклуб "Cmon"         Фитнес-клуб               30%   B940CC
devman@challenges:~$ scrape_coupons --category Фитнес-клуб --sort --max 3
Спортклуб "Cmon"         Фитнес-клуб               70%   ABDE44
Зевс                     Фитнес-клуб               70%   87DD7F
Arena Fitness            Фитнес-клуб               70%   DEA087
devman@challenges:~$ scrape_coupons --store Nike
Nike                     Спортивные товары          7%   0EADC9
Nike                     Спортивные товары          4%   1CFEFB
devman@challenges:~$ scrape_coupons --store Мир спорта
usage: scrape_coupons [-h] [--category CATEGORY] [--store STORE] [--sort]
                      [--max MAX]
scrape_coupons: error: unrecognized arguments: спорта
devman@challenges:~$ scrape_coupons --store " Мир спорта"
devman@challenges:~$ scrape_coupons --store "Мир спорта"
Мир спорта               Спортивные товары         70%   1BE75C
Мир спорта               Спортивные товары          4%   33FE4C
Мир спорта               Спортивные товары         70%   8ECDC6
Мир спорта               Спортивные товары         30%   72597A
devman@challenges:~$ scrape_coupons --store 'Магазин "Titanlab"'
Магазин "Titanlab"       Спортивные товары          7%   02454D
Магазин "Titanlab"       Спортивные товары          4%   CCCDFE
Магазин "Titanlab"       Спортивные товары          7%   AE54F3
Магазин "Titanlab"       Спортивные товары          5%   CCA603
devman@challenges:~$
