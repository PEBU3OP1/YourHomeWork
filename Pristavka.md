# Шпаргалка по git

## Основные Команды

*__git version__* - команда, отображающая текущую версию git.

*__git status__* - команда, отображающая состояние файла.

*__git init__* - команда, инициализируащая локальный репозиторий.

*__git add + название файла с расширением__* - команда, добавляющая папку для git с целью отслеживания файлов.

*__git commit -m "text"__* - команда, позволяющая сохранить текущее состояние файла.

*__git diff__* - команда, отображающая разницу между сохраненными файлами (commitами).

*__git log__* - команда, отображающая все сохраненные commitы.

*__git checkout__* - команда, позволяющая переключаться между сохраненными файлами (commitами)

*__git commit -amend__* - команда, редактирующая последний commit.

*__clear__* - команда очистки терминала.

## Команды ветвления

*__git branch__* - команда, выводящая список веток.

*__git branch имя ветки__* - команда, создающая новую ветку.

*__git checkout имя ветки__* - команда перемещения между ветками.

*__git branch -d имя ветки__* - команда удаления ветки.

*__git merge имя ветки__* - команда слияния веток.

    ВАЖНО! Необходмо находится в ветке куда будут загружены изменения.

*__git log -graph__* - команда визуализации веток.

## Работа с изображениями

![Мой дом](Home.jpeg)

## Синтаксис языка Markdown

(**) - жирный текст.

(*) - курсив.

(#) - Заголовок 1 типа.

    Последующие # меняют размер заголовка.

(1,2,3 ...) - нумерованный список.

(* в начале строки) - ненумерованный список.

## Удаленный репозиторий

## 1. Начало работы
* В браузере перейти по ссылке https://github.com/
* Зарегистрироваться.
* Ознакомиться с сайтой.

## 2. Команды

*git clone имя сайта* - команда, позволяющая сделать копию удаленного репозитория в локальный.

    ! в VScode не должно быть созданного репозитория.

*cd (chang directory) имя папки* - смена папки.

*git remote add origin имя сайта* - команда, связывающая удаленный и локальный репозиторий.

*git branch -M main* - команда, присваивающая приоритет ветке в удаленном репозитории.

    Если локальный репозиторий существует, то при выполнении этой команды необходимо находится в главной ветке локального репозитория.

*git push -u origin main* - команда первой отправки данных из локального в удаленный репозиторий. Далее используем *git push*.

*git pull* - команда, стягивающая данные из удаленного в локальный репозиторий.

    ! git pull - составная команда, подгружает изменения и сразу сливает их (merge).

*pull request* - запрос на предложение изменения данных в чужом репозитории.

*fork* - команда копирование с чужого удаленного репозитория в свой удаленный репозиторий.

    ! Изменения в чужом проекте делается в отдельной ветке.