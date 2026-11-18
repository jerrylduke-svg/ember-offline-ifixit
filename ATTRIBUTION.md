# Source and contributor attribution

- iFixit and its contributing authors/teams: https://www.ifixit.com/
- iFixit content license: https://www.ifixit.com/Info/Licensing
- CC BY-NC-SA 3.0: https://creativecommons.org/licenses/by-nc-sa/3.0/
- Source archive: https://download.kiwix.org/zim/ifixit/ifixit_en_all_2025-12.zim
- Archive creator metadata: iFixit; publisher metadata: openZIM.

## Finding supplied credits

Each `credits/ifixit-en-part-NNNN.jsonl.gz` decompresses to UTF-8 JSON Lines. Each row binds package/version/document identity, archived source URL and entry, raw/adapted resource paths and SHA-256 hashes, and ordered supplied references. `references[].supplied_labels` contains supplied names/labels; `href` is the exact archived relative reference. `has_blank_anchor` records an anchor with no nonblank visible label. Resolve such references only with the original archive's documented path rules, not by assuming a live website route. These source-relative paths are collection paths, not user filesystem locations.

The source URL identifies the actual archive and exact entry context. Retain these bindings, the supplied contributor labels and original article credits when redistributing. The supplement covers selected author/team references, not every original outbound link, comment credit, media-specific notice or revision history. Original source resources and all their notices remain authoritative.

## Separate embedding model

`sentence-transformers/all-MiniLM-L6-v2`, revision 1110a243fdf4706b3f48f1d95db1a4f5529b4d41, `onnx/model_qint8_arm64.onnx`, from https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2/tree/1110a243fdf4706b3f48f1d95db1a4f5529b4d41 . Apache 2.0; preserve `MODEL-LICENSE.txt` and `MODEL-NOTICE.txt` (copied byte-exact from the shared package). Model SHA-256 4278337fd0ff3c68bfb6291042cad8ab363e1d9fbc43dcb499fe91c871902474. No affiliation or endorsement implied.
