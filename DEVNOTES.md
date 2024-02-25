### Exporting notebooks to static html files:
with hiding code cells (input) tagged with 'hide_cell' in jupyter AND image embedding from dynamic code outputs as static images:
```
jupyter nbconvert --to html --TagRemovePreprocessor.remove_input_tags="{'hide_cell'}" --embed-images clean_notebooks/predicting_walmart_sales.ipynb
```