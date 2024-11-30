# Contexte de notre projet 

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

   -visual studio code
   
   -Node JS

1. Install

   ```bash
   npm install
   ```

2. Start the app

   ```bash
    npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Limitation Identifiée et Perspectives d’Amélioration
Cependant, nous avons rencontré une petite contrainte liée au traitement des images. Pour que l’analyse fonctionne correctement, il est nécessaire de :
	1.	Prendre la photo à environ 30 centimètres de l’objet à analyser.
	2.	Zoomer sur l’image avant de lancer l’analyse.

Si l’analyse échoue, il suffit d’ajuster le zoom sur l’image et de réessayer. Cette étape est importante car l’algorithme a besoin d’une image de taille et de qualité optimales pour fonctionner correctement.

À l’avenir, cette limitation pourrait être levée en :
	•	Ajoutant un module capable de redimensionner automatiquement les images avant l’analyse.
	•	Optimisant l’algorithme pour qu’il s’adapte à différents formats et résolutions sans intervention manuelle.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
