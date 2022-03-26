
<p align="center" >
<img height="100" src="http://assets.stickpng.com/images/580b57fcd9996e24bc43c51f.png" />
</p>

# Google Clone avec Next.js

C'est le clone de Google où vous pouvez rechercher n'importe quoi et il affichera exactement le même résultat que nous avons utilisé l'API personnalisée de Google à travers laquelle nous avons réalisé ce projet, il est entièrement réactif et vous pouvez également l'installer en tant que PWA. Vous pouvez également visiter les liens sans danger, mais il y a un inconvénient à ce que Google n'autorise que 100 requêtes à partir d'une seule clé API par jour. Ainsi, cette application ne peut rechercher que 100 fois par jour.

## Fonctionnalités

- Recherche Google précise et en temps réel
- Mode plein écran
- **PWA** installable
- Rechercher n'importe quelle requête
- Réactivité totale
- Prise en charge du thème sombre en fonction de l'appareil de l'utilisateur

## Technologies utilisées

<p>  
<img title="React JS" width="60" src="https://cdn4.iconfinder.com/data/icons/logos-3/600/React.js_logo-128.png" />
<img title="Next JS" width="60" src="https://iconape.com/wp-content/files/gm/82643/svg/next-js.svg"  />&nbsp;
<img title="Tailwind" width="60" src="https://cdn.icon-icons.com/icons2/2699/PNG/512/tailwindcss_logo_icon_167923.png"> 
<img title="Google Search API" width="60" src="https://cutt.ly/zRgpYnW">
</p>

## Démonstration

[Cliquer ici pour voir le site](https://google-clone-ten-alpha.vercel.app/)




## Commencer

Créer un répertoire ou un dossier

```bash
mkdir project
```

Cloner le projet

```bash
  clone git https://github.com/codingtuto/google-clone.git
```

Aller dans le répertoire du projet

```bash
  cd project
```

Installer les dépendances

```bash
  npm install
  # ou
  yarn
```

Tout d'abord, lancez le serveur de développement :

```bash
  npm run dev
  # ou
  yarn dev
```

Ouvrez http://localhost:3000 avec votre navigateur pour voir le résultat.

Vous pouvez commencer à éditer la page en modifiant pages/index.js. La page se met à jour automatiquement lorsque vous modifiez le fichier.

Les routes API sont accessibles sur http://localhost:3000/api/hello. Ce point de terminaison peut être modifié dans pages/api/hello.js.

Le répertoire pages/api est mappé sur /api/\*. Les fichiers de ce répertoire sont traités comme des itinéraires d'API au lieu de pages React.

## Variables d'environnement

Pour exécuter ce projet, vous devrez ajouter les variables d'environnement suivantes à votre fichier .env

`NEXT_PUBLIC_API_KEY` - [Cliquez ici](https://developers.google.com/custom-search/v1/introduction#identify_your_application_to_google_with_api_ke)

- Allez sur le lien et cliquez sur **Obtenir une clé**
- Si vous avez déjà créé un projet, continuez, sinon créez-en un nouveau et suivez les étapes après avoir terminé, vous obtiendrez la clé API

`NEXT_PUBLIC_CONTEXT_KEY` - [Cliquez ici](https://cse.google.com/cse/create/new)

- Accédez au lien et saisissez "www.google.com", puis cliquez sur **Créer**
- puis cliquez sur `Obtenir le code`
 - vous obtiendrez la balise de fichier de script dans ce fichier, telle que `<script async src="https://cse.google.com/cse.js?cx=b221ffffddfd63f8a4"></script>` nous n'avons besoin que du `cx ` valeur *copier* cela et coller dans votre `.env`

`NEXT_PUBLIC_GEOLOCATION_API` - [Cliquez ici](https://ipdata.co/)
 - Allez sur le lien et créez un compte et obtenez l'API gratuitement
 - Il y a une limite de 1500 demandes par jour, alors soyez prudent avec cela et collez-le dans `.env`

## Licence

[MIT](https://choosealicense.com/licenses/mit/)

## Retour d'information

Si vous avez des commentaires, veuillez nous contacter à notre bot Telegram @codingsupport_bot
## Développeur

- [@codingtuto](https://t.me/codingtuto)
