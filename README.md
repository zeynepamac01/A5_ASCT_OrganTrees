# Organ-specific tree visualizations

The organ-specific anatomical and cell-type tree visualizations were generated using:
- HRA_OrganTree_v1.ipynb: the original notebook used as the base generator.
- HRA_OrganTree_v1_highlighted_red_nodes.ipynb: the latest modified version used to generate the final visualizations and highlight the requested structures, FTUs, and cell types with red nodes.
The notebooks use the HRA v2.5 ASCT+B tree data:
- data/v2.5/asct-nodes.csv
- data/v2.5/asct-edges.csv
The visualizations show hierarchical relationships among body structures, anatomical structures, FTUs, and cell types. The final outputs were exported as SVG files for editing in Adobe Illustrator.

The latest generated files are located in:
ftu_horizontal_generator/highlighted_cell_labels_v4_red_nodes/
The original source notebook and its outputs were preserved and were not overwritten.
Brain data limitation
Some requested brain structures and cell types were not available as connected nodes in the current HRA v2.5 source data. Therefore, unsupported relationships were not added to the final tree visualization:
- Pyramidal glutamatergic neurons
- Magnocellular neurosecretory cells
- Pituitary gland and somatotrophs
- Pinealocytes
These terms are biologically valid but were not represented in the source data used to generate the visualization.
