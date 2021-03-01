# devops_les2
Будут проигонрированны

**/.terraform/*
все файлы и директории в директориях .terraform по всем папкам рекурсивно

*.tfstate
*.tfstate.*
Все файлы с расширением .tfstate и и содержащие в названии файла .tfstate.

crash.log
Файл crash.log в корне

*.tfvars
Все файлы с расширением .tfvars

override.tf
override.tf.json
*_override.tf
*_override.tf.json
файл  override.tf и override.tf.json, а так же оканчивающиеся _override.tf и _override.tf.json

.terraformrc
terraform.rc
Файлы .terraformrc и terraform.rc в корне 
