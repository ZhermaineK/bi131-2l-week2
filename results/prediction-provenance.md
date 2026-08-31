# Prediction Provenance Record

- **Assigned UniProt Accession:** P01308
- **Primary Prediction Route:** AlphaFold Database (AFDB)
- **Secondary Route Status:** AlphaFold Server submitted / pending
- **Retrieval Date:** 2026-08-31
- **AFDB Entry URL:** https://alphafold.ebi.ac.uk/entry/P01308

## Preserved Files and Checksums

| Filename | Description | MD5 Checksum |
| :--- | :--- | :--- |
| `results/afdb_model.pdb` | AlphaFold DB PDB structure model | $(md5 -q results/afdb_model.pdb || md5sum results/afdb_model.pdb | awk '{print $1}') |
| `results/afdb_pae.json` | AlphaFold DB PAE json data | $(md5 -q results/afdb_pae.json || md5sum results/afdb_pae.json | awk '{print $1}') |
