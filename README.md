# MUA_GTNH_MODS

This repository is a `.minecraft/mods` directory for GTNH players of MUA. Players can update their mods via this repository. 

This repository distributes the compiled jar of an **unofficial modified build** of
GT: Not Leisure (Science Not Leisure). It is not the upstream project and is not
affiliated with or endorsed by the upstream authors.

## Artifact

- Jar: `sciencenotleisure-0.2.7-pre3-dev-290.37+082483e468.jar`
- SHA-256: `5981f86467ee9eb97562358437aa5548294e7e9130a0ffebd73438ee70bcfe00`
- Base upstream version: `0.2.7-pre3-dev-290.37+082483e468`
- Base upstream commit: `082483e468942eb1949975f08bc900510c91d930`
- Target: GT: New Horizons `2.9.0-beta-3` / Minecraft 1.7.10 / Forge 10.13.4.1614

## Modifications

The jar replaces the deprecated IC2 block `IC2:blockAlloyGlass` (183:0) with
GregTech `gregtech:gt.blockglass1` metadata 10 (3028:10) in 5 multiblock
structures, 7 recipe input references, and 7 quest material requirements.
See `MODIFICATIONS.md` for the full list and the modification date.

## Corresponding source (LGPL-3.0 compliance)

The complete corresponding source is available here:

- Source repository: `https://github.com/KurumiMyWaifu/GT-Not-Leisure-BUAA-Unofficial/tree/v1.0.0`
- Source archive: attached to the same GitHub Release as the jar
  (`GT-Not-Leisure-082483e468-glassfix-source.tar.gz`)

The source archive contains the modified source, the build scripts, and the
license text. Please keep the source repository public for as long as you
distribute this jar.

## License

- The jar and the modified source are distributed under the **GNU Lesser General
  Public License v3.0 (LGPL-3.0)**. See `LICENSE-LGPL-3.0.txt` / `LICENSE.txt`.
- Third-party code and assets retain their own licenses; see
  `THIRD-PARTY-NOTICES.md` and the upstream README credits.
- There is **no warranty**, to the extent permitted by law.
- This is an unofficial build; do not imply endorsement by the upstream authors.

## Redistribution

If you redistribute this jar, keep this notice, the LGPL-3.0 license text, the
source link/archive, and the third-party notices. Do not apply a more restrictive
license to the jar or add restrictions that conflict with LGPL-3.0.
