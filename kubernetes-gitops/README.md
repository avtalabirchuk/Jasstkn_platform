# Выполнено ДЗ №9

 - [x] Основное ДЗ
 - [x] Задание co :star: | Автоматизация подготовки Kubernetes cluster
 - [x] Задание со :star: | Установка Istio operator

## В процессе сделано:
 - Сконфигурирован репозиторий (https://gitlab.com/Jasstkn/base-layer)[base-layer] с возможностью автоматической валидации terraform кода, построения плана, деплоя и дестроя окружения
 - Сконфигурирован репозиторий platform-layer c возможностью автоматического построения диффа, деплоя и дестроя инфраструктурных сервисов
 - Сконфигурирован репозиторий microservices-demo с возможностью валидации Dockerfile-ов, сборки единовременно всех образов или образа конкретного приложения и пуша в удаленный докер репозиторий
 - Сконфигурирована GitOps система на основе FluxCD + Helm-Release для автоматического деплоя новых образов или изменений в хелм-чартах
 - Установлен Istio несколькими способами: как add-on для GKE, через istioctl и через Istio Operator (в base-layer репозитории istio можно включить через переменную окружения)

## Как запустить проект:

## Как проверить работоспособность:


## Ответы на вопросы: