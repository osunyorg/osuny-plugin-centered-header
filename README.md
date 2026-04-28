# Plugin Osuny : centered header

Ce plugin centre le menu principal en desktop.

<img width="1440" height="731" alt="image" src="https://github.com/user-attachments/assets/65987ebc-4460-4fa5-acdb-6dc67b58f662" />


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

<img width="1440" height="786" alt="image" src="https://github.com/user-attachments/assets/52ef58f5-4939-4cdb-a2e6-2f787939bd25" />

