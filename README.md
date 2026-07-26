# GGDeals to PCGamingWiki link

Userscript de Tampermonkey que añade un enlace a PCGamingWiki en las páginas de GG.deals. / Tampermonkey userscript that adds a PCGamingWiki link to GG.deals pages.

## Español

**Qué hace:** en las páginas de juego, pack o DLC de **GG.deals** añade un botón hacia **[PCGamingWiki](https://www.pcgamingwiki.com/)** (compatibilidad, arreglos y configuración técnica) buscando por el título mostrado en la página. Incluye el logo de PCGamingWiki como SVG inline (evita bloqueos de CSP/hotlink).

**Instalación:**
1. Instala [Tampermonkey](https://www.tampermonkey.net/).
2. Abre el instalador: [ggdeals-to-pcgamingwiki.user.js](https://github.com/g31w0fw0rld/ggdeals-to-pcgamingwiki/raw/main/ggdeals-to-pcgamingwiki.user.js) (también en [GreasyFork](https://greasyfork.org/es-419/users/1590477-g31w) y [OpenUserJS](https://openuserjs.org/users/g31w0fw0rldgmail.com/scripts)).

**Sitios:** `gg.deals/game/*`, `gg.deals/pack/*`, `gg.deals/dlc/*`

## English

**What it does:** on **GG.deals** game, pack or DLC pages it adds a button to **[PCGamingWiki](https://www.pcgamingwiki.com/)** (compatibility, fixes and technical configuration), searching by the title shown on the page. The PCGamingWiki logo is embedded as inline SVG (avoids CSP/hotlink blocking).

**Install:**
1. Install [Tampermonkey](https://www.tampermonkey.net/).
2. Open the installer: [ggdeals-to-pcgamingwiki.user.js](https://github.com/g31w0fw0rld/ggdeals-to-pcgamingwiki/raw/main/ggdeals-to-pcgamingwiki.user.js) (also on [GreasyFork](https://greasyfork.org/es-419/users/1590477-g31w) and [OpenUserJS](https://openuserjs.org/users/g31w0fw0rldgmail.com/scripts)).

**Sites:** `gg.deals/game/*`, `gg.deals/pack/*`, `gg.deals/dlc/*`

## Privacidad / Privacy

**ES:** el script no hace ninguna petición de red ni guarda nada: solo lee el título de la página (`document.title`) para sacar el nombre del juego e inserta un enlace hacia PCGamingWiki. Declara `@grant none`, así que no tiene acceso a las APIs privilegiadas del gestor de userscripts (almacenamiento, peticiones entre dominios). No se envía nada a terceros ni al autor, y solo visitas PCGamingWiki si haces clic en el botón.

**EN:** the script makes no network requests and stores nothing: it only reads the page title (`document.title`) to get the game name and inserts a link to PCGamingWiki. It declares `@grant none`, so it has no access to the userscript manager's privileged APIs (storage, cross-origin requests). Nothing is sent to third parties or to the author, and you only visit PCGamingWiki if you click the button.

## Apoyar / Support

Esto es parte de algo que estoy construyendo para crecer. Si te sirve y quieres apoyar, puedes invitarme un café en **[Ko-fi](https://ko-fi.com/g31w0fw0rld)** —solo si quieres—; y si hay una causa que lo necesite más que yo, ayúdala a ella.

This is part of something I'm building to grow. If it helps you and you'd like to support it, you can tip me on **[Ko-fi](https://ko-fi.com/g31w0fw0rld)** —only if you want—; and if a cause needs it more than I do, help that one instead.

---
Autor / Author: **g31w0fw0rld** · Licencia / License: **MIT**
