# Employees
Данный проект представляет приложение на Delphi, на котором располагается компонент TTreeList(!!!не DB!!! простой TTreeList), 
в который бы в виде дерева выводятся подчиненные сотрудники из таблицы SCOTT.EMP, начиная с президента компании (mgr is null).

Для задания параметров соединения с базой данных Oracle используется файл /Bin/setup.ini.
Предварительно следует скомпилировать oracle-package из файла /Database/scott.emp_processing.pck

В проекте описаны комметарии, проект реализован с помощью Odac-компонентов.
