---
title: "[Jeux] Découvrez la date du DevFest Toulouse 2019"
brief: Plusieurs dizaines de personnes ont participé à notre concours pour gagner le premier ticket pour le DevFest Toulouse 2019 !
image: /images/blog/encryption.jpeg
date: 2019-01-20
draft: false
---

Aujourd'hui nous avons lancé un jeu concours pour découvrir quand aura lieu le DevFest Toulouse 2019 :

{{< tweet 1087257164182364160 >}}

Nous avons crée ce jeu pour engager la communauté et il n'aura fallut que 20 minutes pour que quelqu'un trouve la bonne réponse 😱 !

{{< tweet 1089767584302579712 >}}

Si vous avez été bloqués, voici la solution :

## Solution

1. Téléchargez ce [fichier](http://bit.ly/SaurasTuTrouverLaDateDuDevFestToulouse2019)
2. Décodez le token JWT via <http://jwt.io> (par exemple)
3. Récuperez le champ data, qui est en base64 donc décodez le via un outil en ligne ou `base64 -d ...`
4. Récuperez le fichier JPG
5. Ouvrez le avec <https://hexed.it/>
6. Découvrez la date !

Si vous voulez connaître la date sans passer par toutes ces étapes, cliquez [ici]({{< ref "/blog/get-ready-for-2019" >}})