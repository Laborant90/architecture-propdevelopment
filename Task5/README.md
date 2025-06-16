Задание 5. Управление трафиком внутри кластера Kubertnetes

1) minikube необходимо запустить с параметрами:
   minikube start --network-plugin=cni --cni=calico

2) Создание подов проводится в скрипте network-policies.sh

3) Настройка трафика между сервисами определена в файлах:
* admin-api-allow1.yaml
* admin-api-allow2.yaml
* non-admin-api-allow1.yaml
* non-admin-api-allow2.yaml

