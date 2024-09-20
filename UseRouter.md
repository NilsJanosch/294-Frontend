_Mit UseRouter kann man auf die sogenannten Path Variablen zugreifen, dies wird häufig verwendet um z.B. User-Profile oder Posts anzuschauen._
_Beispiel: https://youtube.com/MrBeast <- Hierbei ist "MrBeast" die Path-Variable._

Usage Beispiel: 
```javascript
  const router = useRouter();
  const { id } = router.query;
```
Die Ordnerstruktur ist hierbei sehr wichtig, in diesem Beispiel sah die Ordner Struktur so aus:
![[zImage.png]]
[id] zeigt React, dass dieser Name mit einem Wert ersetzt wird.
Eine valide Benutzung des Beispiels ist z.B. https://localhost:3000/posts/4/comments
hierbei wurde [id] mit 4 ersetzt.