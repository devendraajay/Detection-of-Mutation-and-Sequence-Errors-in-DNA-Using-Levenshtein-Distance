# Detection of Mutation and Sequence Errors in DNA Using Levenshtein Distance

## 📘 Overview
This project focuses on the **detection of mutations and sequence errors in DNA** using the **Levenshtein distance algorithm**, which measures the minimum number of edits (insertions, deletions, or substitutions) required to convert one DNA sequence into another.  
By integrating concepts from **automata theory** and **string similarity**, this approach efficiently identifies variations between reference and test DNA sequences, providing insight into possible genetic mutations or sequencing errors.

---

## 🧬 Motivation
DNA sequences are prone to mutations and errors during biological replication or data sequencing.  
Accurately identifying these differences is crucial in **bioinformatics**, **genetic analysis**, and **medical diagnostics**.  
This project offers a computational model that applies **Levenshtein distance** and **automata principles** to detect such variations systematically and accurately.

---

## ⚙️ Features
- Detects **insertions**, **deletions**, and **substitutions** in DNA sequences.  
- Calculates the **Levenshtein distance** between two sequences.  
- Uses **automata-based validation** for sequence comparison.  
- Provides the **position and type** of mutation detected.  
- Displays an overall **similarity percentage** between sequences.  

---

## 🧠 Methodology
1. **Input:**  
   - A *reference DNA sequence* and a *test DNA sequence* are provided as input.  
2. **Validation:**  
   - The sequences are checked to ensure they contain only valid nucleotide bases (A, T, G, C).  
3. **Computation:**  
   - The **Levenshtein distance algorithm** is applied to compute the minimum number of edits.  
   - Automata transitions model each possible edit operation for clear visualization of sequence changes.  
4. **Output:**  
   - Displays detected mutation type(s) and position(s).  
   - Shows total edit distance and sequence similarity percentage.  

---

## 🧩 Example
**Reference DNA:** `ATGCTAGC`  
**Test DNA:** `ATGCGAGC`

**Output:**
