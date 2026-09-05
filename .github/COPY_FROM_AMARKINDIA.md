This repository will receive a bulk copy of files from https://github.com/amark-india/eventspotter.

What will be copied (per instruction):
- All source code (src/), data/, evaluation/, report/, paper/, and top-level files (README.md, LICENSE, build files, etc.).

What will be excluded to avoid API size/rate limits and huge binaries:
- All JARs under lib/ (lib/*.jar and lib/**/.jar)
- Generated API docs under lib/**/apidocs/**

Notes:
- The copy will be performed via the GitHub API in a sequence of commits (batched), because uploading many files in a single request may hit size limits.
- Commit history from the original repository will NOT be preserved; this is a file-content copy only.

If you need different exclusions, reply and I will adjust before proceeding with the bulk upload.
