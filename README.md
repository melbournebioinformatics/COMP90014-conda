# COMP90014-conda
Environment settings for workshops in Algorithms in Bioinformatics

## Binder
Open a [Binder](https://mybinder.org/v2/gh/melbournebioinformatics/COMP90014-conda/HEAD) session using the environment settings from this repo.

## Working with Gitpod

If working on this repo from a Gitpod workspace dependancies from the Dockerfile should be automatically installed 
and enabled in the base conda environment along with any packages listed in `requirements.txt`.

You will need to `conda install` any non-pip packages.

### Opening a Jupyter session from Gitpod

```bash
# Increase gitpod timeout setting
gp timeout set 6h

# Launch jupyter-lab
jupyter lab --NotebookApp.allow_origin='*' --NotebookApp.allow_remote_access=True

# or Launch jupyter-notebook
jupyter notebook --NotebookApp.allow_origin='*' --NotebookApp.allow_remote_access=True

```
The notebook will be available on port 8888 by default. You can open this port using the link in the `Ports` tab above the terminal.

If prompted for a password or token find the line that looks like this in your terminal and copy the token:
 `http://localhost:8888/tree?token=51b713c73bad3c2cf19b43b91007ec7dc651b47cbcedd865`


**Note:** See other [gitpod settings](https://www.gitpod.io/docs/references/gitpod-cli#set) here.
