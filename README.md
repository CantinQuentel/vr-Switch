# VR-Markdown


*hello*

```
<!DOCTYPE html>
<html>
  <head>
    <script src="https://aframe.io/releases/1.5.0/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
      <!-- Définir l'asset pour l'image du panorama -->
      <a-assets>
        <img id="panorama-image" src="chemin_vers_votre_image.jpg">
      </a-assets>

      <!-- Utiliser l'asset pour créer le panorama -->
      <a-sky src="#panorama-image"></a-sky>
    </a-scene>
  </body>
</html>

```

`<a-scene>` est l’élément principal qui contient tous les objets 3D de la scène scène A-Frame.


`<a-assets>` est utilisé pour précharger les ressources, comme l'image de panorama.


`<img id="panorama-image" src="chemin_vers_votre_image.jpg">` définit une image que vous utiliserez pour le panorama. Remplace "chemin_vers_votre_image.jpg" par le chemin vers ton image de panorama.

`<a-sky src="#panorama-image"></a-sky>` crée le panorama en utilisant l’image que vous avez définie. Il utilise l’ID de l’image comme source.

N’oublie pas de remplacer "chemin_vers_votre_image.jpg" par le chemin réel vers ton image de panorama. Attention: l’image doit être au format equirectangular pour qu’elle s’affiche correctement comme un panorama 360°.
