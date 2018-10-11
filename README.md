# Java библиотека для парсинга файлов экспорта ЕИС

В соответствии с регламентом ЕИС (http://zakupki.gov.ru) вся информация 
по госзакупкам ежедневно выкладывается на FTP (ftp://free:free@ftp.zakupki.gov.ru)
в форматах, описанных в документации (http://zakupki.gov.ru/epz/main/public/document/view.html?sectionId=432&pageNo=1&categories=FZ44&_categories=on&categories=FZ223&_categories=on&categories=FZ94&_categories=on&categories=FZALL&_categories=on)

Этот проект формирует Java библиотеку для парсинга файлов экспорта ЕИС на основе публикуемых в официальной документации схем.

Схемы имеют версионность, при выходе новой версии схемы файлы, сформированные в соответствии со старой версией, на FTP не изменяются, поэтому будьте внимательны при разборе данных.
Для поддержки версионности схем все пакеты в библиотеке имеют префикс схемы, например пакеты для версии схем 8.1.7 пакеты будут такие:

* ru.gov.zakupki.v817.base
* ru.gov.zakupki.v817.export
* ru.gov.zakupki.v817.it615  
* ru.gov.zakupki.v817.it

