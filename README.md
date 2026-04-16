# Chapter01

## Description
Projet d'exemple ciblant `.NET 10`. Ce dépôt contient le code source et la solution associée pour les exercices et démonstrations du chapitre 01.

## Arborescence (extrait)
- `Chapter01.sln` — solution Visual Studio
- `<ProjectName>/` — projets C# ciblant `.NET 10`
- `README.md` — documentation (ce fichier)

(Adapté selon la structure réelle du dépôt.)

## Prérequis
- .NET 10 SDK installé (dotnet CLI)
- Visual Studio 2026 (recommandé) ou un éditeur compatible
- Connexion Internet pour restaurer les paquets NuGet si nécessaire

## Installation locale
1. Cloner le dépôt :
   - `git clone https://github.com/amine-chograni/Chapter01.git`
2. Ouvrir la solution dans Visual Studio 2026 : double-cliquer sur `Chapter01.sln`
   ou depuis la ligne de commande :
   - `cd Chapter01`
   - `dotnet restore`

> Remarque : une copie locale a été observée sous `C:\Users\hp\source\repos\Chapter01` (contexte de développement).

## Compilation et exécution
- Avec Visual Studio : ouvrir `Chapter01.sln`, sélectionner la configuration souhaitée et exécuter.
- Avec la CLI :
  - `dotnet build`
  - `dotnet run --project <ProjectPath>` (remplacer `<ProjectPath>` par le projet d'entrée)

## Tests
S'il existe un projet de tests, lancer :
- `dotnet test`

Si aucun test n'est présent, créer un projet de tests avec :
- `dotnet new xunit -n Chapter01.Tests`
- `dotnet add Chapter01.Tests reference <ProjectPath>`

## Contribution
- Ouvrir une issue pour discuter des changements majeurs.
- Créer une branche dédiée pour vos modifications :
  - `git checkout -b feat/ma-fonctionnalite`
- Faire une PR détaillée vers `master`.

## Licence
Ajouter ici le type de licence utilisé (ex. `MIT`) ou supprimer cette section si non applicable.

## Contact
Pour questions ou suggestions, ouvrir une issue sur le dépôt :  
`https://github.com/amine-chograni/Chapter01`