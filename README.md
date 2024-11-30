# bienvenue 👋 dans notre application de détection d'objets dans une image par l'IA 🤖

## Contexte de notre projet 

Groupe 5 - Participants du projet :

AKAKPO Samuel

YACKOUNDA MOUGOULA Belle

MENGUE M'ELLA Colette

MBANG OBIANG Donia

Nous avons décidé de faire ce projet suite à notre appréciation commune du Lab Microsoft n°2 AI-900 "Analyze images in Vision Studio" , qui nous a permis d'avoir des connaissances sur fondamentaux de l'IA.  

Nous avons remarqué que nous avons intégré dans notre quotidien l'utilisation des outils NLP, tels que Copilot ; cependant, ceux orientés vers l'analyse d'images et la reconnaissance d'objets semblent parfois moins accessibles et utilisés par le plus grand nombre. 
Certes analyser des images et reconnaître des objets autour de nous peut paraître trivial pour les humains, mais le mécanisme qui permet à une IA de réaliser ces tâches est incroyablement complexe et fascinant. Grâce aux API qui ont été mis à notre disposition, nous souhaitions approfondir notre compréhension.  

Notre projet consiste donc à développer une application mobile pour analyser régulièrement l'environnement qui nous entoure. 



## Get started
pré-requis :

   - [visual studio code](https://apps.microsoft.com/detail/xp9khm4bk9fz7q?launch=true&mode=full&hl=fr-fr&gl=fr&ocid=bingwebsearch)
   
   - [Node JS](https://nodejs.org/en/download/prebuilt-installer)

1. Install
   - cloner le depot git et l'ouvrir avec vsCode
   - Verifier que NodeJs est bien installer en faisant :
     
   ```bash
   node --version
   ```
   
   ```bash
   npm --version
   ```
   
   ```bash
   npx --version
   ```
   Si vous rencontrez des erreurs, essayez avec la commande prompt au lieu de powerShell et si cela persiste, réessayez de reinstaller [Node JS](https://nodejs.org/en/download/prebuilt-installer)

   - Installation des dépendances
     
     Dans le terminal a la racine du projet faite :
     
   ```bash
   npm install
   ```
   
   - Installation de l'API
     
     A la racine du projet ouvrez le ficher apiConfig.js
     
     ![image](https://github.com/user-attachments/assets/8f87bcd7-3820-4d8c-b1a0-000ba7e2f80f)

     Puis ajoutez y votre cle et votre endpoint
     
     ![image](https://github.com/user-attachments/assets/5d062605-39b6-4dd3-b430-9760782c348e)

     Nous avons deja complete l'URL plus loin dans le code

   - Installation d'Expo Go sur votre smartPhone [IOS](https://apps.apple.com/fr/app/expo-go/id982107779) ou [Android](https://play.google.com/store/apps/details?id=host.exp.exponent&hl=fr&pli=1)

     ![image](https://github.com/user-attachments/assets/8a5d1970-2a69-4a51-8c24-7f0d01237b91)

     	vous n'avez pas besoin de vous authentifier vous pouvez skip cette etape
     

2. Start the app
   Maintenant nous somme pres a run notre application

   Assurez vous que votre smartPhone et votre ordinateur sois sur le meme resaux.

   Dans le terminal a la racine du projet faite :  

   ```bash
    npm start
   ```
   Apres l'execusion de la commande si dessus votre ceci 👇 devrait s'afficher dans votre terminal
   
   ![image](https://github.com/user-attachments/assets/2d12eef1-b4be-457e-9bfa-88330df18a94)

   - Sur IOS
     
     Vous avez juste a scanner le QRCode avec votre camera ensuite cliquer sur le lien qui devrait souvrire normalement dans votre application Expo GO
     
     Puis attendez quelques seconde le temps que l'application se build.


   - Sur Android
     
     Ouvrez l'application Expo go, vous devriez voir apparetre a l'acceuil un boutton scan QR code
     
     ![image](https://github.com/user-attachments/assets/617d54d2-488b-46f9-bd1f-400cd16ae812)


      scanner le QRCode Puis attendez quelques seconde le temps que l'application se build.

     Que se soit sur IOS ou sur Android

     vous devrez d'abord avoir :

      comme interface 👇

        ![image](https://github.com/user-attachments/assets/8785eaca-8eb7-4871-9b85-bd7a5065f9c4)

  	 puis ceci 👇

        ![image](https://github.com/user-attachments/assets/fe12bcc6-5ffe-4cf7-8f63-dab58f97a013)
     
     	Si jamais vous avez cette intercace si dessous malgre que vos deux appareil soit sur le meme resaux  sacher que c'est une errreur resaux
     	et que votre telephone n'arrive pas a acceder a l'application.

        ![image](https://github.com/user-attachments/assets/8bc77704-091d-44df-9c07-93e20c791956)

	pour y remedier vous pouvez allumer le point d'acces de votre ordinateur et vous y connecter avec votre telephone re Scanner le Qr code.


  3. Utilisation de l'application
     
     Nous vous suggerons d'etre en mode sombre☺️

     Vous aurez une interface comme ceci 👇(IOS)
     
     ![image](https://github.com/user-attachments/assets/a1caa3ae-f880-4a2b-96b6-cf59f0ad2a62)

 - choisiser entre prendre une photo ou charger une photo
 - Autoriser l'acces a l'appareil photo ou a la gallerie
 - prennez une photo, recadrer la puis appuyer sur analyser
 - Vous verrez une page de chargement puis les resultats de l'analyse
     

## Limitation Identifiée et Perspectives d’Amélioration

Cependant, nous avons rencontré une petite contrainte liée au traitement des images. Pour que l’analyse fonctionne correctement, il est nécessaire de :

1. Prendre la photo à environ 30 centimètres de l’objet à analyser.
 
2. Zoomer sur l’image avant de lancer l’analyse.

Si l’analyse échoue, il suffit d’ajuster le zoom sur l’image et de réessayer. Cette étape est importante car l’algorithme a besoin d’une image de taille et de qualité optimales pour fonctionner correctement.

À l’avenir, cette limitation pourrait être levée en :

- Ajoutant un module capable de redimensionner automatiquement les images avant l’analyse.
 
- Optimisant l’algorithme pour qu’il s’adapte à différents formats et résolutions sans intervention manuelle.
 

