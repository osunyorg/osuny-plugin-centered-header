# Plugin Osuny : centered header

Ce plugin centre le menu principal en desktop.

## Utilisation

D'abord, importer le plugin dans le site.

```bash
git submodule add git@github.com:osunyorg/osuny-plugin-centered-header.git themes/osuny-plugin-centered-header
```

Ensuite, ajouter le plugin comme un thème dans `config/_default/config.yaml`.

```yaml
theme: 
  - osuny
  - osuny-plugin-centered-header
```

Enfin, importer le style dans `assets/sass/main.sass`.

```sass
@import "osuny-plugin-centered-header/style"
```

## Exemples 

- https://prototype.frenchcraftguild.osuny.site
