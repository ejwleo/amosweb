---
title: Vorlagen
weight: 2
prev: /docs/email-vorlagen/anwendung
next: /docs/email-vorlagen/vorlagen/
sidebar:
  open: true
---

Für eine bessere Übersichtlichkeit haben wir die Vorlagen in Kategorien aufgeteilt:

{{< cards >}}
  {{< card link="veranstaltungsmails" title="Veranstaltungsmails" subtitle="im Kontext einer Veranstaltung" icon="document-duplicate" >}}
  {{< card link="rechnungsmails" title="Rechnungsmails" subtitle="allgemeine Rechnungsmail" icon="cash" >}}
{{< /cards >}}

{{< callout emoji="💡" title="Tipp" >}}
  Idealerweise verwendest du aus den Vorlagen nur den eigentlichen Mail-Text und hast den generellen Look & die Grundstruktur bereits für dich als personalisierte Vorlage abgespeichert. Daher stellen wir hier nur die eigentlichen Mail-Texte bereit und nicht den kompletten Code.
{{< /callout >}}

---

{{< callout type="info" title="Tipp" >}}
  In den folgenden Vorlagen zeigt das Vorschau-Bild nur den eigentlichen Mailtext, da sich die Inhalte der Vorlage darüber & darunter nicht ändern - siehe dazu auch [Aufbau der Vorlage](/amosweb/docs/email-vorlagen/aufbau)
{{< /callout >}}

## Basis-Vorlage

 Über den ausklappbaren Bereich unten kommst du zu einer Basis-Vorlage, gefüllt mit Beispieltext. Diese solltest du als Ausgangsbasis nehmen, um darin deine Daten anzupassen. Bei der Erstellung der jeweiligen Vorlagen kannst du dich dann an unseren angegebenen Texten orientieren.

 <!--more-->

{{% details title="Code für Basis-Vorlage" closed="true" %}}

