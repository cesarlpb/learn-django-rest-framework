# learn-rest-framework
Repositorio para aprender REST Framework de Django

Tutoriales de [documentación de REST Framework](https://www.django-rest-framework.org/)

## 0. Quickstart

Nota: este comando `django-admin startproject tutorial .` lo ejecuté sin el . final por lo que se crearon las carpetas `quickstart > quickstart`. 
La primera la he renombrado como [0.quickstart](./0.quickstart/)
Esto implica que hay que cambiar en [quickstart > views](./0.quickstart/quickstart/views.py) la línea 4 por:
```
from quickstart.serializers import UserSerializer, GroupSerializer
```
Y en [tutorial > urls](./0.quickstart/tutorial/urls.py) línea 3.
```
from tutorial.quickstart import views
```
Respecto del [tutorial de la documentación](https://www.django-rest-framework.org/tutorial/quickstart/). Lo demás está igual :) 

## 1. Serializers

[Tutorial de Serializers](https://www.django-rest-framework.org/tutorial/1-serialization/) en [1.serializers](./1.serializers/)

## 2. Request & Responses

[Tutorial de Requests y Responses](https://www.django-rest-framework.org/tutorial/2-requests-and-responses/) en [2.Requests and responses](./2.requests_responses/)

## 3. Class Based Views

## 4. 

## 5. 

## 6. 