LILA TWITCH CHAT OVERLAY

Fájl: lila-chat-overlay.html

Jellemzők
- Átlátszó, teljes képernyős böngészőréteg
- Bal alsó sarok, alapból kb. 34% széles és 29% magas
- Üveges chat buborékok, felül elhalványuló megjelenítés
- Twitch névszínek, emote-ok és a chat által küldött badge-ek
- Nyilvános Twitch chathez nem kér bejelentkezést vagy tokent

Gyors előnézet
Nyisd meg ezt a fájlt modern böngészőben. Alapértelmezett csatorna: lila.
Másik csatorna: lila-chat-overlay.html?channel=CSATORNANÉV
Üzenetszám: ?channel=CSATORNANÉV&messages=14 (3 és 30 közötti érték)

Moblin használat
1. Tedd közzé a HTML fájlt egy HTTPS címen, amelyet a telefon böngészője elér.
2. Moblinben adj hozzá Browser/Web overlay réteget, és illeszd be az URL-t, például:
   https://SAJAT-DOMAIN/lila-chat-overlay.html?channel=SAJAT_TWITCH_NEVE
3. Állítsd a réteget teljes vászonméretűre. Az oldal háttere átlátszó; a chat a kép bal alsó részén jelenik meg.

Privát GitHub repó
A forrás maradhat privát. A Moblinnek a közzétett HTML HTTPS URL-je kell; a privát github.com/.../blob/... linket nem tudja betölteni. A Pages publikus weboldal, ezért az oldal tartalmát bárki elérheti, aki ismeri az URL-t. Tartsd a Pages könyvtárban csak ezt az overlayt. Ha a repóhoz nincs GitHub Pages publikálás, használhatsz privát GitHub repót összekapcsoló statikus tárhelyet is (például Cloudflare Pages).

Technikai megjegyzés
Az emote képek és Twitch chat WebSocket a Twitch CDN/szolgáltatás felől töltődnek. A natív browser preview és Moblin Web overlay internetkapcsolatot igényel. Badge-ek a Twitch IRC badge tag alapján jelennek meg jelölt, színes ikonként; az ikon fölé tartva látszik a badge típusa és szintje.
