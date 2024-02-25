## Проект Discovery на основе Eureka Spring

Проект Discovery - это приложение, разработанное на основе Eureka Spring, которое обеспечивает возможность регистрации, обнаружения и управления микросервисами в вашей среде.

### Цель проекта

Цель проекта Discovery состоит в обеспечении простого и надежного механизма для управления микросервисами в распределенной архитектуре. Используя Eureka Spring, проект позволяет регистрировать различные приложения и обеспечивает механизм поиска их в сети.

### Ключевые компоненты

1. **Eureka Server**: Центральный компонент, который отвечает за регистрацию и обнаружение микросервисов. Запускается как сервер реестра, который управляет регистрацией и запросами на обнаружение.
   
2. **IntIn**: Микросервис, зарегистрированный в Eureka, который предоставляет некоторые входные данные для последующей обработки.
   
3. **IntConvert**: Микросервис, также зарегистрированный в Eureka, который отвечает за преобразование входных данных, предоставленных IntIn.
   
4. **IntHandler**: Еще один микросервис, зарегистрированный в Eureka, который обрабатывает данные, полученные от IntConvert.

5. **Gateway**: Веб-приложение, которое выступает в качестве точки входа в систему и маршрутизирует запросы к соответствующим микросервисам.


Пример зарегестрированных приложений:
<img width="2058" alt="Снимок экрана 2024-02-25 в 19 22 53" src="https://github.com/Pekar7/discovey/assets/90376574/4a83ce72-2043-4c5a-97c0-298facfe7957">
