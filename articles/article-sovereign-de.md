# Dein Smartphone spioniert dich aus – und längst geht es nicht mehr um die Taschenlampe

*Vor einem Jahr habe ich die Einstellungen meines Smartphones geöffnet und durch die App-Liste gescrollt. Und mir wurde schlagartig klar: Nicht ich benutze diese Apps – sie benutzen mich. Das hier ist, was ich dagegen getan habe.*

## Die Überwachung, die du nie zu sehen bekommst

Das klassische Beispiel ist eine Taschenlampen-App, die aus irgendeinem Grund deinen Standort und die Karte deiner WLAN-Netze wissen will. Aber seien wir ehrlich: **Nicht jede Taschenlampe spioniert, und nicht auf jedem Gerät.** Um ein bestimmtes Icon geht es schon lange nicht mehr.

Bis 2026 haben Hersteller und Werbenetzwerke etwas viel Subtileres gelernt. Das Datensammeln ist in **unsichtbare System-Apps und Hintergrunddienste gewandert – viele davon haben nicht einmal ein Icon auf deinem Startbildschirm.** Du weißt nichts von ihnen, du hast sie nie geöffnet, und löschen kannst du sie auch nicht. Trotzdem ernten sie klammheimlich deinen Standort, die Karte der Geräte um dich herum, deine Kennungen, das Muster deiner Bewegungen. Daraus entsteht ein digitales Modell von dir – eines, dem du nie zugestimmt hast – und es liegt nicht in deiner Tasche, sondern auf fremden Servern.

Wir nehmen das hin wie das Wetter. Aber ein Gedanke hat sich bei mir festgesetzt. In einer Küche gilt eine eiserne Regel: Rohes Fleisch teilt sich kein Brett mit gegartem Essen. Das ist keine Paranoia – das ist Hygiene. In der digitalen Welt haben wir alles auf ein einziges Brett geworfen: Behördengänge, Banking, private Nachrichten, Fotos unserer Kinder, die Krypto-Wallet. Jede App kann potenziell ihren Nachbarn mitlesen. Die digitale Welt hat die Hygiene vergessen. Ich habe beschlossen, sie zurückzubringen.

## Warum Virenscanner und „Inkognito" dich nicht retten

Der erste Reflex ist ein Virenscanner oder der Inkognito-Modus. Funktioniert nicht. Ein Virenscanner fängt Viren – nicht das legale Datensammeln, dem du selbst auf „Erlauben" getippt hast. Der Inkognito-Modus verbirgt deinen Verlauf vor deiner Familie, nicht vor den Websites.

Der zweite Gedanke – „dann werfe ich die Apps eben raus". Auch daneben. Versuch mal, 2026 ohne Banking-App, Behörden-Apps und Online-Marktplatz zu leben. Das ist keine Freiheit, das ist Selbstverbannung aus der Realität.

Der dritte – Custom-ROMs und Root. Das funktioniert, ist aber ein Weg für 0,1 % der Nerds. Ein normaler Mensch flasht sein Handy nicht neu und setzt dafür die Garantie aufs Spiel. Ich wollte eine Lösung für normale Menschen: **Jede App soll ganz normal weiterlaufen – aber sie sollen einander nicht mehr sehen können. Ohne Root. Auf dem Handy, das du schon in der Tasche hast.**

## Drei Identitäten in einem Smartphone

So ist **Sovereign** entstanden – eine App, die ein Smartphone in drei voneinander isolierte Räume aufteilt.

**Bürger.** Die nach außen gewandte Seite: Behörden-Apps, Banken, Marktplätze und Massen-Messenger wie WhatsApp und Telegram. Alles funktioniert in vollem Umfang. Der Staat sieht einen ganz gewöhnlichen Bürger mit einem ganz gewöhnlichen Telefon. Sovereign zeigt dir dabei einfach, was diese Apps tun.

**Mensch.** Dein Privatleben. Messenger für vertrauliche Gespräche (etwa Signal), Krypto-Wallets, Torrent-Knoten, persönliche Fotos und Mails. Eigener Speicher, eigene Schlüssel. Der Bürger kann von hier keine einzige Datei lesen.

**Souverän.** Eine verschlüsselte Enklave für das, was am meisten zählt. Sie taucht in der App-Liste nicht auf. Bei einer gewöhnlichen Kontrolle des Telefons gibt es hier schlicht nichts zu öffnen.

Der entscheidende Punkt: Das hier ist **keine Sandbox und kein Klon.** Die Isolation läuft auf Betriebssystem-Ebene – über Standard-Android-Mechanismen (Arbeitsprofil und Enklave). Deshalb ist **kein Root** nötig, kein Custom-ROM. Es installiert sich wie eine ganz normale App.

## Was drinsteckt

Ich verstecke die Funktionen nicht hinter schwammigen Worten – hier ist, was v1.0 tatsächlich kann:

