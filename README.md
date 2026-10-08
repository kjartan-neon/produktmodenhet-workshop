# Produktmodenhet Workshop

Interaktivt workshopverktøy for å kartlegge teamets produktmodenhet på tvers av fem dimensjoner. Basert på Menti-undersøkelse, bygget om til fysisk/digital workshop der hver deltaker svarer individuelt og deretter sammenligner og diskuterer med teamet.

**URL (kun for NRK-ansatte):** https://produktmodenhet.nrk-stash.dev/

---

## Hva det er

Workshopen dekker fem dimensjoner av produktmodenhet:

1. **Ansvarlige og myndiggjorte team** – måles teamet på verdi, ikke leveranser?
2. **Kontinuerlig innsikt (Teresa Torres)** – er hele teamet i kontakt med brukerne?
3. **Tverrfaglig** – jobber design, produkt og teknologi tett sammen?
4. **Eksperimentering og antagelser** – tester vi før vi bygger?
5. **Kontinuerlige leveranser og måling av verdi** – deployer vi hyppig og lærer av det?

Hvert spørsmål besvares på en skala fra 1 (helt uenig) til 7 (helt enig).

---

## Slik bruker du det

### Individuell utfylling
Hver deltaker åpner lenken på egen enhet (mobil, nettbrett eller PC) og fyller ut alle spørsmålene selv. Svarene lagres i nettleseren (cookie) og blir liggende til de nullstilles.

### Sammenligning og diskusjon
Når alle har svart, går gruppen gjennom én dimensjon om gangen og sammenligner svarene. Store sprik er ofte de mest interessante samtalestartere.

### PDF-eksport
Trykk **«⬇ Last ned PDF»** for å laste ned et sammendrag med dine svar. Én side per dimensjon, med fargekoding. Nyttig til å ta med inn i samtalen eller arkivere.

### Nullstilling
Trykk **«↺ Nullstill»** i toppen for å slette alle svar og starte på nytt. Krever et ekstra klikk som bekreftelse.

---

## Teknisk

- Én enkelt HTML-fil, ingen server eller backend
- Svar lagres i en cookie (60 dager) i den enkeltes nettleser
- PDF genereres lokalt i nettleseren med jsPDF – ingen data sendes ut
- Fungerer på mobil, nettbrett og desktop
- Hostet på nrk-stash med SSO – kun tilgjengelig for NRK-ansatte
