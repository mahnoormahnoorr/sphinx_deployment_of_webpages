                            

# Quantization


This repository explores **quantization methods for Large Language Models (LLMs)**.
Quantization is a key technique for reducing model size and inference cost, enabling LLMs $

We provide examples and experiments for:

- **[BitsAndBytes (bnb)](https://github.com/mahnoormahnoorr/Quantization/tree/main/bitsand$
- **[AWQ (Activation-aware Weight Quantization)](https://github.com/mahnoormahnoorr/Quanti$
- **[GPTQ (Gradient Post-training Quantization)](https://github.com/mahnoormahnoorr/Quanti$

---

## 📖 What to Expect in This Repo

1. **Implementation Examples**
   - Scripts for loading, quantizing, and saving models.
   - Examples include small models (for example; `facebook/opt-125m`) so you can try thing$

2. **Benchmarks**
   - Inference time comparisons before and after quantization.
   - Model size reduction (disk footprint in MB).


3. **Guides & Utilities**
   - Helper functions for measuring model size, timing inference, and testing the quantize$
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

![](img/eurocc.svg)
![](img/coderefinery.svg)

This project has received funding from the European High-Performance Computing
Joint Undertaking (JU) under grant agreement No 101101903.

The lesson file structure and browsing layout is inspired by and derived from
[work](https://github.com/coderefinery/sphinx-lesson) by [CodeRefinery](https://coderefine$
[MIT license](https://opensource.org/licenses/mit-license.html). We have copied and adapted
most of their license text.

### Instructional Material

This instructional material is made available under the
[Creative Commons Attribution license (CC-BY-4.0)](https://creativecommons.org/licenses/by$
The following is a human-readable summary of (and not a substitute for) the
[full legal text of the CC-BY-4.0 license](https://creativecommons.org/licenses/by/4.0/leg$
You are free to:

- **share** - copy and redistribute the material in any medium or format
- **adapt** - remix, transform, and build upon the material for any purpose,
  even commercially.

The licensor cannot revoke these freedoms as long as you follow these license terms:

- **Attribution** - You must give appropriate credit, provide a
  [link to the license](https://creativecommons.org/licenses/by/4.0/), and indicate if cha$
  made. You may do so in any reasonable manner, but not in any way that suggests
  the licensor endorses you or your use.
- **No additional restrictions** - You may not apply legal terms or
  technological measures that legally restrict others from doing anything the
  license permits.


^G Get Help    ^O WriteOut    ^R Read File   ^Y Prev Pg     ^K Cut Text    ^C Cur Pos     
^X Exit        ^J Justify     ^W Where is    ^V Next Pg     ^U UnCut Text  ^T To Spell    