- **Sovereign X-Ray** – ein Röntgenbild der Überwachung. Eine Live-Karte, welche App gerade welche Daten wohin sendet, in Echtzeit. Du siehst den „unsichtbaren" Dienst, der die Analytik anpingt, und die Bank, die selbst im Sperrzustand Dutzende Anfragen pro Stunde abfeuert. Dazu ein wöchentlicher Bericht in Klartext.
- **Sovereign Compass** – eine Bedrohungsampel auf einen Blick: grün / gelb / rot in der Statusleiste, gespeist aus der Analyse hunderter Signale direkt auf dem Gerät. Ganz ohne Internet.
- **Verschlüsselter Tresor mit Post-Quanten-Schutz** – das Hardware-Modul von Android plus die Algorithmen Kyber und Dilithium über AES. Ehrlich gesagt: Der Post-Quanten-Teil schützt den Schlüssel – gegen „Store now, decrypt later"-Angriffe.
- **Sovereign Whisper** – eine KI, die offline läuft, direkt auf dem Telefon: übersetzen, zusammenfassen, deinen Tresor durchsuchen. Ohne ein einziges ausgehendes Paket in die Cloud.
- **The Veil** – ein verborgener Tresor. Im verschleierten Zustand gibt es keinen sichtbaren Tresor – keinen Ordner, kein Icon. Dazu eine Notfall-Löschung: Gib ein Täuschungspasswort ein, und es öffnet sich nur eine leere Hülle.
- **Mesh, Air Gap, eigener DNS** – Dateiübertragung von Telefon zu Telefon ohne Server, ein Profil vollständig vom Netz trennen, Netzwerkverkehr isolieren.

## Ehrlich gesagt: Was Sovereign NICHT tut

Mit „absolutem Schutz" zu werben ist eine Lüge, und die verkaufe ich nicht. Sovereign ist digitale Hygiene, **kein Tarnumhang gegen staatliche Behörden.**

Der verborgene Tresor bietet glaubhafte Abstreitbarkeit auf **Alltagsebene** – echten Schutz gegen jemanden, der dein Handy in die Hand nimmt, aber keine mathematische Garantie gegen ein forensisches Labor des Staates. Ohne Root setzt das Betriebssystem Grenzen, und ich umgehe sie nicht und verspreche das auch nicht. Mein Ziel ist einfacher und ehrlicher: den Staat und die Banken von deinem Privatleben zu trennen, so wie eine Küche Rohes von Gegartem trennt.

## Warum solo

Ich habe kein Team und keine Finanzierungsrunde. Ich habe ein Telefon, einen Laptop und Sturheit. Jede Funktion habe ich selbst geschrieben und getestet, auf einem echten Gerät. Das ist langsam und mühsam – aber die Solo-Entwicklung hat einen Vorteil: **Es gibt niemanden, an den ich deine Daten verkaufen könnte.** Die App hat keine Cloud, keine Server, kein Abo. Sie kann nicht lecken – sie hat kein Wohin.

In Deutschland gibt es für diesen Gedanken sogar einen eigenen Begriff: **informationelle Selbstbestimmung** – das Recht, selbst zu entscheiden, wer was über dich weiß. Sovereign ist mein Versuch, dieses Recht in eine App zu gießen.

Daher die Philosophie, die ich in das Projekt eingebaut habe: **Du bist ein Subjekt, keine Funktion.** Ein Werkzeug soll für dich arbeiten, nicht du für das Werkzeug.

## So kannst du es ausprobieren

Sovereign ist fertig, getestet und als installierbare **.apk** verpackt. Die Lizenz gilt einmalig und lebenslang, keine Abos. Bezahlung in USDT/USDC; nach der Zahlung kommen dein Schlüssel, der Download-Link und das vollständige Handbuch per E-Mail.

- **Sovereign-Seite (Demo & Kauf):** https://s0vereign.pw/sovereign.html
- **Demo auf YouTube ansehen:** https://youtu.be/cvy4_lwi-TI

## Das Ökosystem

Sovereign ist Teil des digitalen Ökosystems des Solo-Entwicklers **Vladislav Shter**:

- **Sovereign** – Schutz persönlicher Daten auf deinem Telefon (dieser Artikel).
- **Egregor** – ein Desktop-Multi-KI-Konsilium, **bereits im Verkauf.**
- **SovereignWeb3 Browser** – ein einzigartiger Web3-Browser, **in Kürze verfügbar.**
- **SovereignBank-Web3** – nicht-verwahrendes On-Chain-Banking.

Links:

- Ökosystem-Website – https://s0vereign.pw/
- GitHub – https://github.com/VladislavShter/SOVEREIGN
- GitVerse (Mirror) – https://gitverse.ru/wadyas/SOVEREIGN
- SovereignBank-Web3 – https://github.com/VladislavShter/SovereignBank-Web3
- Demo – https://youtu.be/cvy4_lwi-TI

*Solo erschaffen, dem Unausweichlichen zum Trotz. — Vladislav Shter*
