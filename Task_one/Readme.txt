
AVIP 2026 Generative AI Internship — Task 1
Project status
This is an audit and recovery package, not yet a complete submission. The 20 prompts are included, along with one non-empty file per prompt. However, only the responses for prompts 18–20 were visible in enough detail in the available conversation to copy into this package. Files 01–17 are clearly marked as unrecovered original outputs and must be replaced with the original text before submission.

The official internship task PDF was not present in the available conversation uploads or searchable file library. The official naming convention and full rubric therefore remain unverified. Do not treat this folder name as an official required convention.

Project overview
Task 1 consists of text-generation prompts on 20 AI, computing, science, education, and technology topics. The aim is to preserve the exact prompts and their generated responses, document the generation method, and provide a short qualitative evaluation.

Model, source, and generation method
Tool visible in the conversation: ChatGPT web/app interface.
Generation method: Manual prompting through the ChatGPT conversational interface; responses were copied from assistant messages. No API call, local inference run, or model execution script is evidenced by the available history.
Exact model/version: Not recoverable for each earlier response from the available conversation. Do not assume that the current model identity equals the version that generated every historical sample.
Official service terms: https://openai.com/policies/row-terms-of-use/
Model licence: A hosted ChatGPT model is not a downloadable model checkpoint for this project. The applicable service terms govern use of the hosted service and its outputs; do not describe it as Apache/MIT/open-source licensed. OpenAI's terms state that, as between the user and OpenAI and to the extent permitted by law, the user owns the output, while also warning that outputs may be inaccurate and must be evaluated. Read the current terms directly before submission.
Official model information: https://help.openai.com/en/articles/20001354-gpt-6-and-other-models-in-chatgpt (current model-picker information only; it does not prove which model generated older samples).
Setup
No local model setup is required to reproduce the documented historical method: open ChatGPT, submit the prompts in prompts.txt, and save each response as plain text. Re-running a prompt may produce a different response, so do not overwrite historical samples with new responses without labelling them as regenerated.

To validate the package using Python 3:

python validate_project.py
The validator checks the expected filenames, prompt count, empty files, and whether any file is marked as an unrecovered output. A successful structural check does not mean all original outputs have been recovered.

Repository structure
AVIP_2026_Generative_AI_Task_1/
├── README.md
├── prompts.txt
├── generation_method.md
├── evaluation_summary.md
├── audit_report.md
├── validate_project.py
└── generated_samples/
    ├── 01_ai_in_healthcare.txt
    ├── ...
    └── 20_future_of_artificial_intelligence.txt
Important submission note
Before submitting, retrieve and include the official AVIP task PDF/rubric, replace all recovery-marker files with the actual original outputs, confirm the required naming convention, and rerun the validator. Do not submit this package as if all 20 original outputs were present.

