# Awesome Open Problems for Machine Learning

#### How to contribute:
- **If you are an ML enthusiast and want a side project with real impact:** You are welcome to choose a problem from below. When you have result to share, please link back here and open an issue to get your result listed.
- **If you are from another field and want to see how ML can speed up science:** Please list open problems with datasets and benchmarks. You can do this via opening an issue or fork and pull request.

---

### Table of Content
- [Protein Folding](#protein-folding)
- [Short-term Earthquake Prediction](#short-earthquake)

<a name="protetin-folding"></a>
## #1. Protein Folding
**Predict the 3-dimensional structure of a protein from its 1-dimensional polypeptide chain.** The folding process happens automatically in nature giving a protein its 3-d structure, which decides the funtions of a protein. Proteins with similar 3-d structures would have similar functions, even if they have different polypeptide chains. This has important applications in designing and engineering proteins for novel functions.

### Datasets
- [ProteinNet](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-019-2932-0)
- [RCSB PDB: Protein Data Bank](https://www.rcsb.org/docs/programmatic-access/file-download-services) linked by [CASP](https://www.predictioncenter.org/index.cgi?page=links)

<a name="short-earthquake"></a>
## #2. Short-term Earthquake Prediction
**Predict the time, location, and magnitude of the next earthquakes.** There are several measurable properties of the earth such as *foreshocks, water level, leaked gases, magnetic field, ionosphere, Van Allen belts, etc.* that may be precursors before an earthquake happens. However, the relationships between these potential indicators and the earthquakes are very complex. The goal is to model these complex relationships to make accurate prediction in useful short term, from seconds to months in advance. 

Note: Most earthquake datasets only contain information about the shocks. [TODO]: Find data about precursors of earthquake.

### Datasets
- [USGS Earthquake Archive](https://earthquake.usgs.gov/earthquakes/search/)
- [STEAD: STanford EArthquake Dataset](https://github.com/smousavi05/STEAD)
