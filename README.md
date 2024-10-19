# finetuned_llm_ollama

Project ini dibuat dengan Python dan [Ollama](https://github.com/ollama/ollama). Silahkan lakukan installasi sesuai sistem operasi yang digunakan. Jika memiliki mesin dengan spesifikasi terbatas, bisa memanfaatkan [Google Colab - free tier](https://colab.research.google.com/).

Berikut kebutuhan terkait yg digunakan dalam project ini:

- dataset: [syntethic text to sql](https://huggingface.co/datasets/gretelai/synthetic_text_to_sql)
- unsloth: [pretrained model](https://github.com/unslothai/unsloth)

Ouput `.gguf` file juga sudah tersedia dan bisa langsung digunakan, silahkan download melalui link [Google drive](https://youtube.com/live/Y4a17qNeekE) yg sudah disediakan dalam deskripsi video.

Setelah download semua file yang tersedia, jalankan service Ollama lalu ketik perintah berikut untuk membuat dan menjalankan model:

```
ollama create nama_model_disini -f ./Modefile
ollama run nama_model_disini
```
