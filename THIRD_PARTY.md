# Provenance and license boundaries

The PEQ core used by the audio and UI components derives from [DiamondBond/q2-ringnav](https://github.com/DiamondBond/q2-ringnav), revision `d127c6ea07af20bde73dd842df255ce58d52e5be`, under MIT. LICENSE and UPSTREAM.md files are retained beside the relevant sources. That license applies to the components it covers.

The project contains custom player adaptation, text compatibility handling, and native UI bindings. Minimal AWTK interface declarations and related adaptation still require a file-level provenance and license review. Equalizer APO application source is not included; full application compatibility is not claimed.

Builders obtain stock V2.43 executables, artwork, fonts, and system files from their own official input. The source tree includes only the added startup hook and insertion metadata, not the complete stock S90play script. The firmware release contains stock material. Local copies stay under ignored `.local/`; their presence alone does not establish redistribution permission.

There is no repository-wide LICENSE yet. Shanling agreed that the project could be published on GitHub on 2026-10-13. This permission is not product validation or a license for unrelated third-party components. Stock software and artwork retain their owners' rights. The licenses and notices of other upstream components still apply.
