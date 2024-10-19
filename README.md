# finetuned_llm_ollama
<a href="https://colab.research.google.com/github/devactivity/finetuned_llm_ollama/blob/main/DA_LLM.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>

Project ini dibuat dengan Python dan [Ollama](https://github.com/ollama/ollama). Silahkan lakukan installasi sesuai sistem operasi yang digunakan. Jika memiliki mesin dengan spesifikasi terbatas, bisa memanfaatkan [Google Colab - free tier](https://colab.research.google.com/).

Berikut kebutuhan terkait yang digunakan dalam project ini:

- dataset: [synthetic text to sql](https://huggingface.co/datasets/gretelai/synthetic_text_to_sql)
- unsloth: [pretrained model](https://github.com/unslothai/unsloth)

Output `.gguf` file juga sudah tersedia dan bisa langsung digunakan, silahkan download melalui link [Google Drive](https://youtube.com/live/Y4a17qNeekE) yang sudah disediakan dalam deskripsi video.

Setelah download semua file yang tersedia, jalankan service Ollama lalu ketik perintah berikut untuk membuat dan menjalankan model:

```
ollama create nama_model_disini -f ./Modefile
ollama run nama_model_disini
```

