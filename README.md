# Russian Words on the US License Plates
Transliteration of Russian dictionary for US license plates
Транслитерация русских слов для номеров авто США

Many US states allow customized license plates. Here's a dictionary for those of you who want to use Russian words on your plate: https://docs.google.com/spreadsheets/d/1RUIafOwZWmTg2UBlE6YCZPEsv4EDr64wT3HPPFG8qkU/edit?usp=sharing

The Python code in the repo takes the frequency dictionary and transliterates each word. I'm using the transliterate package by Artur Barseghyan (https://pypi.org/project/transliterate/).

Files list and description:
- ru_freq_dict.txt - original dictionary file in windows-1251 encoding (source: http://www.speakrus.ru/dict/hagen_freq_desc.rar)
- ru_freq_dict_utf.txt - original dictionary file in UTF-8 encoding
- hagen_freq_desc.txt - dictionary description and structure
- ru_freq_dict_translit_full.csv - the full dictionary with transliteration
- ru_freq_dict_translit.csv - the dictionary that only includes transliterated words between 3 and 7 symbols long
- ru_words_for_plates.ipynb - Python code
