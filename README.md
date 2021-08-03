### Treball de Fi de Màster - Universitat Autònoma de Barcelona
## Fine-tune a Neural Machine Translation Model for Legal Domain: theories explained and practice with Hugging Face

*Fine-tuned model pushed to Hugging Face 🤗 Hub: https://huggingface.co/guocheng98/HelsinkiNLP-FineTuned-Legal-es-zh*



This repo functions as complementary materials of the author's master thesis. It contains codes for the Methodology chapter, part of the parallel corpus files, and the full text of the master thesis.

1. **ChinaLawInfo_Spanish**: Spanish translations found on *BOE (Boletín Oficial del Estado)* and EUR-Lex of files downloaded from *China Law Info (北大法宝 Beida Fabao)*.
2. **CivilCode_Spanish**: Spanish Civil Code parsed from an HTML file. The folder contains the HTML file (BOE.html), the processing code (Processing codes.ipynb), and the TXT files obtained.
3. **Constitution**: the original text of Spanish Constitution and its translation into Simplified Chinese.
4. **Extract data from TMX.ipynb**: Jupyter Notebook file; code of extracting structurally the textual information from the translation memory file.
5. **HuggingFace_Fine-tune.ipynb**: Jupyter Notebook file; code of the whole fine-tuning process.
6. **HuggingFace_gettingtranslation.ipynb**: Jupyter Notebook file; code of the inference stage where we obtain the machine translation outputs of the original and the fine-tuned models.
7. **Full_text.pdf**: Full text of the author's master thesis.
8. **Other TXT files**:
    - Test_es.txt: Spanish part of the test set.
    - Test_zh.txt: Simplified Chinese part of the test set.
    - Translation_FT.txt: machine translation outputs of the fine-tuned model, with Test_es.txt as the source text.
    - Translation_original.txt: machine translation outputs of the original model, with Test_es.txt as the source text.
