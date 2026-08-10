# Content Metadata Standard

An admission and metadata standard for child-safe namespaces, maintained by the
International Foundation for Child-Safe internet Standards (IFC-SiS).

**Status: in preparation.** Version 1.0 is being prepared for release as a draft
for public comment. This repository is the canonical location; the vocabulary
files will be published here under `schema/v1.0/`.

## What this is

A structured classification vocabulary that allows an admission decision about a
domain to be recorded in machine-readable form, transferred between institutions,
and read by independent parties without loss.

The schema is invariant across jurisdictions: the same fields, the same encoding,
so that any conforming system reads any national record. The values inside those
fields are set locally. The comparison is to ISO 8601, which fixes how a date is
written without any opinion about which dates matter.

The Foundation maintains the format. Each jurisdiction determines what goes in it.

## What this is not

The schema contains no field describing the faith, tradition, political alignment
or value system of a domain, and will not. It is not a content policy, not a
blocklist, and not a filtering product.

## Structure

- `schema/` — versioned vocabulary files, one directory per version
- `CHANGELOG.md` — what changed between versions and why
- `LICENSE` — Creative Commons Attribution 4.0 International

Versions are published in their own directories and are not overwritten. A
citation to a version continues to resolve after later versions exist.

## Comment and contest

This standard is published to be argued with. Open an issue in this repository to
raise a question, propose a change, or record a disagreement. Issues are part of
the public record of the standard's development.

Substantive correspondence: shknudson@ifcsis.org

## Companion documents

- *White Paper I: Zoning the Namespace* — land-use law as the legal technology of admission
- *White Paper II: The Admission Layer* — technical architecture

## Citation

International Foundation for Child-Safe internet Standards, *Content Metadata
Standard*, version 1.0 (draft), https://ifc-sis.github.io/content-metadata-standard

## License

Creative Commons Attribution 4.0 International. You may share and adapt this
material for any purpose, including commercially, provided attribution is given.
