### Fine-tuning 6-Billion GPT-J (& other models) in colab with LoRA and 8-bit compression [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/gustavecortal/gpt-j-fine-tuning-example/blob/main/finetune_8bit_models.ipynb)

This notebook is a simple example for fine-tuning [GPT-J-6B](https://huggingface.co/EleutherAI/gpt-j-6B) with limited memory. A detailed explanation of how it works can be found in [this model card](https://huggingface.co/hivemind/gpt-j-6B-8bit). It is heavily based on [this Colab](https://colab.research.google.com/drive/1ft6wQU0BhqG5PRlwgaZJv2VukKKjU4Es#scrollTo=vfdLQHOuEU7h). Huge thanks to Hivemind!

You can also finetune [GPT-Neo-2.7B](https://huggingface.co/gustavecortal/gpt-neo-2.7B-8bit), [French GPT-J (Cedille's Boris)](https://huggingface.co/gustavecortal/fr-boris-8bit) and [T0-3B](https://huggingface.co/gustavecortal/T0_3B-8bit) with limited memory.

Models trained with this method:

Sauge Divine: [@saugedivine](https://twitter.com/saugedivine). Trained on philosophical, trippy and mystical content.  
La Voix du Bot: [@lavoixdubot](https://twitter.com/lavoixdubot). Trained on French news.

LoRA: https://arxiv.org/abs/2106.09685  
8-bit Optimizers: https://arxiv.org/abs/2110.02861  

Twitter: [@gustavecortal](https://twitter.com/gustavecortal)
