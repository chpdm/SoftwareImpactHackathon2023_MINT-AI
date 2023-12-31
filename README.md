# Identifying missing software citations with LLMs

This project demonstrates the potential use of Large Language Models to: 
- process a paragraph from a scholarly manuscript
- extract entities in this paragraph representing software missing citations
- suggest a canonical citation for each identified software entity 

The project consists of the following subrepos:
- [gpt-cite-notebooks](https://github.com/chpdm/gpt-cite-notebooks): a set of notebooks leveraging GPT3.5 prompts to implement the above workflow.
- [softcite-data-prep](https://github.com/chpdm/softcite-data-prep): the Softcite software mention dataset that was used to train a custom/fine-tuned GPT 3.5 turbo model.
- [manubot-ai-cite](https://github.com/cgreene/manubot-ai-cite): a test application of this workflow in manubot.
- [ai-cite-test-manuscript](https://github.com/chpdm/ai-cite-test-manuscript): a test manuscript template used by manubot.


***

## About this project

This repository was developed as part of the [Mapping the Impact of Research Software in Science](https://github.com/chanzuckerberg/software-impact-hackathon-2023) hackathon hosted by the Chan Zuckerberg Initiative (CZI). By participating in this hackathon, owners of this repository acknowledge the following:
1. The code for this project is hosted by the project contributors in a repository created from a template generated by CZI. The purpose of this template is to help ensure that repositories adhere to the hackathon’s project naming conventions and licensing recommendations.  CZI does not claim any ownership or intellectual property on the outputs of the hackathon. This repository allows the contributing teams to maintain ownership of code after the project, and indicates that the code produced is not a CZI product, and CZI does not assume responsibility for assuring the legality, usability, safety, or security of the code produced.
2. This project is published under a MIT license.

### Team

- Casey Greene ([@cgreene](https://github.com/cgreene))  
- Josh Greenberg ([@epistemographer](https://github.com/epistemographer))  
- Melissa Harrison ([@Melissa37](https://github.com/Melissa37))    
- Arfon Smith ([@arfon](https://github.com/arfon))  
- Dario Taraborelli ([@dartar](https://github.com/dartar))

## Code of Conduct

Contributions to this project are subject to CZI’s Contributor Covenant [code of conduct](https://github.com/chanzuckerberg/.github/blob/master/CODE_OF_CONDUCT.md). By participating, contributors are expected to uphold this code of conduct. 

## Reporting Security Issues

If you believe you have found a security issue, please responsibly disclose by contacting the repository owner via the ‘security’ tab above.
