# Ungry Mama

Ungry Mama è un programma che organizza automaticamente i file in una cartella selezionata dall'utente, creando sottocartelle per immagini, video, documenti, archivi, eseguibili, musica e altro. Questo programma è stato creato da Fabio Bracciali (elblasco01) con l'assistenza di ChatGPT (OpenAI).

## Utilizzo del Programma

### Come Avviare il Programma

1. Scarica l'eseguibile `ungrymama.exe` dal repository.
2. Esegui il file `ungrymama.exe`.
3. Si aprirà una GUI dove potrai selezionare la cartella da organizzare.
4. Conferma l'operazione nella finestra di dialogo che apparirà.

### Organizzazione dei File

#### Cartella Generica

Quando selezioni una cartella generica, il programma crea le seguenti sottocartelle e sposta i file nei rispettivi luoghi:

- `Immagini e Video`
  - `Immagini`: .png, .jpg, .jpeg, .gif, .bmp, .webp
  - `Video`: .mp4, .avi, .mov, .wmv, .ts, .mkv
- `Documenti`
  - `Word`: .doc, .docx, .txt, .dot, .dotx, .odt
  - `PDF`: .pdf, .p7m
  - `XML`: .xml
  - `Excel`: .xls, .xlsx, .csv, .ods
  - `PowerPoint`: .ppt, .pptx, .odp
  - `Publisher`: .pub
  - `eBook`: .epub, .mobi, .azw
- `Archivi`: .zip, .rar, .7z, .tar, .gz
- `Eseguibili`: .exe
- `Musica`: .mp3, .wav, .flac, .aac, .ogg, .m4a
- `Font TrueType`: .ttf

#### Cartella Desktop

Quando selezioni il Desktop come cartella da organizzare, il programma:

- Esclude i file di collegamento a programmi o applicazioni.
- Esclude le icone di sistema (Cestino, Risorse, etc).
- Crea una cartella chiamata `Ungry Mama` sul Desktop contenente la stessa organizzazione detta sopra.

## Riconoscimenti

Questo programma è stato creato da Fabio Bracciali (f.bracciali@gmail.com) con l'assistenza di ChatGPT (OpenAI).

## Licenza

Questo software è distribuito sotto la licenza MIT. Consulta il file [LICENSE](./LICENSE) per maggiori dettagli.
