# LEGA: LEVANDA, trys variantai

Siuntimui 2026 m. spalio 6 d. GitHub paketas Omnisend importui, laiškas neišsiųstas.

GitHub aplankas: https://github.com/elaiskai/lega-email-assets/tree/main/campaigns/c44-levanda-three-ways

Importuoti `newsletter.html`. Nuotraukų adresai absoliutūs ir veda į šio aplanko assets. 2026 m. spalio 5 d. dar kartą patikrinta: LEVANDA L negalimas, S, M, XL, XXL ir 3XL galimi. Galutinio HTML desktop 600 px ir mobile 320, 390, 430 px peržiūros patikrintos su stiliais ir be head stilių bei šriftų nuorodų.

Tema: Vieni marškiniai, keli būdai dėvėti

## Telefono pataisymas, 2026 m. spalio 5 d.

Pagal pateiktą Gmail testo ekrano kopiją pataisytas per siauras hero tekstas. Kompaktiškas pilno pločio tekstas dabar yra bazinis inline variantas, todėl jam nereikia media taisyklių. Desktop dviejų stulpelių hero taikomas tik per desktop stilius. Patikrinta 11 šviežių variantų, įskaitant pašalintus head stilius ir papildomas 16 px paraštes telefone. Nuotraukos patikrintos naudojant gyvus GitHub adresus. Ankstesnis Omnisend importas automatiškai neatsinaujina: reikia iš naujo importuoti newsletter.html ir atsiųsti naują tikro telefono testo ekrano kopiją. Gmail rezultatas dar nepatvirtintas.

Trys realiais originaliais kadrais pagrįsti variantai: laisvai su KAVA, su dirželiu ir KAVA, su dirželiu ir VERBENA. Atsegtų marškinių kadro produkto galerijoje nėra, todėl šios anksčiau pasiūlytos idėjos atsisakyta. Modeliai ir apranga negeneruoti, nuotraukos tik sumažintos išlaikant originalų santykį.

## Šaltiniai ir patikra

Patikrinta 2026 m. spalio 4 d. Oficialūs Shopify produktų JSON išsaugoti research kataloge.

* https://lega.lt/products/marskiniai-levanda-alyvuogiu-chaki
* https://lega.lt/products/placios-kelnes-kava-alyvuogiu-chaki
* https://lega.lt/products/sijonas-verbena-alyvuogiu-chaki

LEVANDA aprašymas patvirtina tiesų prailgintą siluetą, neprisiūtą dirželį, matinį trikotažo paviršių ir derinimą su KAVA bei VERBENA. Sudėtis 45 % liocelio, 50 % poliesterio, 5 % elastano. Laiške nėra teiginio apie gryną ar 100 % natūralų liocelį. Puslapio SEO title klaidingai mini NIDA, tačiau H1, produkto JSON, nuotraukos ir aprašymas atitinka LEVANDA.

Patikros metu LEVANDA L dydis ir KAVA S dydis nebuvo galimi. Papildomai patikrintas `levanda-current.json`: S, M, XL, XXL ir 3XL galimi, L negalimas. V2 laiške faktinis priminimas „L dydis jau išparduotas“ ir raginimas rinktis, kol yra savas dydis. Nėra teiginių apie pardavimo greitį, mažus vienetų likučius, papildymo nebuvimą ar ribotą laiką. Prieš siuntimą šį priminimą būtina patikrinti iš naujo.

V2 hero pakeistas iš dviejų modelių palyginimo į asimetrišką kakavos spalvos viršelį su viena originalia sėdinčio modelio nuotrauka. Palyginimas perkeltas į laiško vidų. Mobilus viršelis susideda į vieną stulpelį, o vaizdas išlaiko natūralias proporcijas.

V3 prieš paskutinį LEVANDOS mygtuką pridėta tiksli Violetos citata iš oficialaus LEVANDOS produkto puslapio: „Puikus marškinių modelis 👏 Ačiū jums labai !“. Puslapyje tikrinant matytas vienas atsiliepimas. Žvaigždučių, patvirtinto pirkimo žymos ar apibendrinimo apie visas klientes nepridėta. Autorės nuoroda veda į tą patį produktą.

Vizualinė kryptis iš esamų LEGA kampanijų: bronzinė logotipo juosta, šiltas dramblio kaulo fonas, Outfit tekstas, Didot / Georgia antraštės. Realus LEGA logotipas iš ankstesnės patvirtintos kampanijos. Spalvos priklauso maketo sistemai, ne naujam oficialiam brand guide.

## Prieš siuntimą

1. Dar kartą patikrinti dydžių likučius.
2. Patikrinti, kad Omnisend importavo visas viešais adresais pateiktas nuotraukas.
3. Patvirtinti platformos atsisakymo žymą.
4. Išsiųsti Omnisend testą ir patikrinti tikrame telefone. Naršyklės QA nėra Gmail ar Omnisend pristatymo patvirtinimas.

`qa.json` sieja automatines patikras su tiksliu HTML SHA256. Vizualinė peržiūra įrašoma atskirai į `qa-visual.json`. JPG yra visas laiškas.
