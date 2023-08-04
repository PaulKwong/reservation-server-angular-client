# ReservationClient

OpenReservation angular client, developed with angular 12 + material, supports deployment to docker and k8s

[![Build status](https://weihanli.visualstudio.com/Pipelines/_apis/build/status/OpenReservation.AngularClient.CI)](https://weihanli.visualstudio.com/Pipelines/_build/latest?definitionId =21)

## Docker

``` bash
docker run -d -p 8081:80 openreservation/angular-client:latest
```

##Kubernetes

``` bash
kubectl apply -f k8s-deploy.yaml
```

##More

Reservation server: <https://github.com/OpenReservation/ReservationServer>
