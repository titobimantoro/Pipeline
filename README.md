# RAG Literature Gap Matrix dengan Gemini API

Notebook Google Colab untuk ekstraksi PDF, chunking, embedding multilingual, retrieval dengan FAISS, generasi delapan kolom Literature Gap Matrix dengan Gemini, sintesis research gap, dan ekspor Excel.

## Cara menjalankan
1. Buka https://colab.research.google.com/
2. Upload file `RAG_Literature_Gap_Matrix_Gemini.ipynb`.
3. Jalankan sel dari atas ke bawah.
4. Masukkan Gemini API key saat diminta; jangan simpan key di notebook.
5. Upload PDF artikel ilmiah.
6. Periksa hasil satu artikel sebelum menjalankan semua artikel.
7. Unduh file Excel hasil pipeline.

## Dependensi
pymupdf, sentence-transformers, faiss-cpu, pandas, openpyxl, google-genai.

## Output Excel
- `Literature Gap Matrix`: tepat 8 kolom sesuai instruksi.
- `Analisis Research Gap`: sintesis lintas artikel.
- `Statistik PDF`: status ekstraksi teks.

## Peringatan
Hasil AI wajib diverifikasi pada PDF asli. PDF scan mungkin memerlukan OCR. Biaya/kuota Gemini bergantung pada model dan akun. Jangan unggah API key atau dokumen sensitif ke GitHub.
