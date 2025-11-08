# wishlist-galore 🇮🇹

In questo repository conservo le mie liste della spesa

## Lista della Spesa dall'Italia

Una bellissima applicazione single-page, mobile-first, per visualizzare cosa portare (e cosa NON portare) dall'Italia.

### Funzionalità

- 📱 **Design Mobile-First**: Completamente responsive e ottimizzato per tutti i dispositivi
- 🎨 **UI Moderna**: Bellissimo sfondo sfumato con layout a card
- ✨ **Animazioni Fluide**: Animazioni sottili usando Animate.css
- 🔄 **Contenuto Dinamico**: Elementi caricati da file JSON esterni
- 🎯 **Icone Font Awesome**: Icone visive per ogni elemento
- 🔗 **Link Esterni**: Link diretti per maggiori informazioni su ogni elemento
- ✅ **Liste Doppie**: Due liste separate - una per cosa portare e una per cosa NON portare
- 💾 **Persistenza Locale**: Le checkbox salvano automaticamente il loro stato in localStorage
- 🎯 **Navigazione a Tab**: Interfaccia intuitiva per passare tra le due liste

### Come Usare

1. Apri `index.html` in un browser web
2. Gli elementi sono caricati automaticamente da `items.json` e `items-not-to-bring.json`
3. Usa le tab per passare tra "Da Portare" e "Da NON Portare"
4. Spunta le checkbox per marcare gli elementi - lo stato viene salvato automaticamente

### Come Aggiornare gli Elementi

Modifica i file `items.json` o `items-not-to-bring.json` per aggiungere, rimuovere o modificare elementi. Ogni elemento segue questa struttura:

```json
{
  "name": "Nome Elemento",
  "description": "Descrizione dell'elemento in qualsiasi lingua",
  "icon": "fa-solid fa-icon-name",
  "link": "https://example.com"
}
```

**Trovare Icone Font Awesome:**
Sfoglia le icone disponibili su [Font Awesome](https://fontawesome.com/icons) e usa il nome della classe (es. `fa-solid fa-heart`)

### Tecnologie Usate

- **Bootstrap 5.3.2**: Griglia responsive e utilità
- **Font Awesome 6.4.2**: Libreria di icone
- **Animate.css**: Libreria di animazioni
- **Google Fonts (Poppins)**: Tipografia
- **Vanilla JavaScript**: Caricamento dinamico del contenuto e gestione localStorage
