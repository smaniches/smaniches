# Santiago Maniches

**Software engineering | AI/ML infrastructure | Scientific computing**

I build Python software for AI-assisted research and data-intensive systems. My focus is the engineering that has to work beyond a demonstration: reliable APIs, explicit data contracts, source traceability, offline behavior, regression tests, and reproducible releases.

I am pursuing software engineering, AI/ML infrastructure, and research engineering roles. The work below is public, inspectable code.

## Selected open-source systems

### [UniProt MCP Server](https://github.com/smaniches/uniprot-mcp) | Scientific APIs and verifiable data

A Python MCP server exposing **41 documented tools** for protein and variant research. It preserves source URLs, retrieval times, release identifiers when provided, and SHA-256 evidence. Its UniProt verification path can detect when a previously captured upstream record has changed; it does not certify third-party biomedical conclusions.

**Inspect:** [tool documentation](https://github.com/smaniches/uniprot-mcp/blob/main/docs/tools.md) · [real TP53 capture and contract test](https://github.com/smaniches/uniprot-mcp/blob/main/tests/contract/test_tp53_capture_binding.py) · [release reproduction script](https://github.com/smaniches/uniprot-mcp/blob/main/scripts/replicate.sh)

### [Semantic Scholar MCP Server](https://github.com/smaniches/semantic-scholar-mcp) | API resilience and software supply chain

A **14-tool** MCP integration for literature search, citation graphs, authors, and recommendations. Engineering work includes identifier validation, bounded retries and rate limiting, typed error handling, and installable Python and container releases with build provenance and a software bill of materials.

**Inspect:** [HTTP client](https://github.com/smaniches/semantic-scholar-mcp/blob/main/src/semantic_scholar_mcp/client.py) · [input validators](https://github.com/smaniches/semantic-scholar-mcp/blob/main/src/semantic_scholar_mcp/validators.py) · [release workflow](https://github.com/smaniches/semantic-scholar-mcp/blob/main/.github/workflows/publish.yml)

### [AlphaFold Sovereign MCP](https://github.com/smaniches/alphafold-sovereign-mcp) | Local-first biomedical integration

A Python MCP server connecting AlphaFold DB and other public biomedical sources, with a local SQLite knowledge graph. An explicit offline mode refuses outbound network requests. Cross-source joins, identifier matching, and derived research heuristics retain documented uncertainty; the system is not clinically validated.

**Inspect:** [knowledge graph](https://github.com/smaniches/alphafold-sovereign-mcp/blob/main/src/alphafold_sovereign/storage/knowledge_graph.py) · [status and acceptance boundaries](https://github.com/smaniches/alphafold-sovereign-mcp/blob/main/STATUS.md) · [known limitations](https://github.com/smaniches/alphafold-sovereign-mcp/blob/main/LIMITATIONS.md)

## Scientific and numerical software

- **[TopoGeoML](https://github.com/smaniches/TopoGeoML):** Python toolkit for topology-aware ML, including train-fitted transforms, simplicial operators, and experimental PyTorch losses. Its separate graph-classification study reports negative results rather than claiming an uplift.
- **[PCA and persistent-homology replication](https://github.com/smaniches/pca-topology-crossdomain-replication):** Reproducible multi-cohort analysis, controls, explicit methodological corrections, and an executable audit trail. Biological interpretation remains bounded by the evidence.
- **[Homology Cliff](https://github.com/smaniches/homology-cliff):** Frozen protein-language-model retrieval evaluation, archived computational evidence, calibration/failure analysis, and a published erratum.

## How I evaluate my work

I separate source-reported facts from derived inference, verify artifacts against their actual inputs, preserve negative results, and document failure modes before making deployment claims. Tests, signatures, provenance receipts, and AI-assisted reviews do not replace independent scientific or security validation. AI tools have assisted implementation and internal review; I direct the work and remain responsible for the conclusions and releases.

**Connect:** [LinkedIn](https://www.linkedin.com/in/santiagomaniches) · [ORCID](https://orcid.org/0009-0005-6480-1987) · [Kaggle](https://www.kaggle.com/santmani)
