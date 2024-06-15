# Az alkalmazás letöltése

Az alkalmazás legfrissebb verzióját a [download.anytype.io](https://download.anytype.io) oldalról töltheted le.

{% hint style="info" %}
Az Anytype önálló, asztali és mobil eszközökön működő szoftver. Az alkalmazásnak nincs böngészőben futtatható verziója. A böngészőalkalmazásokban számos sebezhetőségi pont van, amelyek veszélyeztetnék elkötelezettségünket az adatbiztonság és a titkosítás iránt.
{% endhint %}

### Rendszerkövetelmények

* PC és Mac: az Electron fejlesztési platform használata miatt a rendszerkövetelményeket az Electron határozza meg. Például a Windows 7 és Windows 8.1 rendszerek nem támogatottak, mert a Microsoft általi támogatási időszakok lejártak
* Android: 8.0 vagy újabb rendszert futtató, 64-bites, legalább 4 GB RAM-mal rendelkező eszköz (ha az alkalmazás a Google Play-ről lett beszerezve)
* iOS: iOS 16 vagy újabb

### Telepítési hely

Az Anytype telepítési könyvtára az egyes operációs rendszerek esetében az alábbi:

* Windows 10 vagy újabb rendszeren, általában:\
  `C:\Felhasználók\<felhasználónév>\Appdata\Local\Programs\anytype2\Anytype.exe`\&#x20;
* MacOS: ` HHD > Felhasználók >`` `` `_`felhasználónév`_` `` ``> Library > Application Support > anytype `
* Linux: `~/.config/anytype`
* Android: `_device/data/app\_​`, a gyorsítótár mentési helye: `_device/data/data/io.anytype.app_`
  A könyvárat biztonságos mappában tároljuk, amely a felhasználó által nem hozzáférhető.
* iOS: az alapértelmezett telepítési helyet a rendszer határozza meg

### Tárolási hely módosítása

A széf létrehozásakor lehetőséged van a tárolási hely kiválasztására a meghajtón. A tárolási helyet abban az esetben is megváltoztathatod, ha már rendelkezel széffel az eszközön. Ehhez jelentkezz ki az alkalmazásból, majd a bejelentkezési képernyő jobb felső sarkában lépj a Beállításokra. A széfbe történő belépést követően az adataidat szinkronizáljuk.

<figure><img src="../.gitbook/assets/Custome Storage Location.gif" alt="" width="563"><figcaption></figcaption></figure>

{% hint style="danger" %}
Ügyelj arra, hogy a **Csak helyi** hálózati beállítás használata esetén az adataidat legfeljebb két eszközön tárolhatod a peer-to-peer (P2P) kapcsolat révén.
{% endhint %}

#### Hordozható meghajtók és felhőtárhelyek&#x20;

A széf tárolási helyeként hordozható meghajtót is beállíthatsz. Ehhez csatlakoztasd a meghajtót az eszközödhöz, majd kövesd a lépéseket a [#Tárolási hely módosítása](get-the-app.md#custom-storage-location "mention") pontban. Ne feledd, hogy adataidat csak akkor fogod tudni elérni, ha a meghajtó csatlakoztatva van.

Felhőtárhelyek használatát (pl. Google Drive, iCloud) tárolási helyként nem javasoljuk, mert az eltérő szinkronizálási technológiák használati problémákat eredményezhetnek.
