# KÄRŸ Desktop — Releases

Binaris **descarregables** de l'ecosistema **KÄRŸ Desktop** (Windows · macOS · Linux).

Aquest repositori és **públic a propòsit**: només conté artefactes de release
(instal·ladors i bundles), perquè qualsevol usuari els pugui descarregar **sense
autenticar-se a GitHub**. El **codi font viu als repos privats** corresponents i es
publica aquí **automàticament** des dels seus workflows de release.

## Aplicacions i convenció de tags

Cada app publica amb un **prefix de tag** propi (per no xocar al repo compartit):

| App | Repo privat (codi) | Tag del release públic |
|-----|--------------------|-------------------------|
| **KÄRŸ Desktop** (launcher) | `NORKARYM/KARY-LAUNCHER` | `kary-desktop-v*` |
| **BITXOS** | `NORKARYM/BITXOS` | `bitxos-v*` |
| **GENOAI** | `NORKARYM/GENOAI` | `genoai-v*` |

## Descarregar

Vés a **[Releases](../../releases)** i busca el teu sistema:

| Sistema | Artefacte |
|--------|-----------|
| Windows | `.exe` (installer) / `.msi` |
| macOS (Apple Silicon / Intel) | `.dmg` |
| Linux | `.AppImage` |

> Builds **sense firma** de moment (Authenticode / notarització Apple arribaran amb els
> certificats). El SO pot avisar en obrir-los el primer cop.

## Verificar la baixada

El launcher verifica el **sha256** de tot el que instal·la abans d'executar-ho.

## Com es publica

El workflow de release de cada repo privat construeix i fa un **mirall** dels bundles cap
aquí. Només cal el secret `RELEASES_TOKEN` (millor com a secret d'org de NORKARYM).

---

© NORKARYM · KÄRŸ
