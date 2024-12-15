---
cover: ../.gitbook/assets/Frame 1050.png
coverY: 0
---

# 📊 Moyennes générales

Papillon récupère automatiquement votre moyenne générale depuis votre service scolaire si celui-ci le fournit. Mais dans le cas ou votre moyenne est indisponible, Papillon va venir automatiquement la calculer.

{% hint style="warning" %}
Le calcul automatique des moyennes **n'est pas une information exacte**, mais une estimation qui essaye de s'en rapprocher un maximum.
{% endhint %}

### Le problème

Nous n'avons pas connaissance des algorithmes de calcul de moyennes des services scolaires. C'est pour cela que la communauté s'investit pour en fournir [une alternative documentée](https://github.com/PapillonApp/Papillon/blob/main/src/utils/grades/getAverages.ts) et la plus efficace possible. Cependant, celle-ci ne fonctionne pas dans toutes les configurations.

### Ma moyenne est incorrecte, que faire ?

#### La question de la méthode de calcul

Lorsque l'on parle de **moyenne générale**, on parle ici de la moyenne pondérée de la moyenne des matières, en prenant donc en compte les coefficients, barèmes, notes bonus et autres variables. Il se peut que selon les paramètres considérés, cela change.

#### Aidez-nous à mieux comprendre vos notes

Venez sur le [Discord](https://discord.gg/wVKWBRTbfh) nous partager votre problème ! Cela peut nous aider à améliorer le calcul pour tous les utilisateurs !&#x20;

{% hint style="info" %}
Pour considérer cela comme problématique, il faut une différence **notable** avec votre moyenne réelle, d'au delà de 0.30 points environ.
{% endhint %}