``` html
<re-html>
<re-head>
    <re-title>
        Anmeldebestätigung für $VERANSTALTUNGSNAME$
    </re-title>
</re-head>
<re-body background-color="#ffffff" padding="40px 5px 80px 5px">
    <re-preheader>
        $BRIEFANREDE_DU$, herzlichen Glückwunsch, du bist dabei!
    </re-preheader>
    <re-main background-color="#fff" border-radius="6px">
        <re-block border-radius="10px" align="center" padding="40px" background-color="#f4f4f4">
            <re-image src="https://amosweb.de/contact-book/amos_favicon_170.png" width="170px"></re-image>
            <re-spacer height="20px"></re-spacer>
            <re-spacer height="20px"></re-spacer>
            <re-heading margin="0 0 5px 0" level="h4" align="left">
                Bestätigung der Anmeldung für $VORNAME$ $NACHNAME$: Angebotsnummer $ANGEBOTSNUMMER$: „$VERANSTALTUNGSNAME$“
            </re-heading>
            <re-spacer></re-spacer>
            <re-divider background-color="#adb5bd"></re-divider>
            <re-spacer></re-spacer>
            <re-heading margin="0 0 5px 0" level="h3" align="left">
                $BRIEFANREDE_DU$,
            </re-heading>
            <re-text align="left">
                herzlichen Glückwunsch, du bist dabei!
            </re-text>
            <re-spacer height="20px"></re-spacer>
            <re-text align="left">
                Wir haben deine Anmeldung zu „$VERANSTALTUNGSNAME$“ in $VERANSTALTUNGSORT$ vom <b>$VERANSTALTUNGSBEGINN_LANG$ bis $VERANSTALTUNGSENDE_LANG$</b> erhalten und bestätigen hiermit die Teilnahme. Damit ist gemäß unseren Reisebedingungen der Reisevertrag zustande gekommen.<br>
                <br>
                Anbei findest du die ausführliche Anmeldebestätigung sowie weitere, wichtige Hinweise. Bitte lies dir diese aufmerksam durch.<br>
                <br>
                Die beiden Rechnungen für die Freizeit (1x Anzahlung, 1x Restbetrag) versenden wir gesondert von dieser Bestätigung an den angegebenen Rechnungsempfänger.<br>
                <br>
                Spätestens drei Wochen vor Beginn der Freizeit bekommst du einen <br>
                ausführlichen Informationsbrief. Für weitere Fragen stehen wir natürlich <br>
                gerne zur Verfügung. In $ANZAHL_TAGE_BIS_VERANSTALTUNG$ Tagen geht’s los!<br>
                ﻿<br>
                ﻿PS: Falls du sowohl Teilnehmende:r als auch Kontaktperson/Rechnungsempfänger:in bist erhältst du ggf. mehrere E-Mails. Das ist beabsichtigt und kein Fehler 👍&nbsp;<br>
            </re-text>
        </re-block>
        <re-block>
            <re-spacer height="32px"></re-spacer>
        </re-block>
    </re-main>
    <re-footer padding="" border-radius="6px">
        <re-block padding="30px 30px 30px 30px" border-radius="10px" background-color="#123a5e">
            <re-text color="#ffffff">
                Viele Grüße aus ## DEINE ORGANISATION ##, <br>
                $SACHBEARBEITUNG_VORNAME$ $SACHBEARBEITUNG_NACHNAME$<br>
                <br>
                <a href="mailto:$SACHBEARBEITUNG_E-MAIL$" style="color: rgb(255, 255, 255);">$SACHBEARBEITUNG_E-MAIL$</a>﻿ | $SACHBEARBEITUNG_TELEFON$
            </re-text>
        </re-block>
        <re-block>
            <re-spacer height="32px"></re-spacer>
        </re-block>
        <re-block padding="30px 30px 30px 30px" border-radius="10px" background-color="#f4f4f4">
            <re-heading level="h3" font-weight="normal">
                Wir sind <b>für dich da!</b>
            </re-heading>
            <re-spacer></re-spacer>
            <re-text>
                Egal ob du Fragen hast, uns Rückmeldung geben möchtest oder dir etwas anderes auf dem Herzen liegt - wir freuen uns von dir zu hören! Melde dich direkt in der Geschäftsstelle, komm einfach während den Öffnungszeiten vorbei oder kontaktiere direkt den zuständigen Ansprechpartner. Die Übersicht dazu findest du <a href="https://deine-domain.de/wir/geschaeftsstelle/" style="color: rgb(34, 34, 40);">hier</a>﻿.
            </re-text>
            <re-spacer height="20px"></re-spacer>
            <re-divider background-color="#d4d4d4"></re-divider>
            <re-spacer height="20px"></re-spacer>
            <re-grid>
                <re-column padding="0 0 20px 0" width="50%">
                    <re-heading margin="0 0 5px 0" level="h4">
                        Geschäftsstelle
                    </re-heading>
                    <re-text>
                        ## ORGANISATIONSNAME ##<br>
                        ....<br>
                        Musterstraße 42<br>
                        12345 Bielefeld
                    </re-text>
                </re-column>
                <re-column-spacer></re-column-spacer>
                <re-column padding="0 0 20px 0" width="50%">
                    <re-heading margin="0 0 5px 0" level="h4">
                        Erreichbarkeit
                    </re-heading>
                    <re-text>
                        Mo. – Do. / 09.00 Uhr – 18.00 Uhr<br>
                        Fr. / 09.00 Uhr – 16.00 Uhr
                    </re-text>
                </re-column>
            </re-grid>
            <re-spacer></re-spacer>
            <re-grid>
                <re-column padding="0 0 20px 0" width="50%">
                    <re-heading margin="0 0 5px 0" level="h4">
                        Kontakt
                    </re-heading>
                    <re-text>
                        Telefon: 07152 / 123456<br>
                        Fax: 07152 / 124568<br>
                        E-Mail: <a href="mailto:info@eine-domain.de" style="color: rgb(34, 34, 40);">info@deine-domain.de</a>
                    </re-text>
                </re-column>
                <re-column-spacer></re-column-spacer>
                <re-column padding="0 0 20px 0" width="50%">
                    <re-heading margin="0 0 5px 0" level="h4">
                        Social Media
                    </re-heading>
                    <re-social>
                        <re-social-item href="https://www.youtube.com/ejwleode" alt="YouTube" src="https://raw.githubusercontent.com/ejwleo/amosweb/main/static/icons/youtube_small.png" width="45px"></re-social-item><re-social-spacer>&nbsp;&nbsp;&nbsp;</re-social-spacer><re-social-item href="https://www.instagram.com/ejwleo" alt="Instagram" src="https://raw.githubusercontent.com/ejwleo/amosweb/main/static/icons/instagram_small.png" width="42px"></re-social-item><re-social-spacer>&nbsp;&nbsp;&nbsp;</re-social-spacer><re-social-item href="https://www.facebook.com/ejwleo" alt="Facebook" src="https://raw.githubusercontent.com/ejwleo/amosweb/main/static/icons/facebook_small.png" width="42px"></re-social-item>
                    </re-social>
                </re-column>
            </re-grid>
            <re-spacer></re-spacer>
            <re-text color="#adb5bd" align="left">
                ©&nbsp;## ORGANISATIONSNAME ##. Alle Rechte vorbehalten.<br>
                <a href="https://deine-domain.de/service/hinweise-datenverarbeitung/" style="color: rgb(173, 181, 189);">Hinweise zur Datenverarbeitung</a>﻿&nbsp; |&nbsp;&nbsp;<a href="https://deine-domain.de/impressum/" style="color: rgb(173, 181, 189);">Impressum</a>﻿&nbsp; |&nbsp;&nbsp;<a href="https://deine-domain.de/datenschutzerklaerung/" style="color: rgb(173, 181, 189);">Datenschutzerklärung</a>
            </re-text>
        </re-block>
        <re-block>
            <re-spacer height="32px"></re-spacer>
            <re-text color="#adb5bd">
                Diese E-Mail wird automatisch erzeugt. Du erhältst diese E-Mail, da du dich bei einer Veranstaltung des ## ORGANISATIONSNAME ## angemeldet hast. Die E-Mail und übermittelte Dateien können vertrauliche Informationen enthalten. Falls Du nicht der/die richtige Empfänger:in bist, bist du zur Verwendung dieser Informationen nicht befugt. In einem solchen Fall melde dich bitte bei uns.
            </re-text>
        </re-block>
    </re-footer>
</re-body>
</re-html>
```

{{% /details %}}
