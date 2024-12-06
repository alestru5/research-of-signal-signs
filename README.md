# Исследование сигнальных признаков
Программа для выполнения лабораторной работы по Теории Информации

# Подключение к удаленному репозиторию:

'''
Клонирование удалённого репозитория с использованием HTTPS
git clone https://github.com/alestru5/research-of-signal-signs

Переход в ваш локальный репозиторий
cd path_to_dir

Проверка добавленного удалённого репозитория
git remote -v

# Как писать код и выкладывать его:

1) Создать новую ветку:
'''
git checkout -b "RESEARCHSIGNALS-3" (вместо 3 пишите номер тиккета из трекера)
'''
Далее изменения делаете в новой ветке
2) После изменения кода вы добавляете его
'''
git add . (вместо . указывайте путь/пути до файлов которые изменили)
'''
3) Делаете коммит
'''
git commit -m "name_commit"
'''
4) Создаете пулл реквест
'''
git push origin RESEARCHSEGNALS-3 --force (вместо RESEARCHSEGNALS-3 пишите название ветки которую вы создали)
'''
После создания ПР вам необходим один апрув от кого угодно из команды, чтобы смержить его с мастером
