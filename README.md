# Imageomics Guide

Welcome to the Imageomics Guide!

Just joining or starting a new project? 
Checkout the [Imageomics Guide](https://imageomics.github.io/Imageomics-guide/) for guidance on conventions and best practices.


## Templates

### Hugging Face
We have Imageomics-specific versions of Hugging Face's Dataset and Model Card templates with guidance and examples, along with some reference information for their flavor of markdown and the Imageomics grant information. 

To use the template for a new dataset or model repository on Hugging Face (HF), just navigate to the "Model/Dataset Card" tab on your repo, select "Create Model/Dataset Card", then copy and paste the contents of the appropriate template ([Dataset Card](docs/wiki-guide/HF_DatasetCard_Template_Imageomics.md?plain=1) or [Model Card](docs/wiki-guide/HF_ModelCard_Template_Imageomics.md?plain=1)) into the README.md file. For more information on working with Hugging Face, see the [HF Repo Guide](https://imageomics.github.io/Imageomics-guide/wiki-guide/Hugging-Face-Repo-Guide/) and [HF Workflow](https://imageomics.github.io/Imageomics-guide/wiki-guide/The-Hugging-Face-Workflow/) entries in the [Imageomics Guide](https://imageomics.github.io/Imageomics-guide/).

> [!NOTE]
> The Dataset and Model cards have incorporated some of Hugging Face's January 2024 updates (following their [Dataset Card Overhaul](https://github.com/huggingface/huggingface_hub/commit/6dd7ee829bd1b1216663a9993c1943c29b64690a)). It doesn't appear they will be updated more and we do not currently anticipate further large updates on our end as our overall template formats have diverged, but you may nevertheless wish to check HF for extra information or tagging updates ([HF Dataset Card](https://github.com/huggingface/huggingface_hub/blob/main/src/huggingface_hub/templates/datasetcard_template.md), [HF Model Card](https://github.com/huggingface/huggingface_hub/blob/main/src/huggingface_hub/templates/modelcard_template.md)).


## Testing
To test this site locally, first clone this repository, then create an environment with `requirements.txt`
```
pip install -r requirements.txt
```
and run `mkdocs serve`:
```
mkdocs serve
```
Then the site will run at http://127.0.0.1:8000/Imageomics-guide/.
