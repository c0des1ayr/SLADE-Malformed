## SLADE Malformed
It's (mostly) an SRB2 Editor

### About

This fork of SLADE3 adds the CVar `zip_save_with_duplicate_entries`, which allows for saving (malformed) PK3s and ZIPs with duplicate entries names. This is WIP, as trying to close SLADE while the CVar is enabled will cause it to hang instead. Make sure to disable `zip_save_with_duplicate_entries` before closing!
