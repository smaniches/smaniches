## Santiago Maniches

I build production-grade, provenance-verified tooling at the intersection of AI
and bioinformatics: software that lets an AI agent reach authoritative biomedical
data and prove every answer against its primary source.

TOPOLOGICA LLC (independent research lab) · ORCID [0009-0005-6480-1987](https://orcid.org/0009-0005-6480-1987)

### What I build
- **Provenance-first MCP servers** — Model Context Protocol servers that wrap
  authoritative sources (UniProt, Semantic Scholar, AlphaFold) with per-response
  SHA-256 provenance and independent verification, so AI outputs are auditable
  rather than merely plausible.
- **Reproducible computational research** — preregistered, fully-tested studies
  with SHA-256-locked pre-registrations, where negative results are reported with
  the same prominence as positive ones.

### Why it's hard
Trustworthy biomedical data for AI demands production-science rigor: tamper-evident
audit trails, 100% line-and-branch test coverage, and honest reporting of what is
and isn't validated. These projects are built and maintained to that standard as
single-author work.

### Selected work
- **[uniprot-mcp](https://github.com/smaniches/uniprot-mcp)** — published on PyPI
  (`uniprot-mcp-server`). 41 tools over UniProt with per-response SHA-256 provenance
  and a `uniprot_provenance_verify` tool; 100% test coverage; every claim mapped to
  evidence in `docs/CLAIMS.md`.
- **[semantic-scholar-mcp](https://github.com/smaniches/semantic-scholar-mcp)** —
  published (`s2-mcp-server`). 14 tools over 200M+ papers; SLSA build-provenance
  attestations and a CycloneDX SBOM on every release.
- **[alphafold-sovereign-mcp](https://github.com/smaniches/alphafold-sovereign-mcp)** —
  published. 29 tools over AlphaFold structures and nine biomedical sources; 100%
  test coverage.
- **[homology-cliff](https://github.com/smaniches/homology-cliff)** — a five-paper
  research compendium characterizing a systematic failure mode in frozen
  protein-language-model (ESM-2) biosecurity retrieval; 9,360 pre-registered results
  and a deployable rescue.

### Contact
GitHub [@smaniches](https://github.com/smaniches) · ORCID [0009-0005-6480-1987](https://orcid.org/0009-0005-6480-1987) · TOPOLOGICA LLC
