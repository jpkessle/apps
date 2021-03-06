---

copyright:
  years: 2017, 2018
lastupdated: "2018-05-21"

---

{:shortdesc: .shortdesc}
{:tip: .tip}
{:new_window: target="_blank"}
{:codeblock: .codeblock}
{:screen: .screen}

# Tutoriel d'initiation
{: #create}

Dans {{site.data.keyword.Bluemix}}, vous pouvez générer des applications mobiles et Web au niveau de l'entreprise, et tirer parti des extensions cloud hébergées par {{site.data.keyword.Bluemix_notm}}. Vous pouvez utiliser les outils de ligne de commande et la console {{site.data.keyword.Bluemix}} pour générer, exécuter et déployer vos applications. Vous pouvez démarrer de deux façons : en créant une application avec un kit de démarrage qui gère le processus pour vous, ou, si vous savez précisément ce que vous voulez, en générant votre application avec les ressources dont vous avez besoin.
{:shortdesc}

Vous pouvez utiliser un kit de démarrage pour que votre application démarre rapidement et pour la préparer à des développements futurs. Choisissez un kit de démarrage et un langage de programmation, créez une application, puis configurez une chaîne d'outils DevOps pour déployer automatiquement votre application. Vous pouvez également télécharger le code pour un examen immédiat.

Les kits de démarrage sont disponibles dans de nombreuses catégories, telles que les suivantes :

* [Watson](https://console.bluemix.net/developer/watson){:new_window}
* [Apple](https://console.bluemix.net/developer/appledevelopment){:new_window}
* [Mobile](https://console.bluemix.net/developer/mobile){:new_window}
* [Application Web](https://console.bluemix.net/developer/appservice){:new_window}
* [Sécurité](https://console.bluemix.net/developer/security){:new_window}
<!--* [Watson Data Platform developer console](https://console.bluemix.net/developer/dataplatform)-->
* [Finance](https://console.bluemix.net/developer/finance){:new_window}

## Avant de commencer

[Inscrivez-vous ](https://console.bluemix.net){: new_window} pour obtenir un compte {{site.data.keyword.cloud_notm}}. Indiquez votre adresse électronique, votre nom, le nom de votre société, votre région et votre numéro de téléphone.

Vous n'avez pas besoin d'une carte de crédit pour obtenir un compte gratuit, mais si vous entrez un numéro de carte de crédit, vous pourrez accéder à davantage de ressources et vous comprendrez mieux tout ce que {{site.data.keyword.cloud_notm}} peut vous offrir.

## Etape 1 : Créer une application
{: #project}

1. Cliquez sur l'icône **Menu** ![Icône Menu](../icons/icon_hamburger.svg) > **Applications Web**.

2. Cliquez sur **Initiation** dans la section **Démarrer à partir du Web**.

3. Sélectionnez un kit de démarrage de votre choix, lisez les détails, puis cliquez sur **Créer**.

  Pour voir ce qui est inclus dans le kit de démarrage, développez la vignette sur le tableau de bord des kits de démarrage de service d'application.
  {: tip}

4. Donnez un nom à votre application, sélectionnez votre langage, puis cliquez sur **Créer**.

C'est un bon début ! Vous venez de créer une application.

Pour examiner votre code, cliquez sur **Télécharger le code** sur la page des détails d'application. Vérifiez le fichier `README.md` dans le fichier compressé téléchargé pour savoir si vous devez exécuter d'autres actions pour rendre votre application de démarrage active.
{: tip}

## Etape 2 : Ajouter des ressources
{: #addResources}

La majeure partie des kits de démarrage demande à {{site.data.keyword.cloud_notm}} de mettre automatiquement des ressources à votre disposition. Vous pouvez également associer davantage de ressources à votre application en cliquant sur **Ajouter une ressource** sur la page des détails d'application.

Pour développer et exécuter votre application localement utilisez le [{{site.data.keyword.dev_cli_notm}}](../cli/idt/index.html)
{: tip}

## Etape 3 : Effectuer un déploiement sur {{site.data.keyword.cloud_notm}}
{: #deploy}

Cliquez sur **Déployer dans Cloud** sur la page des détails d'application, sélectionnez une méthode de déploiement (par exemple, Kubernetes Cluster ou Cloud Foundry App), puis cliquez sur **Créer**. {{site.data.keyword.cloud_notm}} crée automatiquement une chaîne d'outils ouverte complétée par un référentiel Git et un pipeline de distribution continue. Visualisez le composant pipeline de votre nouvelle chaîne d'outils afin de commencer le processus de génération et de déploiement initial de sorte que votre application soit active en quelques minutes.

Vous êtes maintenant prêt pour des tâches de développement itératif et de distribution continue.
