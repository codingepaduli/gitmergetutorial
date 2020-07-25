# gitmergetutorial

## Creazione branch

``git branch development`` Crea il branch

``git branch -vv`` elenca i branch

``git checkout development`` passa al branch dev

operazione di add e commit

``git log --pretty=format:"%h %s" --graph`` vede i vari cambiamenti

``git push`` chiede l'upstream

``git push --set-upstream origin development`` crea un upstream, cioè un branch remoto

Poi vado in remoto, clicco su "New pull request", seleziono un confronto "master" -> "development", e clicco "crea pull request" e confermo.

Creata la pull request, devo cliccare "merge e pull" e poi confermo.

Per sincronizzare con remoto
```
git fetch --all
```

Per pulire rispetto ai branch remoti:
```
git fetch --prune
```
