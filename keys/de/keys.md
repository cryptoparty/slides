% ![](../images/logo.png)
% <strong>Kryptographische Schlüssel</strong>
% {{Speaker Name}} — {{Month}} {{Date}}, {{Year}}

# Überblick

- Kryptographische Schlüssel 
- Verschlüsseln und Signieren
- Zertifikate
- Sicherheitsannahmen

<img src="./images/CryptoKey.svg" style="align:right"/>

# Schlüsselpaar

 "Immer zu zweit sie sind! Ein Meister und ein Schüler!"
    ~ Meister Yoda (Episode 1)

<hr/>

<table align=center>
<tr><td>öffentlicher Schlüssel</td><td>privater Schlüssel</td></tr>
<tr><td><img src="./images/PubKey.svg" style="align:right"/></td><td><img src="./images/PrivKey.svg" style="align:right"/></td></tr>
</table>

<hr />

Schnappschloß Tür-Analogie: 

- öffentlich: jeder kann die Tür zuziehen
- privat: nur mit Schlüssel zu öffnen


# Verschlüsseln

- Macht Daten unlesbar 
- "ausser"
- mit dem passenden Schlüssel.
- Bsp: "Das wird jetzt kryptisch!"

  hQEMA9WCTo3/O878AQf8Cl0QcfmgAO1vLDjfqC21hUqoZ6zI5qrgcwZO3uLH4RBr
  uDwG+wMo+Mx1fiqGCgwJRelRx03u1p5bi9IpVn9kPttFhmhIOVEuZ9fyyF1dYUe6
  YOBnbdwaQ3IeI5p+JqrlG6Xgnw8pSrhlwGYOwg2ya+U9gMjcrFa6IgwpOKI3Dime
  kJcmkq5cQWyiyfK811romZzfUi66L02lTp8RchZjrvwvMOjcmbOKJrp56xWe1RP9
  XqpRzoreiQmn8XgkHA6eTLmMFz79Jbpz/LLS21x0VVBmhojVTxiPmQXfdxazgeYZ
  FJ+mWrKTgrIMMXdVEL0YLDWdqh5N2ZY15jfnktf6ZdJVARIwGjjVdOpXZecJwgLY
  Ftllw5hXyA+QOdzK8IGiAy5hMfSSFew/mk6aLxa2txrtmOliO5ahJBz8N29hxczY
  EI8qdfou4kjpfY8ekB+qxWjYKpF9uA===VXx6




# Public-Key Verschlüsselung

<img src="./images/PublicKeyCryptography.png" style="height:80%"/>


# Signieren

- Privater Schlüssel: ist nur dem Besitzer bekannt
- Entschlüsseln kann nur mit privatem Schlüssel geschehen

- Signatur ist Anwendung des Privaten Schlüssels auf Daten
- Jeder andere kann dies mit dem Öffentlichen Schlüssel prüfen

- Voraussetzung: Kenntnis des Öffentlichen Schlüssels


# Zertifikat

Signatur über:

- Identifikator: Name, Email, Web-Adresse,…
- öffentlicher Schlüssel

<hr /> 

Signierender Zertifizierer muß vorher prüfen:
- Identifikator gehört zur Person
- Person kennt passenden privaten Schlüssel

<hr />

Glaubwürdigkeit von Zertifikaten
- ist Vertrauenswürdigkeit des Zertifizierers


# Sicherheit

- Entschlüsseln ohne passenden Schlüssel: schwierig
- Geheimhaltung d. priv. Schlüssels
- Hauptproblem: Zertifizierungsstellen (CA)
- z.B. im Browser 250 "vertrauenswürdige" Stellen
- Jede CA kann alle Seiten signieren


# Zusammenfassung

-