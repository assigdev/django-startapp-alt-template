# Django StartApp Alt Template

Альтернативный шаблон для startapp

#### Фичи:

##### По дефлту
- добалвен forms.py
- добавлен urls.py
- добавлена дериктория tests с тестами для моделей и вьюшек

##### Full
- добалвен forms.py
- добавлен urls.py
- добавлена дериктория tests с тестами для моделей и вьюшек
- шаблоны list.html и detail.html


### Использование:

startapp default:

    $ python manage.py startapp --template=https://github.com/assigdev/django-startapp-alt-template/archive/default.zip --extension=py --name=Procfile app_name
    
startapp full:

    $ python manage.py startapp --template=https://github.com/assigdev/django-startapp-alt-template/archive/full.zip --extension=py --name=Procfile app_name

OR:

use project template https://github.com/assigdev/django-project-alt-template

then python manage.py altstartapp app_name
