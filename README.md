# MIND: Manifestos Indicating Notorious Deviations

## Overview

The MIND dataset is a comprehensive collection of mass shooter manifestos, designed to support researchers studying these unique texts. For each manifesto in the dataset, we provide the full text of the manifesto, metadata about the manifesto, and the text of news articles related to the manifesto.

## Dataset Structure

The dataset is organized in the following way:

### `data.csv`

This is a metadata file for each manifesto in the dataset. Each row represents one manifesto and the columns are defined as follows:

- `id`: A unique identifier for each manifesto. This ID is used to associate the metadata with the corresponding manifesto text and related news articles.
- `title`: The title of the manifesto, as originally given by its author. If there is no title given by the author, `title` will be `unnamed`.
- `author`: The name of the person who wrote the manifesto.
- `n_news`: The number of news articles in the dataset that are related to the manifesto.

### `manifestos/`

This directory contains the text of each manifesto. Each file is named with the `id` of the corresponding manifesto from `data.csv` and has a `.txt` extension. For example, the text of the manifesto with `id` 1 is in the file `manifestos/1.txt`.

### `news/`

This directory contains the text of news articles related to each manifesto. Each file is named with the `id` of the corresponding manifesto from `data.csv`, followed by an underscore and the index of the news article for that manifesto, and has a `.txt` extension. For example, the text of the first news article related to the manifesto with `id` 1 is in the file `news/1_1.txt`.

## Citation

If you use the MIND dataset in your research, please cite it as follows:

```
TODO
```

For any further queries or requests, please contact TODO.

No.10 too long
NO.21 is a book for purchase
No.28 image format, not in text format
