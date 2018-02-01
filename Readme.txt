Description de l'application "RNNChiffresManuscrits"
---------------------------------------------------


Cette petite démo a été écrite en Java en utilisant TENSORFLOW pour reconnaître des chiffrer manuscrits dans des images et les classer en 10 classes : 0 , 1 ,..., 9 .

Le  modèle utilisé est Inception V3 .

Aprés l'execution du programme , on doit choisir le dossier du modéle entrainé (l'inception) en clickant sur le boutton "choose Inception" , aprés ,  on choisie une image de la base de test pour voir si le reseau de neurone peut bien reconnaitre le chiffre .

Le modèle Inception V3 pré-formé peut étre téléchargé depuis https://drive.google.com/open?id=1rH5_kKfjxO23OltWSp1Opw8UFe_mhNr_

Les images de test peuvent étres téléchargés depuis https://drive.google.com/open?id=1Lf4SbW8ZaTx5ydDKBkQi9pDA58y-zN1o 
	comme vous pouvez utiliser votre propre image (.jpg ou .jpeg ) qui contien un chiffrer de 1 à 2 et tester.

Aprés le choix du dossier de l'inception et l'image à tester , on clicke sur le boutton "predict" pour voir est ce que le réseau a bien reconue le chiffre ainsi que le pourcentage de réussite.



LA CLASSE QUI CONTIENT LA METHODE " MAIN " EST Recognizer QUI EST INCLU DANS LE PACKAGE "gi.ensao.RNNChiffresManuscrits"  .