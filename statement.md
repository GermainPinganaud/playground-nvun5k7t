# Exemple


*On peut rédiger un simple quiz en markdown auquel sont ajouté certaines fonctionnalités.*

## Quizz

```python
try:
    a = {"key": "value"}
    print("Success")
except:
    print("Failure")

try:
    b["key"] = "value"
    print("Success")
except:
    print("Failure")

try:
    c = {}
    c["key1"]["key2"] = "value"
    print("Success")
except:
    print("Failure")
```

?[Quels messages la console va afficher?]
-[ ] Failure, Failure, Failure
-[ ] Success, Failure, Failure
-[ ] Success, Success, Failure
-[ ] Success, Success, Success


## Execution de script

*On peut aussi executer du script (et donner la réponse, du coup).*

```python runnable
try:
    a = {"key": "value"}
    print("Success")
except:
    print("Failure")

try:
    b["key"] = "value"
    print("Success")
except:
    print("Failure")

try:
    c = {}
    c["key1"]["key2"] = "value"
    print("Success")
except:
    print("Failure")

```

## Utilisation plus avancé

*On peut conserver les quizz sur github, importer des library pour faire des script plus avancés. L'éditeur en ligne comprend la commande ctrl + z pour undo et probablement plein d'autre choses.*
