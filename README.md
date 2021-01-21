# SerienStream-API

---

Legende: <br>
[o]: optional <br>
[r]: required

---

URL : https://s.to/api/v1/series/list

Method : Get

Parameter: [o] extended (0, 1); [o] category (0, 1, 2, 3, 4); [o] genre (0, 1)

Info [DE]: Liefert eine Liste der Serien.

---

URL : https://s.to/api/v1/genres/list

Method : Get

Parameter: 

Info [DE]: Liefert eine Liste der Genre.

---

URL : https://s.to/api/v1/series/get

Method : Get

Parameter: [r] series (Serien-ID); [o] season (Staffel)

Info [DE]: Liefert Informationen zu einer Serie, Staffel oder Episode.

---

URL : https://s.to/api/v1/statistics/get

Method : Get

Parameter:

Info [DE]: Liefert die aktuelle Statistik.

---

URL : https://s.to/api/v1/account/login

Method : Post

Parameter: [r] email; [r] passwort

Info [DE]: Meldet einen Nutzer an und setzt ein Session-Cookie (SSTOCDN).

---

URL : https://s.to/api/v1/accountseenepisodes

Method : Get

Parameter: [r] SSTOCDN (Session-Cookie)

Info [DE]: Listet alle gesehenen Episoden des Nutzers.

---

URL : https://s.to/api/v1/account/watchlist/list

Method : Get

Parameter: [o] extended (0, 1); [r] SSTOCDN (Session-Cookie)

Info [DE]: Gibt die Serien der Watchlist des Nutzers aus.

---

URL : https://s.to/api/v1/account/watchlist/add

Method : Post

Parameter: [r] id; [r] SSTOCDN (Session-Cookie)

Info [DE]: Fügt der Watchlist einen Eintrag hinzu.

---

URL : https://s.to/api/v1/account/watchlist/remove

Method : Post

Parameter: [r] wid; [r] SSTOCDN (Session-Cookie)

Info [DE]: Entfernt in der Watchlist einen Eintrag.

---

URL : https://s.to/api/v1/account/subscription/list

Method : Get

Parameter: [o] extended (0, 1); [r] SSTOCDN (Session-Cookie)

Info [DE]: Gibt die Abonnierten Serien des Nutzers aus.

---

URL : https://s.to/api/v1/account/subscription/add

Method : Post

Parameter: [r] id; [r] SSTOCDN (Session-Cookie)

Info [DE]: Fügt den Abonnierten Serien einen Eintrag hinzu.

---

URL : https://s.to/api/v1/account/subscription/remove

Method : Post

Parameter: [r] id; [r] SSTOCDN (Session-Cookie)

Info [DE]: Entfernt in den Abonnierten Serien einen Eintrag.

---
