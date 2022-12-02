# Ldumay - App - .Net with Avalonia UI

Création d'une applicaiton C# avec Avalonia UI

- Site officiel : [avaloniaui.net](https://avaloniaui.net/)
- Documentation complète : [docs.avaloniaui.net](https://docs.avaloniaui.net/)
- Documentation complète de démarrage: [docs.avaloniaui.net](https://docs.avaloniaui.net/docs/getting-started)

## 1 - Pré-requis

- Dotnet : **6.0**

## 2 - Création d'une application Avalonia UI

### 2.1 - Importation d'un template Avalonia

```
dotnet new --install Avalonia.Templates
```

## 2.2 - Création d'une application

```
dotnet new avalonia.app -o MyApp
```

## 2.3 - Démarrer l'application

```
cd MyApp
dotnet run
```

## 2.3 - IDE - IntelliJ Rider - Installer les extensions Avalonia

L'IDE JetBrains Rider a un support intégré pour Avalonia XAML [**à partir de la version 2020.3**](https://www.jetbrains.com/rider/whatsnew/2020-3/#version-2020-3-avalonia-support), y compris un support de première classe pour les fonctionnalités XAML spécifiques à Avalonia et les inspections de code personnalisées.

> **NB** : Consultez [**l'annonce de la version 2020.3**](https://www.jetbrains.com/rider/whatsnew/2020-3/#version-2020-3-avalonia-support) de JetBrains Rider pour plus d'informations. Rider ne fournit pas encore de concepteur visuel, mais cela est en cours de développement. Consultez [**le projet GitHub**](https://github.com/ForNeVeR/AvaloniaRider) pour plus d'informations et les instructions d'installation.

Cependant, il est nécessaire d'installer **l'édition EAP7 de Rider à partir de la version 2022.3 et ultérieur**.
- [Cliquer ici](https://plugins.jetbrains.com/plugin/14839-avaloniarider/) pour vérifier si votre version de Rider est compatible avec le plugin.

## 2.3 - IDE - Visual Studio - Installer les extensions Avalonia

Pour Visual Studio, Avalonia est déjà disponible en extension.

> **NB** : L'extension Avalonia pour Visual Studio comprend un concepteur XAML qui peut être utilisé pour afficher un aperçu en direct du XAML pendant que vous l'écrivez. Une fois l'extension Avalonia pour Visual Studio installée, double-cliquez sur un fichier XAML Avalonia pour l'ouvrir.
Si vous utilisez VS2019 ou VS2017, vous devez installer l'extension pour les anciennes versions.

Pour installer l'extension Avalonia dans Visual Studio :

1. Il suffit d'ouvrir **Visual Studio** ou via un projet.
2. Puis d'installer les extensions **Avalonia** (tel que sur l'image si dessus).

![img](/_img/001.png)