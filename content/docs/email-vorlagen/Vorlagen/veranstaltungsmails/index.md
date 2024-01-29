---
title: Veranstaltungsmails
weight: 1
next: /docs/email-vorlagen/vorlagen/rechnungsmails
prev: /docs/email-vorlagen/vorlagen/
---

## Mails an die Angemeldeten einer Veranstaltung

### Angemeldete/r bestätigt

#### Teilnehmende

Filter, Anhänge und Hinweise:

- Filter ⚙: `Teilnehmerart` ist `Teilnehmer`
- Anhänge 🔗:  [📄 Anmeldebestätigung TN mit Anzahlung](/docs/dokument-vorlagen/#Anmeldebestaetigung-TN-mit-Anzahlung)
- Bemerkung 💡: Wenn eine Veranstaltung keine (!) Anzahlung enthält muss die VOrlage lokal in der Veranstaltung überschrieben werden mit angepasstem Wortlaut.

Betreff:

```
Anmeldebestätigung für $VERANSTALTUNGSNAME$
```

E-Mail-Vorschautext:

```
$BRIEFANREDE_DU$, herzlichen Glückwunsch, du bist dabei!
```

E-Mail-Text:

```
Bestätigung der Anmeldung für $VORNAME$ $NACHNAME$: Angebotsnummer $ANGEBOTSNUMMER$: „$VERANSTALTUNGSNAME$“
---
Wir haben deine Anmeldung zu „$VERANSTALTUNGSNAME$“ in $VERANSTALTUNGSORT$ vom $VERANSTALTUNGSBEGINN_LANG$ bis $VERANSTALTUNGSENDE_LANG$ erhalten und bestätigen hiermit die Teilnahme. Damit ist gemäß unseren Reisebedingungen der Reisevertrag zustande gekommen.

Anbei findest du die ausführliche Anmeldebestätigung sowie weitere, wichtige Hinweise. Bitte lies dir diese aufmerksam durch.

Die beiden Rechnungen für die Freizeit (1x Anzahlung, 1x Restbetrag) versenden wir gesondert von dieser Bestätigung an den angegebenen Rechnungsempfänger.

Spätestens drei Wochen vor Beginn der Freizeit bekommst du einen
ausführlichen Informationsbrief. Für weitere Fragen stehen wir natürlich
gerne zur Verfügung. In $ANZAHL_TAGE_BIS_VERANSTALTUNG$ Tagen geht’s los!

PS: Falls du sowohl Teilnehmende:r als auch Kontaktperson/Rechnungsempfänger:in bist erhältst du ggf. mehrere E-Mails. Das ist beabsichtigt und kein Fehler 👍
```

<details>
  <summary>🖥 Vorschau</summary>
  
  ![Vorschau-Bild E-Mail-Vorlage](veranstaltung_anmeldungen_bestaetigung_tn.png)

</details>

---

#### Betreuende

Filter, Anhänge und Hinweise:

- Filter ⚙: `Teilnehmerart` ist `Betreuer`
- Anhänge 🔗: - / -
- Bemerkung 💡: - / -

Betreff:

```
Anmeldebestätigung für $VERANSTALTUNGSNAME$
```

E-Mail-Vorschautext:

```
$BRIEFANREDE_DU$, herzlichen Glückwunsch, du bist als Mitarbeiter dabei!
```

E-Mail-Text:

```
Bestätigung der Mitarbeiter-Anmeldung für $VORNAME$ $NACHNAME$: Angebotsnummer $ANGEBOTSNUMMER$: „$VERANSTALTUNGSNAME$“
---
$BRIEFANREDE_DU$,
herzlichen Glückwunsch, du bist als Mitarbeiter dabei! Wir sind sehr dankbar, dass du uns unterstützt!

Wir haben deine Anmeldung zu „$VERANSTALTUNGSNAME$“ vom $VERANSTALTUNGSBEGINN_LANG$ bis $VERANSTALTUNGSENDE_LANG$ erhalten und bestätigen hiermit die Teilnahme. Wir haben dich im Team $BETREUERFUNKTION$ zugeordnet.

Weitere Informationen zum Ablauf und der Vorbereitung erhältst du in der Regel direkt von der Freizeitleitung. Für weitere Fragen stehen wir natürlich
gerne zur Verfügung. In $ANZAHL_TAGE_BIS_VERANSTALTUNG$ Tagen geht’s los!

PS: Falls du sowohl Mitarbeitende:r als auch Kontaktperson bist erhältst du ggf. mehrere E-Mails. Das ist beabsichtigt und kein Fehler 👍 
```

<details>
  <summary>🖥 Vorschau</summary>
  
  ![Vorschau-Bild E-Mail-Vorlage](veranstaltung_anmeldungen_bestaetigung_ma.png)

</details>

### Angemeldete/r storniert

- Filter ⚙: - / -
- Anhänge 🔗: - / -
- Bemerkung 💡: Da die Meldung über die Stornierung **nur** an die Teilnehmenden geht setzen wir hier die E-Mail-Adresse der Kontaktperson in CC, damit auch diese (i.d.R. Eltern) informiert werden.
- CC: `$ANMELDUNG_E-MAIL$`

Betreff:

```
Stornierung der Anmeldung für $VERANSTALTUNGSNAME$
```

E-Mail-Vorschautext:

```
$BRIEFANREDE_DU$, wir haben deine Anmeldung zu „$VERANSTALTUNGSNAME$“ in $VERANSTALTUNGSORT$ vom $VERANSTALTUNGSBEGINN_LANG$ bis $VERANSTALTUNGSENDE_LANG$ storniert.
```

E-Mail-Text:

```
Stornierung der Anmeldung für $VORNAME$ $NACHNAME$: Angebotsnummer $ANGEBOTSNUMMER$: „$VERANSTALTUNGSNAME$“ in $VERANSTALTUNGSORT$
---
$BRIEFANREDE_DU$,
wir haben deine Anmeldung zu „$VERANSTALTUNGSNAME$“ in $VERANSTALTUNGSORT$ vom $VERANSTALTUNGSBEGINN_LANG$ bis $VERANSTALTUNGSENDE_LANG$ storniert.

Solltest du noch offene Fragen haben, melde dich gern in der Geschäftsstelle.

PS: Falls du sowohl Teilnehmende:r als auch Kontaktperson/Rechnungsempfänger:in bist erhältst du ggf. mehrere E-Mails. Das ist beabsichtigt und kein Fehler 👍 
```

<details>
  <summary>🖥 Vorschau</summary>
  
  ![Vorschau-Bild E-Mail-Vorlage](veranstaltung_anmeldungen_stornierung.png)

</details>

### Angemeldete/r auf Warteliste gesetzt

- Filter ⚙: - / -
- Anhänge 🔗:  [📄 Information über Warteliste](/docs/dokument-vorlagen/#Anmeldung-TN-Information-Wartenliste)
- Bemerkung 💡: Da die Meldung der Platzierung auf der Warteliste **nur** an die Teilnehmenden geht setzen wri hier die E-Mail-Adresse der Kontaktperson in CC, damit auch diese (i.d.R. Eltern) informiert werden.
- CC: `$ANMELDUNG_E-MAIL$`

Betreff:

```
Wartelistenplatz für $VERANSTALTUNGSNAME$
```

E-Mail-Vorschautext:

```
$BRIEFANREDE_DU$, wir haben deine Anmeldung vom $ANMELDEDATUM_LANG$ zu „$VERANSTALTUNGSNAME$“ vom $VERANSTALTUNGSBEGINN_LANG$ bis $VERANSTALTUNGSENDE_LANG$ erhalten.
```

E-Mail-Text:

```
Information über Wartelisten-Platz für $VORNAME$ $NACHNAME$: Angebotsnummer $ANGEBOTSNUMMER$: „$VERANSTALTUNGSNAME$“ in $VERANSTALTUNGSORT$
---
$BRIEFANREDE_DU$,

wir haben deine Anmeldung zu „$VERANSTALTUNGSNAME$“ in $VERANSTALTUNGSORT$ 
vom $VERANSTALTUNGSBEGINN_LANG$ bis $VERANSTALTUNGSENDE_LANG$ erhalten.

Leider ist die Freizeit bereits voll belegt. Wir können dir deshalb im Moment
keine Zusage geben.

Wir haben deine Anmeldung auf unsere Warteliste gesetzt.
Wenn wir eine Abmeldung von der Freizeit bekommen, rückt deine Anmeldung
automatisch nach. Falls dies der Fall sein sollte, erhältst du von uns sofort Bescheid.

Wenn wir dich von unserer Warteliste streichen sollen, gib uns bitte Bescheid.
Für Rückfragen stehen wir gerne telefonisch oder per E-Mail zu Verfügung

PS: Falls du sowohl Teilnehmende:r als auch Kontaktperson/Rechnungsempfänger:in bist erhältst du ggf. mehrere E-Mails. Das ist beabsichtigt und kein Fehler 👍 
```

<details>
  <summary>🖥 Vorschau</summary>
  
  ![Vorschau-Bild E-Mail-Vorlage](veranstaltung_anmeldungen_warteliste.png)

</details>

### Veranstaltungserinnerung versenden

- Filter ⚙: - / -
- Anhänge 🔗: - / -
- Bemerkung 💡: - / -

Betreff:

```
In $ANZAHL_TAGE_BIS_VERANSTALTUNG$ gehts los! $VERANSTALTUNGSNAME$
```

E-Mail-Vorschautext:

```
$BRIEFANREDE_DU$, in $ANZAHL_TAGE_BIS_VERANSTALTUNG$ Tagen geht es endlich los!
```

E-Mail-Text:

```
$BRIEFANREDE_DU$,
in $ANZAHL_TAGE_BIS_VERANSTALTUNG$ Tagen geht es endlich los!

Wir hoffen, die Vorfreude steigt auch auf deiner Seite bereits - das Team im Jugendwerk freut sich bereits auf dich & die gemeinsame Zeit mit dir!

Alle notwendigen Informationen hast du zum jetzigen Zeitpunkt bereits erhalten - sollten bei dir aber noch Fragen offen sein melde dich gern jederzeit bei uns in der Geschäftsstelle. Wir freuen uns auf dich!

PS: Falls du sowohl Teilnehmende:r als auch Kontaktperson/Rechnungsempfänger:in bist erhältst du ggf. mehrere E-Mails. Das ist beabsichtigt und kein Fehler 👍 
```

<details>
  <summary>🖥 Vorschau</summary>
  
  ![Vorschau-Bild E-Mail-Vorlage](veranstaltung_anmeldungen_erinnerung.png)

</details>

### Neue Anmeldung

#### Teilnehmende

- Filter ⚙: `Teilnehmerart` ist `Teilnehmer`
- Anhänge 🔗:  [📄 Eingangsbestätigung Teilnehmende](/docs/dokument-vorlagen/#Anmeldung-TN-Eingangsbestaetigung)
- Bemerkung 💡: - / -

Betreff:

```
Eingangsbestätigung der Anmeldung für $VERANSTALTUNGSNAME$
```

E-Mail-Vorschautext:

```
$BRIEFANREDE_DU$, wir haben deine Anmeldung vom $ANMELDEDATUM_LANG$ zu „$VERANSTALTUNGSNAME$“ vom $VERANSTALTUNGSBEGINN_LANG$ bis $VERANSTALTUNGSENDE_LANG$ erhalten.
```

E-Mail-Text:

```
Eingangsbestätigung der Anmeldung für Angebotsnummer $ANGEBOTSNUMMER$: „$VERANSTALTUNGSNAME$“ in $VERANSTALTUNGSORT$
---
$BRIEFANREDE_DU$,
wir haben deine Anmeldung vom $ANMELDEDATUM_LANG$ zu „$VERANSTALTUNGSNAME$“ vom $VERANSTALTUNGSBEGINN_LANG$ bis $VERANSTALTUNGSENDE_LANG$ erhalten.

Anmeldungsnummer: $ANMELDUNGSNUMMER$

Dies ist eine Bestätigung über den Eingang der Anmeldung, keine verbindliche Anmeldebestätigung. Wir prüfen nun deine Anmeldung und melden uns so bald wie möglich bei dir. Eine Anmeldebestätigung folgt, sobald unsere Mitarbeitenden diese bearbeitet haben. Aufgrund hohen Anmeldeaufkommens kann das einige Tage in Anspruch nehmen. Wir bitten von telefonischen Anfragen des Anmeldestatus abzusehen, da dies unsere Bearbeitungszeit verlängert.

Falls du noch Fragen hast, melde dich gerne einfach per E-Mail oder rufe kurz bei uns an. Wir freuen uns auf eine tolle Zeit mit dir!

PS: Falls du sowohl Teilnehmende:r als auch Kontaktperson/Rechnungsempfänger:in bist erhältst du ggf. mehrere E-Mails. Das ist beabsichtigt und kein Fehler 👍 
```

<details>
  <summary>🖥 Vorschau</summary>
  
  ![Vorschau-Bild E-Mail-Vorlage](veranstaltung_anmeldungen_eingang_tn.png)

</details>

---

#### Betreuende

- Filter ⚙: `Teilnehmerart` ist `Betreuer`
- Anhänge 🔗: - / -
- Bemerkung 💡: - / -

Betreff:

```
Eingangsbestätigung der Mitarbeiter-Anmeldung für $VERANSTALTUNGSNAME$
```

E-Mail-Vorschautext:

```
$BRIEFANREDE_DU$, wir haben deine Mitarbeiter-Anmeldung vom $ANMELDEDATUM_LANG$ zu „$VERANSTALTUNGSNAME$“ vom $VERANSTALTUNGSBEGINN_LANG$ bis $VERANSTALTUNGSENDE_LANG$ erhalten.
```

E-Mail-Text:

```
Eingangsbestätigung der Mitarbeiter-Anmeldung für Angebotsnummer $ANGEBOTSNUMMER$: „$VERANSTALTUNGSNAME$“
---
$BRIEFANREDE_DU$,
wir haben deine Mitarbeiter-Anmeldung vom $ANMELDEDATUM_LANG$ Uhr zu „$VERANSTALTUNGSNAME$“ vom $VERANSTALTUNGSBEGINN_LANG$ bis $VERANSTALTUNGSENDE_LANG$ erhalten.

Anmeldungsnummer: $ANMELDUNGSNUMMER$
Betreuerfunktion/Team: $BETREUERFUNKTION$

Dies ist eine Bestätigung über den Eingang der Anmeldung, keine verbindliche Anmeldebestätigung. Wir prüfen nun deine Anmeldung und melden uns so bald wie möglich bei dir.

Falls du noch Fragen hast, melde dich gerne einfach per E-Mail oder rufe kurz bei uns an. Wir freuen uns auf eine tolle Zeit mit dir!

PS: Falls du sowohl Mitarbeitende:r als auch Kontaktperson bist erhältst du ggf. mehrere E-Mails. Das ist beabsichtigt und kein Fehler 👍 
```

<details>
  <summary>🖥 Vorschau</summary>
  
  ![Vorschau-Bild E-Mail-Vorlage](veranstaltung_anmeldungen_eingang_ma.png)

</details>

### Ticketmail

- Bemerkung 💡: dafür haben wir aktuell noch keine Vorlage, da wir das Ticket-Feature bisher nicht genutzt haben!

## Mails an Rechnungsempfänger / Kontaktperson einer Anmeldung

### Neue Anmeldung

#### Teilnehmende

- Filter ⚙: `Anmeldungsart` ist `Anmeldung für Teilnehmende`
- Anhänge 🔗:  [📄 Eingangsbestätigung Rechnungsempfänger](/docs/dokument-vorlagen/#Anmeldung-RE-Eingangsbestaetigung)
- Bemerkung 💡: - / -

Betreff:

```
Eingangsbestätigung der Anmeldung für $VERANSTALTUNGSNAME$
```

E-Mail-Vorschautext:

```
$BRIEFANREDE_DU$, wir haben deine Anmeldung vom $ANMELDEDATUM_LANG$ zu „$VERANSTALTUNGSNAME$“ vom $VERANSTALTUNGSBEGINN_LANG$ bis $VERANSTALTUNGSENDE_LANG$ erhalten.
```

E-Mail-Text:

```
Eingangsbestätigung der Anmeldung für Angebotsnummer $ANGEBOTSNUMMER$: „$VERANSTALTUNGSNAME$“
---
$BRIEFANREDE_DU$,
wir haben (d)eine Anmeldung vom $ANMELDEDATUM_LANG$ $ANMELDEDATUM_UHRZEIT$ Uhr zu „$VERANSTALTUNGSNAME$“ in $VERANSTALTUNGSORT$ vom $VERANSTALTUNGSBEGINN_LANG$ bis $VERANSTALTUNGSENDE_LANG$ erhalten.

Anmeldungsnummer: $ANMELDUNGSNUMMER$
Angemeldete Teilnehmende: $NAMEN_DER_TEILNEHMENDEN$ ( Σ $ANZAHL_AN_TEILNEHMENDEN$ Teilnehmende)
Bemerkungen: $BEMERKUNGEN_DES_ANMELDENDEN$

Dies ist eine Bestätigung über den Eingang der Anmeldung, keine verbindliche Anmeldebestätigung. Wir prüfen nun deine Anmeldung und melden uns so bald wie möglich bei dir. Eine Anmeldebestätigung folgt, sobald unsere Mitarbeitenden diese bearbeitet haben. Aufgrund hohen Anmeldeaufkommens kann das einige Tage in Anspruch nehmen. Wir bitten von telefonischen Anfragen des Anmeldestatus abzusehen, da dies unsere Bearbeitungszeit verlängert.

Falls du noch Fragen hast, melde dich gerne einfach per E-Mail oder rufe kurz bei uns an. Wir freuen uns auf eine tolle Zeit mit dir!

PS: Falls du sowohl Teilnehmende:r als auch Kontaktperson/Rechnungsempfänger:in bist erhältst du ggf. mehrere E-Mails. Das ist beabsichtigt und kein Fehler 👍 
```

<details>
  <summary>🖥 Vorschau</summary>
  
  ![Vorschau-Bild E-Mail-Vorlage](veranstaltung_re_eingangsbestaetigung.png)

</details>

---

#### Betreuende

- Filter ⚙: `Anmeldungsart` ist `Anmeldung für Betreuende`
- Anhänge 🔗: - / -
- Bemerkung 💡: - / -

Betreff:

```
Eingangsbestätigung der Mitarbeiter-Anmeldung für $VERANSTALTUNGSNAME$
```

E-Mail-Vorschautext:

```
$BRIEFANREDE_DU$, wir haben deine Mitarbeiter-Anmeldung vom $ANMELDEDATUM_LANG$ zu „$VERANSTALTUNGSNAME$“ vom $VERANSTALTUNGSBEGINN_LANG$ bis $VERANSTALTUNGSENDE_LANG$ erhalten.
```

E-Mail-Text:

```
Eingangsbestätigung der Mitarbeiter-Anmeldung für Angebotsnummer $ANGEBOTSNUMMER$: „$VERANSTALTUNGSNAME$“
---
$BRIEFANREDE_DU$,
wir haben deine Mitarbeiter-Anmeldung vom $ANMELDEDATUM_LANG$ zu „$VERANSTALTUNGSNAME$“ in $VERANSTALTUNGSORT$ vom $VERANSTALTUNGSBEGINN_LANG$ bis $VERANSTALTUNGSENDE_LANG$ erhalten.

Anmeldungsnummer: $ANMELDUNGSNUMMER$
Angemeldete Mitarbeitende: $NAMEN_DER_TEILNEHMENDEN$ ( Σ $ANZAHL_AN_TEILNEHMENDEN$ Mitarbeitende)

Dies ist eine Bestätigung über den Eingang der Anmeldung, keine verbindliche Anmeldebestätigung. Wir prüfen nun deine Anmeldung und melden uns so bald wie möglich bei dir.

Falls du noch Fragen hast, melde dich gerne einfach per E-Mail oder rufe kurz bei uns an. Wir freuen uns auf eine tolle Zeit mit dir!

PS: Falls du sowohl Mitarbeitende:r als auch Kontaktperson bist erhältst du ggf. mehrere E-Mails. Das ist beabsichtigt und kein Fehler 👍 
```

<details>
  <summary>🖥 Vorschau</summary>
  
  ![Vorschau-Bild E-Mail-Vorlage](veranstaltung_re_eingangsbestaetigung_ma.png)

</details>

### Anmeldung bestätigt

#### Teilnehmende

- Filter ⚙: `Anmeldungsart` ist `Anmeldung für Teilnehmende`
- Anhänge 🔗:  [📄 Anmeldebestätigung Rechnungsempfänger (mit Anzahlung)](/docs/dokument-vorlagen/#Anmeldebestaetigung-RE-mit-Anzahlung)
- Bemerkung 💡: - / -

Betreff:

```
Anmeldebestätigung für $VERANSTALTUNGSNAME$
```

E-Mail-Vorschautext:

```
$BRIEFANREDE_DU$, herzlichen Glückwunsch, du bist dabei!
```

E-Mail-Text:

```
Bestätigung der Anmeldung für $NAMEN_DER_TEILNEHMENDEN$: Angebotsnummer $ANGEBOTSNUMMER$: „$VERANSTALTUNGSNAME$“ in $VERANSTALTUNGSORT$
---
$BRIEFANREDE_DU$,
wir haben (d)eine Anmeldung zu „$VERANSTALTUNGSNAME$“ in $VERANSTALTUNGSORT$ vom $VERANSTALTUNGSBEGINN_LANG$ bis $VERANSTALTUNGSENDE_LANG$ erhalten und bestätigen hiermit die Teilnahme von $NAMEN_DER_TEILNEHMENDEN$. Herzlichen Glückwunsch! 

Damit ist gemäß unseren Reisebedingungen der Reisevertrag zustande gekommen. Anbei findest du die ausführliche Anmeldebestätigung sowie weitere, wichtige Hinweise. Bitte lies dir diese aufmerksam durch.

Die beiden Rechnungen für die Freizeit (1x Anzahlung, 1x Restbetrag) erhältst du gesondert von dieser Bestätigung. Bitte beachte hierbei das Zahlungsziel der Anzahlung.

Spätestens drei Wochen vor Beginn der Freizeit bekommst du einen
ausführlichen Informationsbrief. Für weitere Fragen stehen wir natürlich
gerne zur Verfügung. In $ANZAHL_TAGE_BIS_VERANSTALTUNG$ Tagen geht’s los!

PS: Falls du sowohl Teilnehmende:r als auch Kontaktperson/Rechnungsempfänger:in bist erhältst du ggf. mehrere E-Mails. Das ist beabsichtigt und kein Fehler 👍 
```

<details>
  <summary>🖥 Vorschau</summary>
  
  ![Vorschau-Bild E-Mail-Vorlage](veranstaltung_re_anmeldebestaetigung_tn.png)

</details>

---

#### Betreuende

- Filter ⚙: `Anmeldungsart` ist `Anmeldung für Betreuende`
- Anhänge 🔗:  - / -
- Bemerkung 💡: - / -

Betreff:

```
Anmeldebestätigung für $VERANSTALTUNGSNAME$
```

E-Mail-Vorschautext:

```
$BRIEFANREDE_DU$, herzlichen Glückwunsch, du bist dabei!
```

E-Mail-Text:

```
Bestätigung der Mitarbeiter-Anmeldung von $NAMEN_DER_TEILNEHMENDEN$: Angebotsnummer $ANGEBOTSNUMMER$: „$VERANSTALTUNGSNAME$“
---
$BRIEFANREDE_DU$,
herzlichen Glückwunsch, du bist als Mitarbeiter dabei! Wir sind sehr dankbar, dass du uns unterstützt!

Wir haben deine Anmeldung zu „$VERANSTALTUNGSNAME$“ vom $VERANSTALTUNGSBEGINN_LANG$ bis $VERANSTALTUNGSENDE_LANG$ erhalten und bestätigen hiermit die Teilnahme.

Weitere Informationen zum Ablauf und der Vorbereitung erhältst du in der Regel direkt von der Freizeitleitung. Für weitere Fragen stehen wir natürlich
gerne zur Verfügung. In $ANZAHL_TAGE_BIS_VERANSTALTUNG$ Tagen geht’s los!

PS: Falls du sowohl Mitarbeitende:r als auch Kontaktperson bist erhältst du ggf. mehrere E-Mails. Das ist beabsichtigt und kein Fehler 👍 

```

<details>
  <summary>🖥 Vorschau</summary>
  
  ![Vorschau-Bild E-Mail-Vorlage](veranstaltung_re_anmeldebestaetigung_ma.png)

</details>

### Neue Gruppenanmeldung erstellt

- Filter ⚙: - / -
- Anhänge 🔗:  [📄 Anmeldebestätigung TN mit Anzahlung](/docs/dokument-vorlagen/#Anmeldebestaetigung-TN-mit-Anzahlung)
- Bemerkung 💡: Hier kann keine persönliche Anrede verwendet werden, da der Platzhalter hier nicht verfügbar ist.

Betreff:

```
Neue Gruppenanmeldung für $VERANSTALTUNGSNAME$ erstellt
```

E-Mail-Vorschautext:

```
Hey, wir haben die Gruppenanmeldung zu „$VERANSTALTUNGSNAME$“ vom $VERANSTALTUNGSBEGINN_LANG$ bis $VERANSTALTUNGSENDE_LANG$ erhalten.
```

E-Mail-Text:

```
Neue Gruppenanmeldung für $ANGEBOTSNUMMER$: „$VERANSTALTUNGSNAME$“ in $VERANSTALTUNGSORT$ erstellt
---
Hey,
wir haben die Gruppenanmeldung zu „$VERANSTALTUNGSNAME$“ in $VERANSTALTUNGSORT$
vom $VERANSTALTUNGSBEGINN_LANG$ bis $VERANSTALTUNGSENDE_LANG$ erhalten.

Anmeldungsnummer: $ANMELDUNGSNUMMER$

Diesen Link bitte nicht an deine Gruppenteilnehmenden weitergeben. Über diesen Link kannst du die Anmeldungen deiner Gruppenteilnehmenden überprüfen und bestätigen. Wenn alle Anmeldungen eingegangen sind kannst du darüber die Anmeldung schließen und abschicken.

Diesen Link kannst du an deine Gruppenteilnehmenden weiterleiten. Diese können sich dann zu Deiner Gruppe anmelden.

Wir prüfen die angemeldeten Teilnehmer deiner Gruppenanmeldung erst, nachdem du diese abgeschlossen und abgeschickt hast und melden uns so bald wie möglich bei dir.

Falls du noch Fragen hast, melde dich gerne einfach per E-Mail oder rufe kurz bei uns an. Wir freuen uns auf eine tolle Zeit mit dir!
```

💡 Code-Block Buttons inkl. Text (2-spaltiger Absatz)

```
<re-grid>
    <re-column padding="0 0 20px 0" width="50%" valign="top">
        <re-button background-color="#123a5e" font-size="16px" href="$GRUPPENLINK_VERANTWORTLICHE_PERSON$">
            Verwaltung der&nbsp; Anmeldungen
        </re-button>
        <re-spacer></re-spacer>
        <re-text>
            Diesen Link bitte&nbsp;<u>nicht</u>&nbsp;an deine Gruppenteilnehmenden weitergeben. Über diesen Link kannst du die Anmeldungen deiner Gruppenteilnehmenden überprüfen und bestätigen. Wenn alle Anmeldungen eingegangen sind kannst du darüber die Anmeldung schließen und abschicken.
        </re-text>
    </re-column>
    <re-column-spacer></re-column-spacer>
    <re-column padding="0 0 20px 0" width="50%" valign="top">
        <re-button color="#ffffff" background-color="#f29400" font-size="16px" href="$GRUPPENLINK_TEILNEHMENDE$">
            Anmeldelink für Teilnehmende
        </re-button>
        <re-spacer></re-spacer>
        <re-text>
            Diesen Link kannst du an deine Gruppenteilnehmenden weiterleiten. Diese können sich dann zu Deiner Gruppe anmelden.
        </re-text>
    </re-column>
</re-grid>
```

<details>
  <summary>🖥 Vorschau</summary>
  
  ![Vorschau-Bild E-Mail-Vorlage](veranstaltung_anmeldungen_neue-gruppenanmeldung.png)

</details>