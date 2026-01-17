Custom HTML Workout Engine & Translator

A lightweight, high-performance HTML markup generator designed to bridge the gap between visual editing and clean, production-ready code. Unlike standard WYSIWYG editors, this tool acts as a translator, converting user input into a specific, class-based HTML structure optimized for coaching platforms, CMS, and performance databases.
💡 The Core Logic

The engine is built on top of the contentEditable API but bypasses its default messy behavior. It enforces a strict CSS-class-based styling system, ensuring that the generated HTML remains consistent, portable, and free of inline-style "pollution."
🚀 Advanced Technical Features
🧬 Granular DOM Manipulation

The editor implements custom logic to handle complex text selections:

    splitTextNode: Precisely splits text nodes at selection boundaries to apply styles without corrupting the surrounding DOM tree.

    applyColorClass: A recursive function that flushes existing formatting classes before applying new ones, preventing infinite <span> nesting.

    resetColor: An extraction algorithm that strips formatting while preserving text integrity.

📊 Structured Table Generator

A dedicated module to create HTML tables with dynamic row/column parameters, specifically designed for displaying training protocols, interval sets, and performance data.
🛠️ Usage for Performance Scientists

This tool is ideal for developers and trainers who need to:

    Generate clean HTML for workout descriptions.

    Maintain a unified design system by mapping UI actions to predefined CSS classes (e.g., .text-red for high-intensity zones).

    Inject structured content into external databases without manual sanitization.

📄 License

This project is licensed under the MIT License.
🇮🇹 Versione Italiana
Custom HTML Workout Engine & Translator

Un generatore di markup HTML leggero e ad alte prestazioni, progettato per colmare il divario tra l'editing visuale e un codice pulito pronto per la produzione. A differenza dei comuni editor WYSIWYG, questo strumento funge da vero e proprio traduttore, convertendo l'input dell'utente in una struttura HTML basata su classi, ottimizzata per piattaforme di coaching, CMS e database di performance.
💡 La Logica Centrale

Il motore è costruito sull'API contentEditable, ma ne evita i tipici output disordinati. Impone un sistema di stile rigoroso basato su classi CSS, garantendo che l'HTML generato rimanga coerente, portabile e privo di stili inline superflui.
🚀 Caratteristiche Tecniche Avanzate
🧬 Manipolazione Granulare del DOM

L'editor implementa una logica personalizzata per gestire selezioni di testo complesse:

    splitTextNode: Divide con precisione i nodi di testo ai confini della selezione per applicare stili senza corrompere l'albero DOM circostante.

    applyColorClass: Una funzione ricorsiva che pulisce le classi di formattazione esistenti prima di applicarne di nuove, evitando la nidificazione infinita di tag <span>.

    resetColor: Un algoritmo di estrazione che rimuove la formattazione preservando l'integrità del testo.

📊 Generatore di Tabelle Strutturate

Un modulo dedicato per creare tabelle HTML con parametri dinamici di righe/colonne, specificamente progettato per visualizzare protocolli di allenamento, serie di intervalli e dati di performance.
🛠️ Casi d'Uso per Esperti di Performance

Questo strumento è ideale per sviluppatori e trainer che hanno bisogno di:

    Generare HTML pulito per le descrizioni dei workout.

    Mantenere un design system unificato mappando le azioni dell'interfaccia a classi CSS predefinite (es. .text-red per le zone ad alta intensità).

    Iniettare contenuti strutturati in database esterni senza necessità di pulizia manuale.

📄 Licenza

Questo progetto è distribuito sotto licenza MIT.