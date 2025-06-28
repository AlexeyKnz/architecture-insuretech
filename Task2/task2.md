#### Результат работы:
К сожалению образ приложенный в уроке не работает docker pull ghcr.io/yandex-practicum/scaletestapp:latest
Error response from daemon: Head "https://ghcr.io/v2/yandex-practicum/scaletestapp/manifests/latest": unauthorized,
в связи с этим использовал shestera/scaletestapp:latest.
Чтобы добиться репликации выбрал настройки locust 20000/20000, так как не сразу добился
пересечения границы утилизации памяти, на скрине видно что при первом тесте дошел только до 58%,
затем увеличив нагрузку реплика создалась.