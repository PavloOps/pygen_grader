# Одна из версий грейдера для поколения

${\color{red}DISCLAIMER:}$
* я не автор кода, адаптировала под свои нужды, может кому еще пригодиться
* да простят меня авторы курса, я в таске раскрыла страшную тайну решения палиндрома :)

# Инструкция
1. Делаем себе примерно такое **место хранения** ваших прекрасных решений: закидываем в корень хранения и не меняем скрипты **executor.py, test.py** (они тут лежат уже, забирайте). Потом идут **папки** как нравится. Можно папка какого-то модуля, в нем части, в частях таски, короче яйцо в утке, утка в зайце, заяц в шоке. В папке задания должны быть распакованы тесты, называйте папку "tests", в нем всякие клю, которые Тимур нам любезно выдал.

```📁 solutions_python_generation/<br>
├─📄 executor.py
├─📄 test.py
└─📁 module10/
│ └─📁 part_10_5/
│   └─📁 task8/
│         ├─📄 task8.py/
│         └─📁 tests/
│               ├─📄 1
│               ├─📄 1.clue
│               ├─📄 2
│               ├─📄 2.clue
│               ├─📄 3
│               ├─📄 3.clue
│               ├─📄 4
│               ├─📄 4.clue
│               ├─📄 5
└─              └─📄 5.clue
```
2. Как запустить эту шляпу: идем в терминал (у меня PyCharm, но это без разницы), сидим в нужной папке, в моем примере это solutions_python_generation, пинаем скрипт test.py

Terminal

    cd \solutions_python_generation
    python test.py

Скрипт test.py попросит путь к папке со скриптом нашего решения (в моем примере это module10/part_10_5/task8) от того корня, котором сидим, название скрипта (в моем случае это task8.py):
Если бесит, не вставляется с ctrl+V, жмите ctrl+shift+V

Terminal

    module10/part_10_5/task8
    task8.py

3. Все!

P.S. там принт какой-то лишний болтается, мне лень его было кикнуть :)

<img src="https://github.com/PavloOps/pygen_grader/blob/main/result_pycharm.png" width="800"/>
<img src="https://github.com/PavloOps/pygen_grader/blob/main/result_shell.png" width="800"/>
<img src="https://github.com/PavloOps/pygen_grader/blob/main/result_vscode.png" width="800"/>
