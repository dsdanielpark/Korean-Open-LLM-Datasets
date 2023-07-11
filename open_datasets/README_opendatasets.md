
# Datasets
##  `#1` [danielpark/ko_shargpt_deepl_translate_cleaned_v1](https://huggingface.co/datasets/danielpark/ko_shargpt_deepl_translate_cleaned_v1)

I have extracted translation pairs from the [junelee/sharegpt_deepl_ko](https://huggingface.co/datasets/junelee/sharegpt_deepl_ko) dataset using [src/preprocessing/data_gen.py](https://github.com/dsdanielpark/ko-sharegpt-deepl-alpaca/blob/main/src/preprocessing/data_gen.py) and made some corrections to the parts that were awkwardly interpreted in Korean using the algorithm in [src/preprocessing/data_cleaner.py](https://github.com/dsdanielpark/ko-sharegpt-deepl-alpaca/blob/main/src/preprocessing/data_cleaner.py).

### Raw data from [junelee/sharegpt_deepl_ko](https://huggingface.co/datasets/junelee/sharegpt_deepl_ko)
- `ko_sharegpt.json`
- `original_shargpt.json`

### Modified and preprocessed dataset for language translation.
- `ko_shargpt_deepl_translate_cleaned_v1.json`: The dataset extracted and preprocessed using the algorithm to make only the Korean text more natural, as described above. [danielpark/ko_shargpt_deepl_translate_cleaned_v1](https://huggingface.co/datasets/danielpark/ko_shargpt_deepl_translate_cleaned_v1)
- `ko_shargpt_deepl_cleaned_v2.json`: Certain portions have been manually deleted or corrected by human inspection from v1.

<br>


## `#2` [ko_shargpt_google_translate_cleaned_v1.json](https://huggingface.co/datasets/danielpark/ko_shargpt_google_translate_cleaned_v1)
I have extracted translation pairs from the [dbdu/ShareGPT-74k-ko](https://huggingface.co/datasets/dbdu/ShareGPT-74k-ko/tree/main) dataset using 


### Raw data from [dbdu/ShareGPT-74k-ko](https://huggingface.co/datasets/dbdu/ShareGPT-74k-ko/tree/main)


### Modified and preprocessed dataset for language translation.
- `ko_shargpt_google_translate_cleaned_v1.json`: The dataset extracted and preprocessed using the algorithm to make only the Korean text more natural, as described above.
- `ko_shargpt_google_translate_cleaned_v2.json`: Certain portions have been manually deleted or corrected by human inspection from v1.

<br>


## `#Others`

1. [KoAlpaca v1.0](https://huggingface.co/datasets/Bingsu/ko_alpaca_data)
2. [KoAlpaca v1.1](https://raw.githubusercontent.com/Beomi/KoAlpaca/main/KoAlpaca_v1.1.jsonl)
3. [ShareGPT using DeepL](https://huggingface.co/datasets/junelee/sharegpt_deepl_ko)
4. [KoChatGPT](https://github.com/airobotlab/KoChatGPT)
5. [OIG-small-chip2-ko](https://huggingface.co/datasets/heegyu/OIG-small-chip2-ko)
6. [Korquad-Chat](https://huggingface.co/datasets/heegyu/korquad-chat-v1)
7. [AIRC-KETI/kowow](https://github.com/AIRC-KETI/kowow)
8. [smilegate-ai/HuLiC](https://github.com/smilegate-ai/HuLiC)
9. [smilegate-ai/OPELA](https://github.com/smilegate-ai/OPELA)
10. [CounselGPT](https://github.com/MrBananaHuman/CounselGPT)
11. [Evolve-instruct](https://github.com/lcw99/evolve-instruct/)
12. [KULLM v2](https://huggingface.co/datasets/nlpai-lab/kullm-v2)
13. [SharGPT-74K-Kor-GoogleTranslator](https://huggingface.co/datasets/dbdu/ShareGPT-74k-ko)