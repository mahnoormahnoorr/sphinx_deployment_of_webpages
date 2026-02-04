# Quantization


This repository explores **quantization methods for Large Language Models (LLMs)**.  
Quantization is a key technique for reducing model size and inference cost, enabling LLMs to run efficiently on consumer hardware or limited GPU memory.

We provide examples and experiments for:

- **[BitsAndBytes (bnb)](https://github.com/mahnoormahnoorr/Quantization/tree/main/bitsandbytes)** – nf4 quantization using the Hugging Face integration.
- **[AWQ (Activation-aware Weight Quantization)](https://github.com/mahnoormahnoorr/Quantization/tree/main/AWQ)** – a method that preserves accuracy by considering activation statistics.
- **[GPTQ (Gradient Post-training Quantization)](https://github.com/mahnoormahnoorr/Quantization/tree/main/GPTQ)** – post-training quantization optimized for autoregressive transformers.

---

## 📖 What to Expect in This Repo

1. **Implementation Examples**  
   - Scripts for loading, quantizing, and saving models.  
   - Examples include small models (for example; `facebook/opt-125m`) so you can try things quickly, and notes for scaling to larger models.

2. **Benchmarks**  
   - Inference time comparisons before and after quantization.  
   - Model size reduction (disk footprint in MB).  


3. **Guides & Utilities**  
   - Helper functions for measuring model size, timing inference, and testing the quantized model.  
   - Notes on how to run the examples on Puhti, Mahti and LUMI.


 

---

```{toctree}
---
maxdepth: 1
caption: Contents
---

GPTQ.md
AWQ.md
BitsAndBytes.md

```

## See also


[LUMI Documentation](https://docs.lumi-supercomputer.eu/)

## Credits

![](_static_/eurocc.svg)
![](_static_/coderefinery.svg)

This project has received funding from the European High-Performance Computing
Joint Undertaking (JU) under grant agreement No 101101903.

The lesson file structure and browsing layout is inspired by and derived from
[work](https://github.com/coderefinery/sphinx-lesson) by [CodeRefinery](https://coderefinery.org/) licensed under the
[MIT license](https://opensource.org/licenses/mit-license.html). We have copied and adapted
most of their license text.

### Instructional Material

This instructional material is made available under the
[Creative Commons Attribution license (CC-BY-4.0)](https://creativecommons.org/licenses/by/4.0/).
The following is a human-readable summary of (and not a substitute for) the
[full legal text of the CC-BY-4.0 license](https://creativecommons.org/licenses/by/4.0/legalcode).
You are free to:

- **share** - copy and redistribute the material in any medium or format
- **adapt** - remix, transform, and build upon the material for any purpose,
  even commercially.

The licensor cannot revoke these freedoms as long as you follow these license terms:

- **Attribution** - You must give appropriate credit, provide a
  [link to the license](https://creativecommons.org/licenses/by/4.0/), and indicate if changes were
  made. You may do so in any reasonable manner, but not in any way that suggests
  the licensor endorses you or your use.
- **No additional restrictions** - You may not apply legal terms or
  technological measures that legally restrict others from doing anything the
  license permits.

With the understanding that:

- You do not have to comply with the license for elements of the material in
  the public domain or where your use is permitted by an applicable exception
  or limitation.
- No warranties are given. The license may not give you all of the permissions
  necessary for your intended use. For example, other rights such as
  publicity, privacy, or moral rights may limit how you use the material.

### Software

Except where otherwise noted, the example programs and other software provided
with this repository are made available under the [OSI](https://opensource.org/)-approved
[MIT license](https://opensource.org/licenses/mit-license.html).

