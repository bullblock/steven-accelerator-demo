# Accelerator Log

## Options
```json
{
  "bsGitBranch" : "main",
  "bsGitRepository" : "github.com?owner=bullblock&repo=steven-accelerator-demo",
  "gitopsAccount" : "bullblock",
  "gitopsEmail" : "steven.liang@icloud.com",
  "gitopsEnabled" : true,
  "pageColor" : "green",
  "projectName" : "steven-accelerator-demo",
  "repositoryPrefix" : "us.gcr.io/lloyd-266015"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(UseLast))
┃ ┃ ┃ engine.transformations[0].validated.merge (Chain)
┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0] (Merge)
┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo, Combo)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, Exclude)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[0].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[0].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/*]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/launch.json matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/settings.json matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug Procfile matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug app.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/accelerator.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug docs/index.md matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/__init__.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/__init__.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/errors.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/views.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/config.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/models.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/utilities.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/css/main.css matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/broken-tooth-grin.png matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/surfing-web-icon.png matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/404.html matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/500.html matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/base.html matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/home.html matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug mkdocs.yml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug project.toml matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug requirements.txt matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug runtime.txt matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug techdocs_publish.sh matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/conftest.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/__init__.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/test_recipes.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/unit/__init__.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┗ Debug tests/unit/test_models.py matched [**/*] -> included
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[0].<combo>.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [config/*.yaml, Tiltfile, README.md, catalog/*.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/launch.json didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/settings.json didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug Procfile didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug app.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/accelerator.yaml matched [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug docs/index.md didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/__init__.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/__init__.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/errors.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/views.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/config.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/models.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/utilities.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/css/main.css didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/broken-tooth-grin.png didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/surfing-web-icon.png didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/404.html didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/500.html didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/base.html didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/home.html didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug mkdocs.yml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug project.toml didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug requirements.txt didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug runtime.txt didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug techdocs_publish.sh didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/conftest.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/__init__.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/test_recipes.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/unit/__init__.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┗ ┗ Debug tests/unit/test_models.py didn't match [config/*.yaml, Tiltfile, README.md, catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [Tiltfile]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/launch.json didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/settings.json didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Procfile didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [Tiltfile] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug app.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/accelerator.yaml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug docs/index.md didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/__init__.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/__init__.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/errors.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/views.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/config.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/models.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/utilities.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/css/main.css didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/broken-tooth-grin.png didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/surfing-web-icon.png didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/404.html didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/500.html didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/base.html didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/home.html didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mkdocs.yml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug project.toml didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug requirements.txt didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug runtime.txt didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug techdocs_publish.sh didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/conftest.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/__init__.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/test_recipes.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/unit/__init__.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug tests/unit/test_models.py didn't match [Tiltfile] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo>.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [docker.io/project->us.gcr.io/lloyd-2660...(truncated), surfersflaskaccelerator->steven-accelerator-d...(truncated)]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText, ReplaceText, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [config/*.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/launch.json didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/settings.json didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Procfile didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug app.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/accelerator.yaml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [config/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug docs/index.md didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/__init__.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/__init__.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/errors.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/views.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/config.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/models.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/utilities.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/css/main.css didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/broken-tooth-grin.png didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/surfing-web-icon.png didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/404.html didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/500.html didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/base.html didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/home.html didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mkdocs.yml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug project.toml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug requirements.txt didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug runtime.txt didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug techdocs_publish.sh didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/conftest.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/__init__.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/test_recipes.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/unit/__init__.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug tests/unit/test_models.py didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#bsGitRepository != null) evaluated to true
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [https://github.com/surfers-lookout/surfers-flask-accelerator->https://github.com/b...(truncated)]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[2] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#gitopsEnabled) evaluated to true
┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [gitopsaccountname->bullblock, gitopsemailaddress->steven.liang@icloud....(truncated)]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[3] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [: surfers-flask-accelerator->: steven-accelerator...(truncated), value: blue->value: green, : surfersflaskaccelerator->: steven-accelerator...(truncated)]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[3].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[3].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [README.md]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/launch.json didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/settings.json didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Procfile didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug app.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/accelerator.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug docs/index.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/__init__.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/__init__.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/errors.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/views.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/config.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/models.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/utilities.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/css/main.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/broken-tooth-grin.png didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/surfing-web-icon.png didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/404.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/500.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/base.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/home.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mkdocs.yml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug project.toml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug requirements.txt didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug runtime.txt didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug techdocs_publish.sh didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/conftest.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/__init__.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/test_recipes.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/unit/__init__.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug tests/unit/test_models.py didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[3].<combo>.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┗ ┗  Info Will replace [surfers-flask-accelerator->steven-accelerator-d...(truncated), surfersflaskaccelerator->steven-accelerator-d...(truncated), SurfersFlaskAccelerator->steven-accelerator-d...(truncated)]
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[4] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[4].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[4].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [catalog/*.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/launch.json didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/settings.json didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Procfile didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug app.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/accelerator.yaml matched [catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [catalog/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug docs/index.md didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/__init__.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/__init__.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/errors.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/blueprints/views.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/config.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/models.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/data/utilities.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/css/main.css didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/broken-tooth-grin.png didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/static/images/surfing-web-icon.png didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/404.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/500.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/base.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug main/templates/home.html didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mkdocs.yml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug project.toml didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug requirements.txt didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug runtime.txt didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug techdocs_publish.sh didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/conftest.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/__init__.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/functional/test_recipes.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug tests/unit/__init__.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug tests/unit/test_models.py didn't match [catalog/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[4].<combo>.transformations[1] (ReplaceText)
┃ ┃ ┃ ┗ ┗ ┗  Info Will replace [surfers-flask-accelerator->steven-accelerator-d...(truncated), surfersflaskaccelerator->steven-accelerator-d...(truncated)]
┃ ┗ ┗ ╺ engine.transformations[0].validated.merge.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
