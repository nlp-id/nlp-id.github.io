# Language Modeling

## Masked Language Models

| Name                                         | Description                                                                                                                                                                                                          | Author                       | Link                                                                          |
|----------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------|-------------------------------------------------------------------------------|
| IndoConvBERT Base Model                      | IndoConvBERT is a ConvBERT model pretrained on Indo4B.                                                                                                                                                               | Akmal                        | [HuggingFace](https://huggingface.co/Wikidepia/IndoConvBERT-base)             |
| Indonesian BERT Base 1.5G (uncased)          | It is BERT-base model pre-trained with indonesian Wikipedia and indonesian newspapers using a masked language modeling (MLM) objective. This model is uncased.                                                       | Cahya Wirawan                | [HuggingFace](https://huggingface.co/cahya/bert-base-indonesian-1.5G)         |
| Indonesian BERT Base 522M (uncased)          | It is BERT-base model pre-trained with indonesian Wikipedia using a masked language modeling (MLM) objective. This model is uncased: it does not make a difference between indonesia and Indonesia.                  | Cahya Wirawan                | [HuggingFace](https://huggingface.co/cahya/bert-base-indonesian-522M)         |
| Indonesian RoBERTa Base 522M (uncased)       | It is RoBERTa-base model pre-trained with indonesian Wikipedia using a masked language modeling (MLM) objective. This model is uncased: it does not make a difference between indonesia and Indonesia.               | Cahya Wirawan                | [HuggingFace](https://huggingface.co/cahya/roberta-base-indonesian-522M)      |
| Indonesian DistilBERT Base (uncased)         | This model is a distilled version of the Indonesian BERT base model. This model is uncased. This is one of several other language models that have been pre-trained with indonesian datasets.                        | Cahya Wirawan                | [HuggingFace](https://huggingface.co/cahya/distilbert-base-indonesian)        |
| IndoELECTRA                                  | IndoELECTRA is a pre-trained language model based on ELECTRA architecture for the Indonesian Language. This model is base version which use electra-base config.                                                     | Christopher Albert Lorentius | [HuggingFace](https://huggingface.co/ChristopherA08/IndoELECTRA)              |
| Indonesian RoBERTa Base                      | Indonesian RoBERTa Base is a masked language model based on the RoBERTa model. It was trained on the OSCAR dataset, specifically the unshuffled_deduplicated_id subset.                                              | Flax Community               | [HuggingFace](https://huggingface.co/flax-community/indonesian-roberta-base)  |
| Indonesian RoBERTa Large                     | Indonesian RoBERTa Large is a masked language model based on the RoBERTa model. It was trained on the OSCAR dataset, specifically the unshuffled_deduplicated_id subset.                                             | Flax Community               | [HuggingFace](https://huggingface.co/flax-community/indonesian-roberta-large) |
| IndoBERT Base Model (phase1 - uncased)       | IndoBERT is a state-of-the-art language model for Indonesian based on the BERT model. The pretrained model is trained using a masked language modeling (MLM) objective and next sentence prediction (NSP) objective. | Indo Benchmark               | [HuggingFace](https://huggingface.co/indobenchmark/indobert-base-p1)          |
| IndoBERT Base Model (phase2 - uncased)       | IndoBERT is a state-of-the-art language model for Indonesian based on the BERT model. The pretrained model is trained using a masked language modeling (MLM) objective and next sentence prediction (NSP) objective. | Indo Benchmark               | [HuggingFace](https://huggingface.co/indobenchmark/indobert-base-p2)          |
| IndoBERT Large Model (phase1 - uncased)      | IndoBERT is a state-of-the-art language model for Indonesian based on the BERT model. The pretrained model is trained using a masked language modeling (MLM) objective and next sentence prediction (NSP) objective. | Indo Benchmark               | [HuggingFace](https://huggingface.co/indobenchmark/indobert-large-p1)         |
| IndoBERT Large Model (phase2 - uncased)      | IndoBERT is a state-of-the-art language model for Indonesian based on the BERT model. The pretrained model is trained using a masked language modeling (MLM) objective and next sentence prediction (NSP) objective. | Indo Benchmark               | [HuggingFace](https://huggingface.co/indobenchmark/indobert-large-p2)         |
| IndoBERT-Lite Base Model (phase1 - uncased)  | IndoBERT is a state-of-the-art language model for Indonesian based on the BERT model. The pretrained model is trained using a masked language modeling (MLM) objective and next sentence prediction (NSP) objective. | Indo Benchmark               | [HuggingFace](https://huggingface.co/indobenchmark/indobert-lite-base-p1)     |
| IndoBERT-Lite Base Model (phase2 - uncased)  | IndoBERT is a state-of-the-art language model for Indonesian based on the BERT model. The pretrained model is trained using a masked language modeling (MLM) objective and next sentence prediction (NSP) objective. | Indo Benchmark               | [HuggingFace](https://huggingface.co/indobenchmark/indobert-lite-base-p2)     |
| IndoBERT-Lite Large Model (phase1 - uncased) | IndoBERT is a state-of-the-art language model for Indonesian based on the BERT model. The pretrained model is trained using a masked language modeling (MLM) objective and next sentence prediction (NSP) objective. | Indo Benchmark               | [HuggingFace](https://huggingface.co/indobenchmark/indobert-lite-large-p1)    |
| IndoBERT-Lite Large Model (phase2 - uncased) | IndoBERT is a state-of-the-art language model for Indonesian based on the BERT model. The pretrained model is trained using a masked language modeling (MLM) objective and next sentence prediction (NSP) objective. | Indo Benchmark               | [HuggingFace](https://huggingface.co/indobenchmark/indobert-lite-large-p2)    |
| IndoBERT Base (uncased)                      | IndoBERT is the Indonesian version of BERT model. The model was trained using over 220M words, aggregated from three main sources: Indonesian Wikipedia, news articles, and an Indonesian Web Corpus.                | IndoLEM                      | [HuggingFace](https://huggingface.co/indolem/indobert-base-uncased)           |
| IndoBERT (Indonesian BERT Model)             | IndoBERT is a pre-trained language model based on BERT architecture for the Indonesian Language. This model is base-uncased version which use bert-base config.                                                      | Sarah Lintang                | [HuggingFace](https://huggingface.co/sarahlintang/IndoBERT)                   |
| Indo RoBERTa Small                           | Indo RoBERTa Small is a masked language model based on the RoBERTa model. It was trained on the latest (late December 2020) Indonesian Wikipedia articles.                                                           | Wilson Wongso                | [HuggingFace](https://huggingface.co/w11wo/indo-roberta-small)                |

## Causal/Generative Language Models

| Name                                                       | Description                                                                                                                                                                                          | Author                 | Link                                                                                     |
|------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------|------------------------------------------------------------------------------------------|
| Indonesian GPT2 Small 522M                                 | It is GPT2-small model pre-trained with indonesian Wikipedia using a causal language modeling (CLM) objective. This model is uncased: it does not make a difference between indonesia and Indonesia. | Cahya Wirawan          | [HuggingFace](https://huggingface.co/cahya/gpt2-small-indonesian-522M)                   |
| GPT2-small-indonesian                                      | This is a pretrained model on Indonesian language using a causal language modeling (CLM) objective. The training data used for this model are Indonesian websites of OSCAR, mc4 and Wikipedia.       | Flax Community         | [HuggingFace](https://huggingface.co/flax-community/gpt2-small-indonesian)               |
| GPT2-medium-indonesian                                     | This is a pretrained model on Indonesian language using a causal language modeling (CLM) objective. The training data used for this model are Indonesian websites of OSCAR, mc4 and Wikipedia.       | Flax Community         | [HuggingFace](https://huggingface.co/flax-community/gpt2-medium-indonesian)              |
| Indonesian GPT-2 finetuned on Indonesian academic journals | This is the Indonesian gpt2-small model fine-tuned to abstracts of Indonesian academic journals. All training was done on a TPUv2-8 VM sponsored by TPU Research Cloud.                              | Galuh                  | [HuggingFace](https://huggingface.co/Galuh/id-journal-gpt2)                              |
| Indonesian GPT-2-medium finetuned on Indonesian poems      | This is the Indonesian gpt2-medium model fine-tuned to Indonesian poems.                                                                                                                             | Muhammad Agung Hambali | [HuggingFace](https://huggingface.co/ayameRushia/gpt2-medium-fine-tuning-indonesia-poem) |
| Indonesian GPT-2 finetuned on Indonesian poems             | This is the Indonesian gpt2-small model fine-tuned to Indonesian poems.                                                                                                                              | Muhammad Agung Hambali | [HuggingFace](https://huggingface.co/ayameRushia/gpt2-small-indonesia-fine-tuning-poem)  |
| Indo GPT-2 Small                                           | Indo GPT-2 Small is a language model based on the GPT-2 model. It was trained on the latest (late December 2020) Indonesian Wikipedia articles.                                                      | Wilson Wongso          | [HuggingFace](https://huggingface.co/w11wo/indo-gpt2-small)                              |

## Datasets
| Name                       | Description                                                                                                                                                                                                                                                                                                                                                         | Author                                                                                                                                                            | Link                                                                       |
|----------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------|
| mC4-sampling               | This dataset builds upon the AllenAI version of the original mC4 and adds sampling methods to perform perplexity-based filtering on the fly. Please, refer to BERTIN Project.                                                                                                                                                                                       | BERTIN Project & Colin Raffel and Noam Shazeer and Adam Roberts and Katherine Lee and Sharan Narang and Michael Matena and Yanqi Zhou and Wei Li and Peter J. Liu | [HuggingFace](https://huggingface.co/datasets/bertin-project/mc4-sampling) |
| OPUS-100                   | OPUS-100 is English-centric, meaning that all training pairs include English on either the source or target side. The corpus covers 100 languages (including English). Selected the languages based on the volume of parallel data available in OPUS.                                                                                                               | Biao Zhang and Philip Williams and Ivan Titov and Rico Sennrich                                                                                                   | [HuggingFace](https://huggingface.co/datasets/opus100)                     |
| mC4                        | A multilingual colossal, cleaned version of Common Crawl's web crawl corpus. Based on Common Crawl dataset: "[https://commoncrawl.org](https://commoncrawl.org)".                                                                                                                                                                                                   | Colin Raffel and Noam Shazeer and Adam Roberts and Katherine Lee and Sharan Narang and Michael Matena and Yanqi Zhou and Wei Li and Peter J. Liu                  | [HuggingFace](https://huggingface.co/datasets/mc4)                         |
| Indonesian Newspapers 2018 | The dataset contains around 500K articles (136M of words) from 7 Indonesian newspapers: Detik, Kompas, Tempo, CNN Indonesia, Sindo, Republika and Poskota. The articles are dated between 1st January 2018 and 20th August 2018 (with few exceptions dated earlier).                                                                                                | Feryandi Nurdiantoro                                                                                                                                              | [HuggingFace](https://huggingface.co/datasets/id_newspapers_2018)          |
| Indonesia Puisi            | Puisi (poem) is an Indonesian poetic form. The dataset contains 7223 Indonesian puisi with its title and author.                                                                                                                                                                                                                                                    | Ilham Firdausi Putra                                                                                                                                              | [HuggingFace](https://huggingface.co/datasets/id_puisi)                    |
| OSCAR                      | OSCAR or Open Super-large Crawled ALMAnaCH coRpus is a huge multilingual corpus obtained by language classification and filtering of the Common Crawl corpus using the goclassy architecture. Data is distributed by language in both original and deduplicated form.                                                                                               | Ortiz Suárez, Pedro Javier and Romary, Laurent and Sagot, Benoit                                                                                                  | [HuggingFace](https://huggingface.co/datasets/oscar)                       |
| CC100                      | This corpus is an attempt to recreate the dataset used for training XLM-R. This corpus comprises of monolingual data for 100+ languages and also includes data for romanized languages (indicated by *_rom). This was constructed using the urls and paragraph indices provided by the CC-Net repository by processing January-December 2018 Commoncrawl snapshots. | Wenzek, Guillaume and Lachaux, Marie-Anne and Conneau, Alexis and Chaudhary, Vishrav and Guzmán, Francisco and Joulin, Armand and Grave, Edouard                  | [HuggingFace](https://huggingface.co/datasets/cc100)                       |
| Wikipedia                  | Wikipedia dataset containing cleaned articles of all languages. The datasets are built from the Wikipedia dump ([https://dumps.wikimedia.org/](https://dumps.wikimedia.org/)) with one split per language. Each example contains the content of one full Wikipedia article with cleaning to strip markdown and unwanted sections (references, etc.).                | Wikimedia Foundation                                                                                                                                              | [HuggingFace](https://huggingface.co/datasets/wikipedia)                   |