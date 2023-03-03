ORM 
    - helps avoid writing raw sql queries
```
class Meta
abstract=True
```
    - will make the class abstract and table wont be present in DB for this

`from django.db import models`

- `on_delete=models.CASCADE`
- `People.objects.filter(name__icontains="J")[0].name`
- `People.objects.filter(name__startswith="JON")[0].name`
- `People.objects.filter(name__endswith="collins")[0].name`
- `People.objects.filter(age__gte=20).count()`
- `People.objects.filter(age = 20).count()`
- `People.objects.get(age=20)` -> will work only if the number of objects returned is exactly 1,else it will throw error
- `People.objects.all()[0:5]`
