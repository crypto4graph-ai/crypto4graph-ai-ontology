# crypto4graph-ai ontology

Ontology Repository

## Requirements

To execute the ontology pipeline you need:
- [Task](https://taskfile.dev/)
- [Docker](https://www.docker.com/), [Podman](https://podman.io/), or a compatible container engine
- [Python 3](https://www.python.org/)

Further documentation of the ontology pipeline is available at https://github.com/eccenca/ontology-pipeline-template .

## TODO

- [ ] 🛠️ Adjust config in `cmemc.ini` (Find details on [documentation.eccenca.com](https://documentation.eccenca.com/latest/automate/cmemc-command-line-interface/configuration/file-based-configuration/))
- [ ] 📡 Make sure to setup a remote for `git push`
- [ ] 🔗 Create a `prefixes.ttl`
- [ ] 📑 Make sure `vocab.ttl`, `vocab.nt`, and `vocab.nt.graph` exist
- [ ] 📝 Make sure `shapes.ttl`, `shapes.nt`, and `shapes.nt.graph` exist
- [ ] 💾 Commit the newly created files

## Build Artifacts

The build artifacts are generated in the directory `artifacts`. In the GitHub Action Workflow the artifacts are attached to a successful build.

### Pipeline Artifacts
- The Ontology Documentation:
  - `schema-documentation.html`
- The RDFUnit test results:
  - `check-rdfunit-auto-results.html`
  - `check-rdfunit-auto-results.xml`
  - `check-rdfunit-manual-results.html`
  - `check-rdfunit-manual-results.xml`
