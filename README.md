# Fjernvarme House Card

## Neutral mobile preview

![Neutral mobile preview of ha-fjernvarme-house-card](docs/preview.png)

> Rendered at 390 px mobile width with fictional Home Assistant entities and values. No private dashboard, person, address, camera, or sensor data is included.


Et selvstændigt, tema-kompatibelt Lovelace-kort til Home Assistant. Kortet er flyttet fra en aktiv installation til et separat repository, så kildekode og versionshistorik kan vedligeholdes sikkert.

## Installation

Kopiér `ha-fjernvarme-house-card.js` til `/config/www/ha-fjernvarme-house-card/` og registrér ressourcen som et JavaScript-modul:

```text
/local/ha-fjernvarme-house-card/ha-fjernvarme-house-card.js?v=0.1.50
```

Tilføj derefter korttypen `custom:ha-fjernvarme-house-card` i Lovelace. De nødvendige entities angives i kortets konfiguration; repositoryet indeholder ingen installationens dashboardkonfiguration eller personlige data.

## Udvikling

```bash
npm run check
```

## Licens

MIT
