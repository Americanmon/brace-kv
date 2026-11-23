Code and data release for "BRACE-KV: Risk-Controlled Budget Selection for KV-Cache Compression" (Findings of EACL 2027).

- brace-kv-code.tgz: budget policy code, calibration routines, reproduction scripts, and GPU entry points
- brace-kv-data.tgz: task scores, stable budget requirements, prompt features, split manifests, frozen release-score checkpoints, and prediction tables
- SHA256SUMS: checksums for both archives

Extract both archives into the same directory and follow README.md in brace-kv-code. The CPU reproduction regenerates every table and figure in the paper from the stored results in about two minutes, without a GPU.

Released under the MIT License.
