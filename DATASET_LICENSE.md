# Dataset License

This document summarizes the upstream licensing terms reused for the released PythonEdu-Rs datasets:

- [`Annoy-PythonEdu-Rs`](https://huggingface.co/datasets/liufeftwer145/Annoy-PyEdu-Rs)
- [`Annoy-PythonEdu-Rs-Raw`](https://huggingface.co/datasets/liufeftwer145/Annoy-PyEdu-Rs-Raw)

## Upstream licenses and terms

The PythonEdu-Rs releases reuse the licensing terms from their direct data sources and synthesis model rather than introducing a new project-specific dataset license.

1. **Direct data source:** `Annoy-PythonEdu-Rs-Raw` is derived from the `python-edu` subset of [`HuggingFaceTB/smollm-corpus`](https://huggingface.co/datasets/HuggingFaceTB/smollm-corpus), whose dataset card declares `license: odc-by`. Therefore the dataset-level license for the released PythonEdu-Rs data is [Open Data Commons Attribution License (ODC-BY 1.0)](https://opendatacommons.org/licenses/by/1-0/).
2. **Underlying code provenance:** The Python source files in the upstream `python-edu` subset are extracted from [The Stack v2](https://huggingface.co/datasets/bigcode/the-stack-v2-train-full-ids) / Software Heritage. Source-code-derived fields remain subject to the original licenses of their upstream repositories, including attribution requirements where relevant.
3. **Synthesis model:** `Annoy-PythonEdu-Rs` is synthesized from the raw subset using [DeepSeek-V2.5](https://huggingface.co/deepseek-ai/DeepSeek-V2.5). DeepSeek-V2.5 is distributed under the [DeepSeek Model License / Model Agreement](https://github.com/deepseek-ai/DeepSeek-V2/blob/main/LICENSE-MODEL), whose model card declares `license: other` and `license_name: deepseek`. DeepSeek states that it claims no rights in generated outputs, but use of the model/output must not contravene the DeepSeek Model License.

The raw dataset preserves provenance fields such as `blob_id`, `repo_name`, and `path` to help users trace files back to the upstream source and review the applicable license obligations.

This is not legal advice; users are responsible for confirming that their intended use complies with the upstream licenses.
