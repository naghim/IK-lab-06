# Labor 06

# Gyakori elemhalmazok előállítása (FP-Growth algoritmus)

## FP-Growth algoritmus

Ebben a laborban a FP-Growth algoritmust vizsgáljuk meg, amely hatékonyabb megoldást kínál a gyakori elemhalmazok kinyerésére, mint az Apriori algoritmus. Az FP-Growth a Frequent Pattern Tree (FP-Tree) adatszerkezetet használja, amely lehetővé teszi, hogy elkerüljük a nagyszámú kandidátushalmaz előállítását, ezzel javítva a számítási teljesítményt, különösen nagy adatbázisok esetén.

Az FP-Growth algoritmus két fő lépésből áll:

1. FP-Tree (Frequent Pattern Tree) felépítése
2. Rekurzív gyakori elemhalmaz keresés az FP-Tree-ben

Az FP-Tree egy kompakt, fa alapú adatszerkezet, amely az input tranzakciós adatokat hatékonyan tárolja. Ahelyett, hogy a teljes tranzakciós halmazt több lépésben újraszámolná (mint az Apriori), az FP-Tree csoportosítja az azonos prefixeket egy tömörített szerkezetbe.

---

A labor során az FP-Growth algoritmus Python implementációját próbáljuk ki, és összehasonlítjuk a teljesítményét más algoritmusokkal, például az Apriori módszerrel.

# Feladatok

1. Nyissuk meg a laborhoz tartozó Jupyter Notebook (`.ipynb`) fájlt. Ismerkedjünk meg az FP-Growth algoritmus működésével és annak implementációjával.
2. Futtassuk a notebookban található kódokat, és elemezzük az eredményeket.
3. Hasonlítsuk össze az FP-Growth és az Apriori algoritmus futási idejét és hatékonyságát különböző adathalmazokon.

A laboróra végén mentsük el a módosított jegyzetfüzetet, és töltsük fel a GitHubra.
