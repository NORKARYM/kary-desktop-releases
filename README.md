# KÄRŸ Desktop — Releases

Binaris **descarregables** del launcher **KÄRŸ Desktop** (Windows · macOS · Linux).

Aquest repositori és **públic a propòsit**: només conté els artefactes de release
(instal·ladors i bundles), perquè qualsevol usuari els pugui descarregar **sense
autenticar-se a GitHub**. El **codi font viu al repo privat** `NORKARYM/KARY-LAUNCHER`
i es publica aquí **automàticament** des del seu workflow de release.

## Descarregar

Vés a **[Releases](../../releases)** i baixa l'artefacte del teu sistema:

| Sistema | Artefacte |
|--------|-----------|
| Windows | `.exe` (installer) / `.msi` |
| macOS (Apple Silicon / Intel) | `.dmg` |
| Linux | `.AppImage` |

> Els builds estan **sense firma** de moment (Authenticode / notarització Apple
> arribaran amb els certificats). El SO pot avisar en obrir-los el primer cop.

## Verificar la baixada

El propi launcher verifica el **sha256** de tot el que instal·la abans d'executar-ho.

## Com es publica

El workflow `Release KÄRŸ Desktop` del repo privat construeix als 3 SO i fa un
**mirall** dels bundles cap aquí (job `publish`). No cal tocar res manualment.

---

© NORKARYM · KÄRŸ
