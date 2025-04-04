# ✨ Phrase Forge ✨ - El Teu Forjador de Frases Personal!

Benvingut/da a **Phrase Forge**! 🧙‍♂️💨 Cansat/da de mirar una pàgina en blanc? Necessites un impuls creatiu? Aquesta petita aplicació web és aquí per ajudar-te a forjar textos increïbles amb el poder de la intel·ligència artificial! 🤖✍️

## 🤔 Com Funciona Aquesta Màgia?

Phrase Forge és com tenir un aprenent d'escriptor molt llest (i digital) al teu servei. Tu li dones les ordres i ell... voilà! Crea text. Aquí teniu el procés pas a pas:

1.  **🔑 El Secret Més Ben Guardat (La Clau API):**
    * Phrase Forge utilitza l'[API d'OpenRouter](https://openrouter.ai/) per accedir a models d'IA potents.
    * **MOLT IMPORTANT:** Perquè funcioni, **necessites la teva pròpia clau API d'OpenRouter**. Pots aconseguir-ne una gratuïtament (amb límits d'ús) a [OpenRouter Keys](https://openrouter.ai/keys).
    * Enganxa la teva clau (hauria de començar per `sk-or-v1-...`) a la secció "OpenRouter API Key" i fes clic a "Save Key".
    * 🔒 **Tranquil/a!** La teva clau es desa **només** al teu navegador (utilitzant `localStorage`). No s'envia a cap altre lloc ni es comparteix. Si esborres les dades del navegador o fas clic a "Clear Key", desapareixerà.

2.  **✍️ Dóna les Instruccions al Forjador:**
    * **Enter Your Prompt:** Aquí escrius la teva idea principal. Què vols que l'IA escrigui? Sigues tan específic/a o general com vulguis! (p. ex., "Escriu un poema sobre un gat astronauta").
    * **Writing Style:** Tria l'estil que més t'agradi (Formal, Informal, Narratiu, etc.).
    * **Language:** Selecciona l'idioma en què vols el text resultant.
    * **Length Slider:** Ajusta la barra lliscant per indicar la llargada aproximada (en paraules) que vols per a la *propera* generació de text.

3.  **🚀 Forja! (Generate & Append Text):**
    * Un cop tinguis la clau desada i les instruccions a punt, fes clic a aquest botó!
    * L'aplicació enviarà la teva petició a l'IA (a través d'OpenRouter).
    * ⏳ Tingues una mica de paciència mentre l'IA "forja" el text... Veureu un indicador de "Generating...".
    * El text resultant s'afegirà a la "Result Area" de sota. Si ja hi havia text, el nou s'afegirà al final, separat per `---`.

4.  **📜 La Teva Creació (Result Area):**
    * Aquí s'acumula tot el text que has generat.
    * **Export as .txt:** Descarrega tot el contingut de l'àrea de resultats com un fitxer de text simple.
    * **Clear:** Esborra tot el text de l'àrea de resultats. Compte, no es pot desfer!

## 📚 L'Historial del Forjador (Generation History)

Cada cop que generes un text amb èxit, es desa una "instantània" a l'historial:

* Veureu una llista de les vostres generacions anteriors, amb un trosset del prompt i del resultat.
* **Fes clic** en un element de l'historial per:
    * Recarregar la configuració (prompt, estil, idioma, llargada) que vas utilitzar per a aquella generació.
    * **SOBREESCRIURE** l'àrea de resultats amb el text *específic* d'aquella generació històrica (ideal per recuperar un text concret).
* L'historial també es desa al teu navegador (`localStorage`) i té un límit (actualment, els últims 20 elements).
* **Clear History:** Esborra tot l'historial de generacions. Compte, tampoc es pot desfer!

## 🛠️ Detalls Tècnics (Per als Curiosos)

* És una aplicació web **100% client-side**: Tot el codi (HTML, CSS, JavaScript) s'executa directament al teu navegador. No hi ha cap servidor nostre pel mig (excepte l'API d'OpenRouter, és clar).
* **Model d'IA per defecte:** Utilitza `mistralai/mistral-7b-instruct:free` d'OpenRouter (un model potent i gratuït!).
* **Emmagatzematge:** Fa servir `localStorage` del navegador per desar la teva clau API (si la proporciones) i l'historial de generacions per a la teva comoditat.

## 🚀 Com Utilitzar-la

* **Localment:**
    1.  Descarrega el fitxer `PhraseForge.htm`.
    2.  Obre'l amb el teu navegador web preferit.
    3.  Introdueix la teva clau API d'OpenRouter quan se't demani.
    4.  Comença a forjar!
* **A GitHub Pages:**
    1.  Simplement visita l'URL: `https://<el-teu-usuari>.github.io/<el-teu-repositori>/PhraseForge.htm` (substitueix `<el-teu-usuari>` i `<el-teu-repositori>`!)
    2.  Introdueix la teva clau API d'OpenRouter quan se't demani.
    3.  Deixa anar la teva creativitat!

---

Esperem que gaudeixis forjant frases i textos amb Phrase Forge! 🎉
