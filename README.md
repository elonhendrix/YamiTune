# YamiTune 0.3.0

YamiTune 0.3.0 - Windows x64 VST3

Zatvori FL Studio pre instalacije. Pokreni YamiTune-0.3.0-Setup.exe i prati korake.
Installer postavlja ceo plugin u standardni Windows VST3 folder i, ako je potrebno,
instalira ukljuceni zvanicni Microsoft Visual C++ x64 Runtime.

U FL-u: Options > Manage plugins > Find installed plugins. Dodaj YamiTune na
mixer insert sa jednim vokalom. Proveri oznaku 0.3.0 u editoru.
Izaberi tonalitet i skalu svoje pesme. Retune Speed: 0-400 ms; Humanize: 0-100%.

Podrzano: Windows 10/11 x64, VST3, mono/stereo, 44.1/48/88.2/96 kHz, float32.
Ovo je Studio engine sa 60 ms plugin latencije. Preporucen pocetni buffer: 256+.
Obezbedi prostor za izlazne vrhove; plugin nema limiter. Eksperimentalni build.
Live mode nije deo 0.3.0. Nije potrebna instalacija Antares ili Waves plugina.

Deinstalacija: Windows Settings > Apps > Installed apps > YamiTune 0.3.0.
Microsoft runtime je zajednicka komponenta i ne uklanja se sa pluginom.

Za prijavu problema navedi Windows/DAW verziju, sample rate, buffer,
Retune/Humanize/Key/Scale i da li se problem cuje u eksportovanom zvuku.
Repo i Releases sadrze distribuciju i uputstvo; izvorni kod nije objavljen.
Licence ukljucenih zavisnosti nalaze se u folderu licenses.

Installer za testiranje nije digitalno potpisan. Izvorni kod nije objavljen.
GitHub automatski nudi Source code ZIP/TAR arhive repoa: one sadrze samo
ovo uputstvo i licence, ne implementaciju plugina.
