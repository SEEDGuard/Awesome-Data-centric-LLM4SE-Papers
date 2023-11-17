# Awesome-Data-centric-LLM4SE-Papers


## Data Security


| Paper Id | Title                                                                                         | Venue  | Year | Target Task           | Task Description                                                                                                                  | Used Data                     | Used LLMs              | Replication Package |
|----------|-----------------------------------------------------------------------------------------------|--------|------|-----------------------|-----------------------------------------------------------------------------------------------------------------------------------|-------------------------------|------------------------|---------------------|
| 1        | Backdooring Neural Code Search                                                                | ACL    | 2023 | Code Search           | "Given a natural language description (query), the code search task is to return related code snippets from a large code corpus." | CodeSearchNet                 | "CodeBERT, CodeT5"     |                     |
| 2        | Multi-target Backdoor Attacks for Code Pre-trained Models                                     | ACL    | 2023 | Defect detection      | Predict whether the input code is vulnerable or not                                                                               | CodeXGLUE                     | "PLBART, CodeT5"       |                     |
|          |                                                                                               |        |      | Clone detection       | Predict whether two programs are semantic-equivalent.                                                                             |                               |                        |                     |
|          |                                                                                               |        |      | Code2Code translation | Translate a piece of Java (C#) code to the version of C# (Java).                                                                  |                               |                        |                     |
|          |                                                                                               |        |      | Text2Code             | Generate the source code of class member functions in Java given the natural language description as well as the class context.   |                               |                        |                     |
|          |                                                                                               |        |      | Code refinement       | Fix a piece of buggy Java code and generate its refined version.                                                                  |                               |                        |                     |
| 3        | CoProtector: Protect Open-Source Code against Unauthorized Training Usage with Data Poisoning | WWW    | 2022 | Code generation       | Generate source code based on a natural language description.                                                                     | CodeSearchNet                 | "DeepCS, GPT-2, NCS-T" |                     |
|          |                                                                                               |        |      | Code search           | Retrieve the related code snippets from a codebase given a natural language query                                                 |                               |                        |                     |
|          |                                                                                               |        |      | Code summarization    | Summarize the code snippet into a summary sentence that describes its functionality                                               |                               |                        |                     |
| 4        | You See What I Want You to See: Poisoning Vulnerabilities in Neural Code Search               | FSE    | 2022 | Code search           | "Input: a natural language description (query), Output: related code snippets from a large code corpus."                          | CodeSearchNet                 | "BiRNN, CodeBERT"      |                     |
| 5        | You Autocomplete Me: Poisoning Vulnerabilities in Neural Code Completion                      | USENIX | 2021 | Code Completion       | "Input: Previous k tokens, Output: Next token"                                                                                    | 2800 repositories from Github | GPT-2                  |                     |



## Data Augmentation


## Data Privacy