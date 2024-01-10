# Dawn Haciendola 2024

## Getting Started
Trabajaremos conectados a github. Donde tendremos los siguientes branch
- Main
- Dev
- Featured Branches (e.j.,feature-add-new-header, fix-checkout-bug )

## Pull Request
Recordar siempre hacer pull request de algun featured branch a dev para evitar merge clonflicts

## Hotfix branch
Si encontramos un bug que necesita ser arreglado con urgencia, se creara un branch desde el `main` que se llame hotfix, una vez el fix es completado mergear de vuelta a `MAIN` y luego actualizar `Dev`

## Mantener Main actualizada
Recordar hacer pulls a main de manera recurrente para actualizar nuestro dev y los featured branches

## Staying up to date with Dawn changes
1. Navigate to your local theme folder.
2. Verify the list of remotes and validate that you have both an `origin` and `upstream`:
```sh
git remote -v
```
3. If you don't see an `upstream`, you can add one that points to Shopify's Dawn repository:
```sh
git remote add upstream https://github.com/Shopify/dawn.git
```
4. Pull in the latest Dawn changes into your repository:
```sh
git fetch upstream
git pull upstream main
```