# Seal-Task-Manager
# A simple task manager with a focus on design.
<img width="1721" height="1018" alt="изображение" src="https://github.com/user-attachments/assets/7cf70e30-ec3c-4e6e-a9cd-e6a0058108d4" />

# It has a simpler mode designed for work...
<img width="1729" height="1016" alt="изображение" src="https://github.com/user-attachments/assets/8e3fce5f-55b3-4bc7-87c1-734e0367b342" />

# ENGLISH README
# 🦭 Seal Task Manager
## Features

Freeform board - columns can be placed anywhere on the screen, not locked to a grid

Two independent drag systems - HTML5 Drag & Drop API for task cards, Pointer API for columns; separated to avoid event conflicts

Persistent state - everything is saved to localStorage: column positions, z-index order, tasks, label colors, and UI preferences

Edit Mode — columns are locked by default to prevent accidental movement; drag handles appear only when edit mode is active

Ambient background - animated floating shapes (circles, lines, spirals) with a toggle to hide them for a cleaner workspace

Collapsible header - the title bar collapses into a small floating dot to free up screen space

Inline column renaming - click the column title to rename it directly, no modal required

Task creation modal - add a title, optional description, and one of five color labels

Deletion confirmation - custom styled dialog instead of the native confirm(), warns if the column contains tasks
z-index management - grabbed columns automatically rise to the top layer


## Stack

Vanilla HTML, CSS, JavaScript — zero dependencies

No frameworks, no npm, no build tools

Single file (~1300 lines)

Font: Varela Round via Google Fonts

# RUSSIAN README
# 🦭 Seal Task Manager

Свободная доска - колонки размещаются в любой точке экрана, не привязаны к сетке

Две независимые drag-системы - HTML5 Drag & Drop API для карточек задач, Pointer API для колонок; разделены чтобы избежать конфликтов событий

Персистентный стейт - всё сохраняется в localStorage: позиции колонок, порядок слоёв, задачи, цвета меток и настройки интерфейса

Режим редактирования - по умолчанию колонки зафиксированы; drag-маркеры появляются только при включённом edit mode

Анимированный фон - плавающие фигуры (круги, линии, спирали) с кнопкой отключения для чистого рабочего пространства

Сворачиваемый хедер - панель с названием сворачивается в маленький плавающий шар

Инлайн-переименование колонок - клик по названию колонки открывает редактирование прямо на месте, без модалки

Модалка создания задачи - заголовок, опциональное описание, один из пяти цветных тегов

Подтверждение удаления - стилизованный диалог вместо нативного confirm(), предупреждает если в колонке есть задачи

Управление z-index - захваченная колонка автоматически выходит на передний план


## Стек

Ванильный HTML, CSS, JavaScript — ноль зависимостей

Никаких фреймворков, npm, инструментов сборки

Один файл (~1300 строк)

Шрифт Varela Round через Google Fonts

# Notes
_Проект делал скорее для себя, но что-то вдохновился залить его на гитхаб. Не рассчитываю на особые охваты, но, что есть то есть..._

_I made this project mostly for myself, but I got inspired to upload it to GitHub. I’m not expecting it to reach a wide audience, but it is what it is..._
