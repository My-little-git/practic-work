# Поучитель по Git для начинающих

Для перемещения и управления фалами и дирикториями в терминале компьютера используются bash-команды
Вот некоторые из них:
1. Перемещение по дерикориям -  __cd__
2. Просмотр всех папок - __ls__
3. Создание дириктории - __mkdir__
4. Удаление файла и удаление дириктории - __rm__ и __rmdir__ соответственно

Более конкретную информацию можно найти на [сайте](https://git-scm.com "Сайт Git") Git

```mermaid
graph LR;
untracked -- "git add" --> staged;
  staged    -- "???"     --> tracked/comitted;

%% стрелка без текста для примера: 
  A --> B;
```
