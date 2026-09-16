# PDF Catalog

This is the human-readable index of published research objects. Add one row for every PDF and link its companion metadata record.

| ID | Date | Provider / model as displayed | Session state | Subject | PDF | Metadata | Status |
|---|---|---|---|---|---|---|---|
| — | — | — | — | First PDF awaiting upload | — | — | Pending |

## Session-state vocabulary

- **Cold/default:** a new or substantially context-free interaction intended to expose default behavior.
- **Cold with supplied object:** a new interaction in which the model receives a defined source object but no prior relational history.
- **Continuation:** the interaction has access to earlier turns in the same conversation.
- **Context-rich:** substantial project material or prior correction history is present.
- **Comparative:** the same or closely matched object is tested across models or conditions.
- **Unresolved:** the available record does not justify a more specific state.

## Status vocabulary

- **Source record:** preserved interaction without a project verdict.
- **Under review:** representation or metadata is still being checked.
- **Corrected:** a later version or correction record exists.
- **Comparative analysis available:** a separate comparison links to this record.
- **Superseded:** retained for provenance after replacement.

Machine-readable entries are maintained in [DATA/catalog.csv](DATA/catalog.csv). Integrity hashes are recorded in [DATA/checksums.sha256](DATA/checksums.sha256).
