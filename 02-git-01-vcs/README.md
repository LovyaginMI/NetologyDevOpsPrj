# create

### За счет файла .gitignore, в каталоге terraform, не попадут в репозиторий (исключение из версионного контроля):
#### все содержимое каталога .terraform проекта
#### файлы с расширением:
- .tfstate
- .tfvars
#### файл журнала crash.log
#### файлы
- override.tf
- override.tf.json
- .terraformrc
- terraform.rc
#### файлы, оканчивающиеся на:
- _override.tf
- _override.tf.json
