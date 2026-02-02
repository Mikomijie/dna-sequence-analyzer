# dna-sequence-analyzer
# 🧬 DNA Sequence Pattern Finder

> Advanced genomic sequence analysis tool built for the AI Vibe Coding Hackathon 2026


## 🎯 Problem Statement

Biology students and researchers spend 2-3 hours manually analyzing DNA sequences for homework and preliminary research. Professional tools like BLAST are overkill and require complex setup. We built an instant, browser-based solution.

## ✨ Features

- **GC Content Analysis** - Calculate guanine-cytosine percentage with visual progress bar
- **Nucleotide Composition** - Count and visualize A, T, C, G distribution  
- **ORF Detection** - Find Open Reading Frames (potential genes)
- **Motif Recognition** - Identify regulatory elements (TATA box, CAAT box, GC box)
- **Reverse Complement** - Generate complementary DNA strand
- **Sample Sequences** - Pre-loaded examples for testing
- **Export Results** - Copy analysis to clipboard

## 🚀 How to Use

1. Open the link `https://dnasequenceanalyzer.surgent.site/`
2. Open in any modern browser (Chrome, Firefox, Edge)
3. Paste a DNA sequence (ATCG format)
4. Click "Analyze Sequence"
5. View instant results!

**No installation. No dependencies. No backend. Just works.**

## 🧪 Example Sequences

### E.coli Gene Sample
```
ATGGCAAGCGTTAACGGCCAGGGCTTGCCGGCTGCGCAATTGAAAGTGAAGATGATGACCAGTAA
```
Expected: ~52% GC content, 1 ORF found

### TATA Box Detection
```
GCTAGCTAGCTATAAAAGGCCAATCTGCTAGCTAGCATGGCTAGCTAGCTAG
```
Expected: TATA box at position 12, CAAT box at position 24

## 🛠️ Tech Stack

- **Frontend:** Pure HTML5, CSS3, JavaScript (ES6+)
- **Styling:** Tailwind CSS (CDN)
- **Architecture:** Single-page application, no backend required
- **Analysis:** Custom JavaScript algorithms for DNA pattern matching

## 🏗️ Built With

- **Surgeon** - AI-powered vibe coding tool
- **AI Vibe Coding Hackathon** - February 2026

## 📊 Scientific Accuracy

All algorithms follow standard bioinformatics practices:
- GC content: (G+C)/total × 100
- ORF detection: ATG start codon → TAA/TAG/TGA stop codons
- Motif recognition: Exact pattern matching for known regulatory sequences
- Reverse complement: Standard Watson-Crick base pairing (A↔T, C↔G)

## 🎓 Educational Impact

**Target Users:**
- Biology students (homework assistance)
- Educators (teaching tool for molecular biology)
- Researchers (quick preliminary analysis)
- Bioinformatics beginners

**Time Saved:** 2-3 hours per sequence analysis → 5 seconds

## 🔮 Future Enhancements

- [ ] Protein translation (DNA → RNA → Amino Acids)
- [ ] Mutation comparison tool (diff two sequences)
- [ ] Integration with genome databases (NCBI, UniProt)
- [ ] Mobile app version
- [ ] .cv domain integration for profile publishing
- [ ] Batch processing (analyze multiple sequences)
- [ ] Export as PDF report

## 📄 License

MIT License - Open source and free to use

## 👥 Team

Built by Michael Omijie for AI Vibe Coding Hackathon 2026

## 🙏 Acknowledgments

- Hackathon organizers
- Surgeon/Surgent.dev for AI coding tools
- The bioinformatics community

---

**⭐ If this helped with your homework or research, give it a star!**
```
