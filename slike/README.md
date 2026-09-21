# Snježni Vrh – restoran i smještaj

Web stranica izrađena za projekt iz multimedije. Tema je zimski restoran i smještaj u Alpama.
Stranica je napravljena u HTML-u i CSS-u i objavljena preko GitHuba i Netlifyja.

## Opis koraka izrade

### tekst (HTML/CSS)

Stranicu sam radio u VS Codeu u HTML-u i CSS-u, bez nekih gotovih predložaka jer sam htio sam napisati kod. Naslove sam stavio u `<h1>` i `<h2>`, tekst u `<p>`, a jela i kontakt podatke u liste. Za cjenik sam napravio tablicu da izgleda uredno. Boje i izgled sam onda namjestio u `style.css` – sve u plavim tonovima da paše uz logo. Izbornik gore skače na dijelove stranice, tako da je sve na jednoj stranici.

### slika (GIMP + galerija)

Skinuo sam četiri besplatne fotke s Pexelsa (restoran, soba, snijeg, hrana). Svaku sam otvorio u GIMP-u, smanjio na 800 px širine da se brže učitava, malo izrezao rubove i preko Brightness-Contrast i Hue-Saturation namjestio boje da izgleda toplije. Spremio sam ih kao JPG i ubacio u mapu „slike". Galeriju sam onda složio u HTML-u tako da su sve slike poredane, a u CSS-u sam im dao istu veličinu i plavi obrub.

### grafika (Illustrator – SVG)

Logo sam sam napravio u Illustratoru kao jednostavan SVG vektor – dvije planine sa snježnim vrhovima. Crtao sam ih od osnovnih oblika i namjestio boje da paše uz plave tonove stranice. Spremio sam ga kao SVG jer ostaje oštar na svakoj veličini i onda ga ubacio u zaglavlje pored naslova preko `<img>` taga i namjestio veličinu.

### zvuk (Audacity)

Htio sam dočarati ugođaj mirne zimske večeri. Skinuo sam par besplatnih zvukova – zimsku oluju, pucketanje peći i kravlja zvona – i složio ih u Audacityju jedan preko drugog kao zasebne trake. Namjestio sam glasnoću da bude mirno i ugodno, skratio zapis i dodao Fade In i Fade Out. Izvezao sam ga kao MP3 i stavio u zaglavlje stranice da se odmah može poslušati.

### video (Shotcut)

Video sam napravio u Shotcutu od pet besplatnih zimskih isječaka – planine, restoran, soba i skijanje. Poslagao sam ih na timeline jedan za drugim i između njih dodao prijelaze da lijepo teče. Ostavio sam ga bez zvuka jer stranica već ima zvučni ugođaj. Na kraju sam ga izvezao kao MP4 i stavio na stranicu.
