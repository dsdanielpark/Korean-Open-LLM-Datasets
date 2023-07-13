
## DataSets
###  `#1` [`danielpark/ko_shargpt_deepl_translate_cleaned_v1`](https://huggingface.co/datasets/danielpark/ko_shargpt_deepl_translate_cleaned_v1)

I have extracted translation pairs from the [junelee/sharegpt_deepl_ko](https://huggingface.co/datasets/junelee/sharegpt_deepl_ko) dataset using [src/preprocessing/data_gen.py](https://github.com/dsdanielpark/ko-sharegpt-deepl-alpaca/blob/main/src/preprocessing/data_gen.py) and made some corrections to the parts that were awkwardly interpreted in Korean using the algorithm in [src/preprocessing/data_cleaner.py](https://github.com/dsdanielpark/ko-sharegpt-deepl-alpaca/blob/main/src/preprocessing/data_cleaner.py).

#### Raw data from [junelee/sharegpt_deepl_ko](https://huggingface.co/datasets/junelee/sharegpt_deepl_ko)
- `ko_sharegpt.json`
- `original_shargpt.json`

#### Modified and preprocessed dataset for language translation.
- `ko_shargpt_deepl_translate_cleaned_v1.json`: The dataset extracted and preprocessed using the algorithm to make only the Korean text more natural, as described above. [danielpark/ko_shargpt_deepl_translate_cleaned_v1](https://huggingface.co/datasets/danielpark/ko_shargpt_deepl_translate_cleaned_v1)
- `ko_shargpt_deepl_cleaned_v2.json`: Certain portions have been manually deleted or corrected by human inspection from v1.
