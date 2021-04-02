# gingko

### Description

-It's kind of like scipy.sparse.csr_matrix... except it works with n-dimensional tensors

-It's kind of like torch.sparse.sparse_coo_tensor... except that it can be sliced

-It's kind of like tf.sparse.SparseTensor... except it's lighter and easier to use

Experiments in "example_wiki.ipynb"

### Data Generation

To crawl and collect wikipedia data starting from a seed topic:
```bash
python run_wikiscraper.py --start_topic Agnosticism --n_depth 2

```
