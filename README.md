# Project T-380

nested journaled objects with copy-on-write semantics

## Features/WIP

- [ ] log-structured document store
- [ ] copy-on-write semantics
- [ ] object is one or more fields
- [ ] fields are interface types
- [ ] a field is a content-addressed reference
- [ ] a field can reference a document
- [ ] a field can reference a journal
- [ ] field references can point offsite
- [ ] reference miss executes callback
- [ ] indexable and searchable by field content
- [ ] fields can be calculated values
- [ ] calculated field values are memoized

- [ ] code for calculated value is stored at reference
- [ ] language of calculated value is our language
- [ ] calculated fields should preserve referential transparency
- [ ] reftran can be tested by app 
- [ ] reftran fail results in new log entry

- [ ] optional, pluggable backing store
- [ ] backing store is an interface
- [ ] backing store interface includes sync()
- [ ] supports hooks for e.g. VCS or FUSE
- [ ] can be used as the storage engine to replace:
    - [ ] copy-on-write immutable objects
    - [ ] git
    - [ ] fuse-overlayfs

- [ ] supports csv, json, yaml I/O
- [ ] can generate formatted table output

