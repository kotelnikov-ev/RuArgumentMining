# ArgBERT

ArgBERT – нейросетевая языковая модель типа BERT, позволяющая осуществлять бинарную классификацию предложений на «аргумент» / «не аргумент». Модель основана на дообучении модели [sbert_large_mt_nlu_ru](https://huggingface.co/sberbank-ai/sbert_large_mt_nlu_ru) с использованием переводных версий корпусов с разметкой по аргументации ArgMicro, Persuasive Essays и UKP Sentential Argument Mining Corpus.

Ссылка на модель: [https://goo-gl.me/S8xHy](https://goo-gl.me/S8xHy).

# ArgBERT-premise

ArgBERT-premise – нейросетевая языковая модель типа BERT, позволяющая классифицировать аргументативные предложения, извлеченные моделью ArgBERT, на два класса: «аргумент за» / «аргумент против». Модель получена за счет дообучения модели ArgBERT на части указанных аргументационных корпусов, включающей только аргументативные предложения.

Ссылка на модель: [https://goo-gl.me/gssrc](https://goo-gl.me/gssrc).
