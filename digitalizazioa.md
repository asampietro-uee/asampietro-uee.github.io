---
layout: page
title: Digitalizazioa
---
# Digitalizazioa

Erronka honetan ez da nahikoa izango azken emaitza lortzea. Proiektua **modu antolatuan planifikatu, garatu eta dokumentatu** beharko duzue.

Horretarako, **GitHub** erabiliko dugu lan-ingurune digital nagusi gisa. Bertan proiektuaren atazak antolatuko ditugu, taldearen lana koordinatuko dugu eta egindako lanaren jarraipena egingo dugu.

Gainera, **GitHub Pages** erabiliz webgune estatiko sinple bat sortuko duzue, erronkan egindako lana aurkezteko.

---

## 1. Proiektuaren antolaketa

Lehenengo pausoa lana egin aurretik **zer egin behar dugun eta nola antolatuko garen** zehaztea izango da.

Horretarako, talde bakoitzak GitHub-en repository bat sortuko du eta bertan **GitHub Projects** erabiliko du proiektuaren kudeaketarako.

### Kanban taula

Proiektuko atazak **Kanban metodologia** erabiliz antolatuko dituzue.

Gutxienez, egoera hauek erabiliko dira:

- **Egiteke** — Oraindik hasi ez diren atazak.
- **Martxan** — Une honetan egiten ari diren atazak.
- **Eginda** — Amaitutako atazak.

Ataza bakoitzean gutxienez honako informazioa adierazi beharko da:

- Atazaren izena.
- Azalpen laburra.
- Arduraduna.
- Egoera.
- Hasiera-data.
- Amaiera-data.

> **Helburua:** taldeko edozein kidek Kanban taula begiratuta proiektuaren egoera ulertzeko gai izatea.

---

## 2. Gantt diagrama

Atazak definitu ondoren, proiektuaren **denbora-plangintza** egingo duzue.

GitHub Projects-en ikuspegi kronologikoa erabiliz, **Gantt diagrama** osatuko duzue.

Diagraman proiektuko ataza nagusiak agertu beharko dira, bakoitzaren:

- Hasiera-data.
- Amaiera-data.
- Iraupena.
- Atazen arteko ordena edo mendekotasunak.

Plangintza ez da behin bakarrik egin eta ahazteko dokumentu bat. Erronka garatzen den bitartean, beharrezkoa bada, **eguneratu egin beharko duzue benetako egoerara egokitzeko**.

---

## 3. GitHub repository-a

Talde bakoitzak repository bat erabiliko du erronkaren dokumentazioa gordetzeko.

Adibidez, honako egitura erabil dezakezue:

```text
asir1-erronka/
│
├── README.md
├── docs/
│   ├── index.md
│   ├── proiektua.md
│   ├── sarea.md
│   └── ondorioak.md
│
└── irudiak/
    └── ...
```

Repository-an egindako aldaketak **commit** bidez gordeko dira.

Commit-en mezuak argiak eta ulergarriak izan behar dira.

Adibidez:

```text
Hasierako web orria sortu
Sarearen eskema gehitu
Proiektuaren deskribapena eguneratu
Ondorioak gehitu
```

---

# 4. GitHub Pages: gure webgunea

Erronkan egindako lana aurkezteko **webgune estatiko sinple bat** sortuko duzue.

Ez dugu web zerbitzari propio bat instalatuko. Horren ordez, repository-an gordetako Markdown fitxategiak erabiliko ditugu eta **GitHub Pages** zerbitzuaren bidez argitaratuko ditugu.

Webgunearen hasierako orria `index.md` fitxategia izango da.

Adibidez:

```markdown
# Lurtek S.L. — Informatika-azpiegitura

## Proiektuari buruz

ASIR1eko lehen erronkan Lurtek S.L. enpresaren
informatika-azpiegitura diseinatu dugu.

## Gure proposamena

Proiektuan honako arlo hauek landu ditugu:

- Hardwarea
- Sistema eragileak
- Sare lokala
- Erabiltzaileen kudeaketa
- Proiektuaren planifikazioa

## Taldea

- Ane
- Jon
- Maialen
- Unai
```

GitHub Pages konfiguratu ondoren, repository-ko edukia Internet bidez eskuragarri egongo da webgune baten moduan.

---

## 5. Webgunearen gutxieneko edukia

Webguneak gutxienez honako atalak izan beharko ditu:

1. **Hasiera** — Proiektuaren aurkezpena.
2. **Enpresaren beharrak** — Hasierako egoeraren azalpena.
3. **Proposatutako azpiegitura** — Egindako diseinuaren laburpena.
4. **Proiektuaren antolaketa** — Taldeak lana nola antolatu duen.
5. **Ondorioak** — Proiektuaren amaierako balorazioa.

Markdown-en oinarrizko elementuak erabili beharko dituzue:

- Izenburuak eta azpiizenburuak.
- Paragrafoak.
- Zerrendak.
- Estekak.
- Irudiak.
- Taulak.
- Kode blokeak.

---

## 📦 Entregagaiak

Digitalizazioa atalaren amaieran honako elementuak egiaztatuko dira:

- GitHub repository-a behar bezala antolatuta dago.
- GitHub Projects proiektua sortuta dago.
- Atazak definituta eta taldekideen artean banatuta daude.
- Kanban taula eguneratuta dago.
- Gantt diagramak proiektuaren planifikazioa erakusten du.
- Commit-en bidez egindako lanaren bilakaera ikus daiteke.
- GitHub Pages aktibatuta dago.
- Webgune estatikoak erronkaren emaitza nagusiak aurkezten ditu.

> **Garrantzitsua:** azken emaitza bezain garrantzitsua izango da proiektuan zehar **nola antolatu, dokumentatu eta koordinatu duzuen lana**.
