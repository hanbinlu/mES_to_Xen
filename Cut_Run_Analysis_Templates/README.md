## Dependencies

Using conda create new environment and install dependencies.

```
conda create -n cut_run python=3.8 bowtie2 samtools macs2 trimmomatic
```

- Trimmomatic: trim reads to help mapping short fragments

To call motif, install meme and bedops. To run in jupyter, add the env's python to jupyter kernels

```
conda activate cut_run
python -m ipykernel install --user --name cut_run --display-name "cr"
```
