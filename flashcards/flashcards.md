# Git Flashcards

## Formaat
Elk kaartje heeft:
- **Commando**: het git commando
- **Omschrijving**: wat het doet in gewone taal

---

## Kaartjes

### git switch -c <branch>
Maak een nieuwe branch aan en switch er gelijk naartoe

### git switch -
Switch terug naar de vorige branch

### git switch <branch>
Switch naar een bestaande branch

### git branch -a
Bekijk alle lokale én remote branches

### git restore <bestand>
Maak wijzigingen in een bestand ongedaan

### git restore --staged <bestand>
Haal een bestand uit de staging area (wijziging blijft behouden)

### git diff
Bekijk wijzigingen die nog niet gestaged zijn

### git diff --staged
Bekijk wijzigingen die klaarstaan om gecommit te worden

### git stash
Zet huidige wijzigingen tijdelijk opzij

### git stash push -m "omschrijving"
Zet huidige wijzigingen opzij met een naam

### git stash list
Bekijk alle opgeslagen stashes

### git stash pop
Herstel de laatste stash en verwijder hem uit de lijst

### git stash apply stash@{1}
Herstel een specifieke stash zonder hem te verwijderen

### git log --oneline --graph --all
Bekijk de commit history als compacte grafiek

### git show <commit-hash>
Bekijk de wijzigingen van een specifieke commit

### git commit --amend --no-edit
Voeg iets toe aan de laatste commit zonder de message aan te passen

### git rebase -i HEAD~3
Open de interactieve rebase editor voor de laatste 3 commits

### git tag -a <naam> -m "omschrijving"
Maak een annotated tag aan op de huidige commit

### git tag -a <naam> -m "omschrijving" <commit-hash>
Maak een annotated tag aan op een specifieke commit

### git push origin --delete <tagnaam>
Verwijder een tag op GitHub

### git remote -v
Bekijk alle geconfigureerde remotes

### git remote rename <oud> <nieuw>
Hernoem een remote

### git worktree add <path> -b <branch> <base>
Maak een nieuwe worktree aan met een nieuwe branch

### git worktree list
Bekijk alle actieve worktrees

### git worktree remove <path>
Verwijder een worktree en de bijbehorende map

### git worktree prune
Ruim achtergebleven worktree referenties op

### git fetch
Haal wijzigingen op van GitHub zonder te mergen

### git blame <bestand>
Bekijk per regel wie en wanneer die als laatste heeft aangepast