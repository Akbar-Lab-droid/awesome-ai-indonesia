# Awesome AI Indonesia 🇮🇩

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/Akbar-Lab-droid/awesome-ai-indonesia?style=social)](https://github.com/Akbar-Lab-droid/awesome-ai-indonesia)

Daftar kurasi ekosistem kecerdasan buatan (AI) Indonesia: model bahasa, dataset, komunitas, kursus, tools, perusahaan, dan riset. Disusun manual, bukan hasil salin-tempel mentah — setiap tautan dicek dan berfungsi per **20 November 2026**.

## Daftar Isi

- [Model Bahasa Indonesia](#model-bahasa-indonesia)
- [Dataset Bahasa Indonesia](#dataset-bahasa-indonesia)
- [Komunitas & Event](#komunitas--event)
- [Belajar AI](#belajar-ai)
- [Tools & Framework](#tools--framework)
- [Perusahaan & Startup AI Indonesia](#perusahaan--startup-ai-indonesia)
- [Media & Berita](#media--berita)
- [Riset & Paper](#riset--paper)

## Model Bahasa Indonesia

Model yang dilatih khusus untuk Bahasa Indonesia dan bahasa daerah — bukan sekadar model multibahasa umum.

- [Sahabat-AI](https://sahabat-ai.com) — LLM open-source untuk Bahasa Indonesia dan bahasa daerah (Jawa, Sunda, Bali, Batak), digagas GoTo dan Indosat. Mulai dari model 8B/9B (2024), kini 70B (2025) dengan layanan chat multibahasa. Modelnya tersedia di [Hugging Face](https://huggingface.co/GoToCompany) dan [Ollama](https://ollama.com/csalab/sahabatai1).
- [Komodo-7B](https://huggingface.co/Yellow-AI-NLP/komodo-7b-base) — LLM 7 miliar parameter dari Yellow.ai untuk Bahasa Indonesia, Inggris, dan 11 bahasa daerah. Berbasis Llama-2 dengan kosakata yang diperluas untuk bahasa Indonesia. [Paper](https://arxiv.org/abs/2403.09362) · [Blog](https://tech.yellow.ai/p/komodo-7b-the-first-llm-for-regional?open=false).
- [Cendol](https://arxiv.org/abs/2404.06138) — Koleksi LLM instruction-tuned untuk bahasa-bahasa Indonesia (300M–13B parameter), riset ACL 2024. Dilaporkan ~20% lebih baik dari model multibahasa umum pada tugas NLU Bahasa Indonesia.
- [SEA-LION](https://huggingface.co/aisingapore) — Keluarga LLM Asia Tenggara dari AI Singapore yang mencakup Bahasa Indonesia, dirancang untuk kebutuhan kawasan.
- [IndoBERT / IndoNLU](https://github.com/indobenchmark/indonlu) — Benchmark dan model NLP Bahasa Indonesia (IndoBERT, IndoBART, IndoGPT). Titik awal standar untuk riset NLP Indonesia.

## Dataset Bahasa Indonesia

- [NusaX](https://github.com/IndoNLP/nusax) — Korpus paralel 12 bahasa: Indonesia, Inggris, dan 10 bahasa daerah (Aceh, Bali, Banjar, Bugis, Madura, Minangkabau, Jawa, Ngaju, Sunda, Batak Toba). Dataset sentimennya ada di [Hugging Face](https://huggingface.co/datasets/SEACrowd/nusax_senti).
- [NusaCrowd](https://indonlp.github.io/nusa-catalogue/) — Inisiatif open-source yang mengumpulkan 137 dataset NLP bahasa Indonesia dan bahasa daerah, lengkap dengan datasheet. [Paper (ACL 2023)](https://aclanthology.org/2023.findings-acl.868/).
- [SEACrowd](https://github.com/SEACrowd) — Hub data multibahasa Asia Tenggara di Hugging Face, termasuk banyak dataset Indonesia. Koleksi dataset IndoNLP: [huggingface.co/datasets/indonlp](https://huggingface.co/datasets/indonlp).
- [OSCAR Bahasa Indonesia](https://huggingface.co/datasets/oscar-corpus/OSCAR-2301) — Korpus web raksasa multibahasa (Common Crawl), termasuk porsi Bahasa Indonesia untuk pretraining.
- [Wikipedia Bahasa Indonesia](https://dumps.wikimedia.org/idwiki/) — Dump resmi Wikipedia bahasa Indonesia, bahan baku klasik untuk korpus dan pretraining.

## Komunitas & Event

- [AIPROXCROP](https://github.com/AIPROXCROP) — Komunitas belajar AI berbahasa Indonesia — seri video edukasi "Ayo Belajar Bersama AIPROXCROP", 90 detik per episode.
- [Google Developer Groups (GDG) Indonesia](https://developers.google.com/community/gdg) — Chapter GDG di berbagai kota Indonesia; banyak meetup dan codelab seputar ML/AI.
- [PyCon Indonesia](https://pycon.id) — Konferensi Python tahunan Indonesia; selalu ada trek data dan machine learning.
- [Kaggle](https://www.kaggle.com/competitions) — Kompetisi data science dan ML. Banyak kompetisi dan dataset Indonesia di sini; tempat terbaik untuk latihan dengan data nyata.
- [Hugging Face](https://huggingface.co) — Rumah bagi model, dataset, dan demo AI open-source, termasuk hampir semua model Indonesia di daftar ini.

## Belajar AI

Jalur belajar yang dipakai ribuan orang Indonesia, dari nol sampai siap kerja.

- [Bangkit Academy — Machine Learning](https://bangkit.academy/machine-learning) — Program Google, GoTo, dan Traveloka. Jalur ML-nya mengajarkan TensorFlow, data, dan deployment, plus proyek capstone. [Situs utama](https://bangkit.academy).
- [Dicoding — Learning Path Machine Learning](https://www.dicoding.com/learningpaths) — Jalur belajar ML berbahasa Indonesia: Python, data, ML, deep learning, sampai deployment. [Situs utama](https://www.dicoding.com).
- [DeepLearning.AI](https://www.deeplearning.ai) — Kursus Andrew Ng dan tim: Machine Learning Specialization, Deep Learning Specialization, dan kursus LLM singkat.
- [Coursera](https://www.coursera.org) — Kursus universitas dan industri (Stanford, Google, IBM) untuk ML, deep learning, dan NLP.

## Tools & Framework

Tools yang dipakai sehari-hari untuk membangun dan menjalankan AI. Pilih satu, kuasai, baru pindah.

- [PyTorch](https://pytorch.org) — Framework deep learning paling populer di riset. [GitHub](https://github.com/pytorch/pytorch).
- [TensorFlow](https://www.tensorflow.org) — Framework deep learning Google; dipakai luas di industri, termasuk di jalur Bangkit.
- [scikit-learn](https://scikit-learn.org) — Library machine learning klasik (klasifikasi, regresi, clustering). Titik awal terbaik sebelum deep learning.
- [Transformers (Hugging Face)](https://github.com/huggingface/transformers) — Library standar untuk memakai dan fine-tuning model seperti BERT, Llama, dan Sahabat-AI.
- [Whisper](https://github.com/openai/whisper) — Model speech-to-text open-source OpenAI; bekerja baik untuk Bahasa Indonesia.
- [MediaPipe](https://github.com/google/mediapipe) — Solusi ML on-device Google: deteksi wajah, pose, gestur, dan lainnya.
- [Ollama](https://www.ollama.com) — Menjalankan LLM (termasuk Sahabat-AI dan Komodo-7B) secara lokal di laptop sendiri.
- [nanoGPT](https://github.com/karpathy/nanoGPT) — Implementasi GPT paling sederhana dan paling banyak dipelajari; cara terbaik memahami cara kerja LLM dari dalam.
- [Google Colab](https://colab.research.google.com) — Notebook Python gratis dengan GPU; tempat latihan ML tanpa perlu beli GPU.
- [Google AI for Developers](https://ai.google.dev) — Dokumentasi dan API Gemini, termasuk panduan untuk developer Indonesia.
- [Anthropic](https://www.anthropic.com) — Pembuat Claude; dokumentasi dan panduan prompt engineering yang rapi.

## Perusahaan & Startup AI Indonesia

Perusahaan Indonesia yang membangun produk AI — tempat belajar, magang, atau bekerja.

- [Kata.ai](https://kata.ai) — Platform conversational AI Indonesia: chatbot dan asisten virtual berbahasa Indonesia untuk perusahaan.
- [Nodeflux](https://www.nodeflux.io) — Perusahaan computer vision Indonesia: pengenalan wajah, analitik video, dan smart city.
- [GoTo — Sahabat-AI](https://sahabat-ai.com) — Ekosistem LLM open-source Indonesia dari GoTo dan Indosat (lihat juga bagian [Model Bahasa Indonesia](#model-bahasa-indonesia)).

## Media & Berita

- [DailySocial](https://www.dailysocial.id) — Media teknologi Indonesia; liputan startup dan AI paling konsisten.
- [Tech in Asia Indonesia](https://id.techinasia.com) — Berita teknologi dan startup Asia Tenggara, edisi Indonesia.

## Riset & Paper

Paper kunci tentang AI berbahasa Indonesia. Kalau mau riset serius, mulai dari sini.

- [NusaCrowd: Open Source Initiative for Indonesian NLP Resources (ACL 2023)](https://aclanthology.org/2023.findings-acl.868/) — 137 dataset, fondasi ekosistem NLP Indonesia modern.
- [Komodo: A Linguistic Expedition into Indonesia's Regional Languages](https://arxiv.org/abs/2403.09362) — Komodo-7B, LLM pertama untuk bahasa daerah Indonesia.
- [Cendol: Open Instruction-tuned Generative LLMs for Indonesian Languages (ACL 2024)](https://arxiv.org/abs/2404.06138) — Koleksi LLM instruction-tuned Bahasa Indonesia 300M–13B.

---

Dikurasi oleh [Akbar](https://github.com/Akbar-Lab-droid). Dibuat untuk komunitas AI Indonesia. 🇮🇩
