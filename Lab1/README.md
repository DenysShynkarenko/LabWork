# LabWork

Лабораторная работа 1

Цель работы:

Освоение работы с гитхабом. Базовые команды для работы в нем и создание аккаунта в гитхабе

Выполнение работы:

1. Создаем обліковий запис GitHub

Создадим аккаунт перейдя по ссылке https://github.com/join?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home

Сама регистрация интуитивна понятная поэтому мы ее подробно расписывать не будем

2. Встановіть CHOCOLATEY

После регестрации нам нужно установить на свой компьютер CHOCOLATEY. В кратце опишим, что такое Chocolatey

Chocolatey — менеджер пакетов с интерфейсом командной строки и установщик программного обеспечения Windows на машинном уровне.
Он использует инфраструктуру упаковки NuGet и Windows PowerShell для упрощения процесса загрузки и установки программного обеспечения.

Теперь нам нужно его установить

Делается это при помощи командной строки запущеной от имени администратора и команды Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

![](ChocoInstall.png)








