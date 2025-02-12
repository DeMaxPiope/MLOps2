## Домашнее задание №2.
**Цель**
В этом задании вы познакомитесь с основами управления данными с помощью DVC, управления экспериментами с использованием MLflow и автоматизации с ClearML. Ваша задача — интегрировать все три инструмента для построения полного цикла ML-проекта.
**Часть 1: управление данными с DVC**
Задача: использовать DVC для управления данными и построения ML-пайплайнов. Настроить удаленное хранилище и запустить пайплайн с использованием CI/CD.
Этапы выполнения
Добавление данных в DVC:
Добавьте набор данных в проект, используя DVC.
Закоммитьте изменения и добавьте DVC файлы в Git.
Настройка удаленного хранилища:
Настройте удаленное хранилище для DVC (например, Google Drive, AWS S3).
Убедитесь, что данные могут синхронизироваться с удаленным хранилищем.
Создание и запуск пайплайна:
Создайте пайплайн для обработки данных (например, очистка данных или подготовка признаков).
Закоммитьте пайплайн в DVC.
Интеграция DVC в CI/CD:
Настройте пайплайн в CI/CD, который будет автоматически запускать DVC-процесс.
Убедитесь, что пайплайн может корректно запускать шаги обработки данных.
**Часть 2: управление экспериментами с MLflow**
Задача: настроить MLflow для управления экспериментами и их сравнением.

Этапы выполнения
Настройка MLflow:
Настройте MLflow для локальной работы или используйте удаленное хранилище.
Убедитесь, что все логи и модели сохраняются корректно.
Запуск экспериментов:
Проведите как минимум два эксперимента с разными параметрами моделей.
Зафиксируйте все метрики экспериментов.
Сравнение моделей:
Используйте MLflow для сравнения двух или более моделей по различным метрикам.
Постройте отчет о производительности моделей.
Документация и отчет:
Составьте отчет с визуализацией результатов экспериментов, включая графики метрик и выводы.
**Часть 3: автоматизация экспериментов с ClearML**
Задача: использовать ClearML для автоматизации процессов, создания и запуска пайплайнов.

Этапы выполнения
Настройка ClearML:
Настройте ClearML сервер и интеграцию с проектом.
Убедитесь, что все эксперименты логируются и доступны через веб-интерфейс.
Создание и запуск пайплайнов:
Создайте автоматизированный пайплайн для запуска экспериментов и обработки данных.
Запустите пайплайн через ClearML и убедитесь, что все шаги корректно выполняются.
Сравнение моделей:
Используйте ClearML для сравнения результатов экспериментов и моделей.
Составьте отчет с выводами.
Отчет и визуализация:
Создайте отчет, содержащий визуализацию экспериментов и моделей, а также анализ результатов.
