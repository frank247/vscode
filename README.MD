
**Лабораторная работа №8** -  Использование фреймворкаQt для разработки графического приложения

**Цель работы:** Разработать на языке C++ с использованием кросплатформенногофреймворка с открытым исходным кодом Qt графическое приложение.

**Ход работы:**

1.	Создать Git-репозиторий на GitHub

Создал Git-репозиторий на Github

2.	Подключить репозиторий в среде разработки vscode

Подключил репозиторий в среде разработки vscode спомощъю команды git clone

3.	Установить Qt на операционную систему Linux

Установил   QT спомощъю команды  sudo apt-get install qt5-default

4.	Записать код создания приложения в файл main.cpp

Прописал код в vscode:


#include QApplication>


#include QMainWindow>


#include QDesktopWidget>


#include QMenuBar>

int main(int argc, char *argv[])


{


  QApplication a(argc, argv);


  QMainWindow w;


  QMenu *fileMenu = w.
  
  menuBar()->addMenu("&File");


  QDesktopWidget dw;


  int x=dw.width()*0.7;


  int y=dw.height()*0.7;


  w.setFixedSize(x,y);


  w.show();


  return a.exec();

}

5.	Собрать и запустить приложение.

Собрал и запустил приложение. 
 
Вывод: Разработал на языке C++ и использовал кросплатформенный  фреймвор с открытым исходным кодом Qt графическое приложение.
