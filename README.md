The script:
Reads CIF files from an input folder or uses a precomputed similarity matrix.
Optionally strips terminal atoms (except O, N, S) from molecular structures.
Compares crystal packing using CCDC’s PackingSimilarity tool.
Builds a similarity matrix based on the number of matched molecules or RMSD (root-mean-square deviation).
Saves results: Matrix as a text file, heatmap as a PNG, and optionally detailed packing similarity outputs (text and overlays).
Plots a dendrogram for clustering (though the plot_dendrogram function is missing in the provided code).
