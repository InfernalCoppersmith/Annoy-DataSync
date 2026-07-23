# Dataset License

This document summarizes the licensing terms for the released PythonEdu-Rs datasets:

- [`Annoy-PythonEdu-Rs`](https://huggingface.co/datasets/liufeftwer145/Annoy-PyEdu-Rs)
- [`Annoy-PythonEdu-Rs-Raw`](https://huggingface.co/datasets/liufeftwer145/Annoy-PyEdu-Rs-Raw)

## Summary

`Annoy-PythonEdu-Rs-Raw` is derived from the `python-edu` subset of [`HuggingFaceTB/smollm-corpus`](https://huggingface.co/datasets/HuggingFaceTB/smollm-corpus), which is released with `license: odc-by`. The Python source files in that upstream subset are extracted from [The Stack v2](https://huggingface.co/datasets/bigcode/the-stack-v2-train-full-ids) / Software Heritage. `Annoy-PythonEdu-Rs` is produced by applying the Annoy data-processing pipeline to the raw PythonEdu-Rs subset.

Accordingly, both released PythonEdu-Rs datasets should be used under the following terms:

1. Dataset-level curation, annotations, processing outputs, and dataset-card materials are released under the [Open Data Commons Attribution License (ODC-BY 1.0)](https://opendatacommons.org/licenses/by/1-0/).
2. Included source-code-derived fields remain subject to the original licenses of their upstream repositories as provided through The Stack v2 / Software Heritage provenance. Any reuse of code content must comply with the applicable original license terms, including attribution requirements where relevant.
3. The raw dataset preserves provenance fields such as `blob_id`, `repo_name`, and `path` to help users trace files back to the upstream source and review the applicable license obligations.

This is not legal advice; users are responsible for confirming that their intended use complies with the upstream licenses.
