# Структура веток

## master

Добавили раздел для ветки master. Еще добавили изменения сюда перед тем, как производить слияние с веткой branch_005.

## branch_001

Добавлены какие-то действия для первой ветки. Закоммичены и отправлены в ветку master. 

## branch_002

Ветка branch_002 создана из ветки master, до того как были внесены изменения в ветку branch_001. После внесения изменений в branch_002, выполнено слияние с веткой master. 

## branch_003

Не переключились с ветки master и начали вносить измения для ветки branch_003. Ветка branch_003 также была создана из ветки master в самом начале, еще до выполнения всех изменений в ветках branch_001 и branch_002. 

Теперь переключились на ветку branch_003 и внесли изменения. После переключения на ветку мастер и попытке выполнить слияние изменений, ожидаем возникновение конфликта. 

При устранении конфликта оставили оба варианта и дополнили данной фразой.

## branch_004

Ветку branch_004 создали из ветки master (после того, как слили в master все изменения из веток 1, 2 и 3). Внесли информацию в данный раздел. Закоммитим изменения и сделаем слияние с веткой master. Конфликтов при слиянии не ожидаем. 

## branch_005

Еще добавили изменений для ветки 5. Теперь сольем их в master. Ожидается наличие конфликта в разделе для ветки branch_005 и в разделе для ветки maser. В разделе для ветки branch_004 конфликта не будет, данные заполнятся теми, что сейчас в ветке master.

Здесь при разрешении конфликта оставили текст из ветки branch_005/
