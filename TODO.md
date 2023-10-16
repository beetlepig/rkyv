- [ ] Update all dependencies to the latest versions
- [ ] Reformat line width
- [ ] Make core traits unsafe
- [ ] Get rid of out_field! if possible
- [ ] Re-enable RawArchivedVec. Move core data structure into shared struct and
      have RawArchivedVec and ArchivedVec be wrappers on top of it with
      different validation implementations.