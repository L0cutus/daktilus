# Daktilus – modello

Questo repository serve solo a distribuire il modello linguistico usato dalla tastiera Android **Daktilus**
(suggerimenti, scelta delle parole dello swipe e correzione degli accenti, tutto sul telefono, senza rete).

La tastiera lo scarica da sola dalle impostazioni; non serve scaricarlo a mano.

| File | Dimensione | SHA-256 |
|---|---|---|
| `qwen3.5-0.8B-Base-Q4_0.gguf` (nella Release `v1`) | 513 MB | `b1d87abcb9e71fd2d81e905dc478d4606bd65aa05d5170a6405f02fc21b0a409` |

## Origine e licenza

- Modello originale: **Qwen3.5-0.8B-Base** di Qwen (Alibaba Cloud), licenza **Apache 2.0** (testo completo in `LICENSE`).
- Modifica: solo conversione in formato GGUF e quantizzazione **Q4_0** con [llama.cpp](https://github.com/ggml-org/llama.cpp)
  (build b11946). Nessun addestramento aggiuntivo, nessun dato personale.
- Il file è ridistribuito secondo i termini della licenza Apache 2.0; tutti i diritti sul modello originale restano dei rispettivi autori.
