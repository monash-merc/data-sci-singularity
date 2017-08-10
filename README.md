# data-sci-singularity
A singularity container def file for Python2/3 &amp; R and some deep learning frameworks

This container was built initially with an image size of 10gb, and then resized to 6gb.

Jupyter can be started by running

```
nvidia-modprobe -u
singularity run --nv data-sci.img
```

Replacing `data-sci.img` with the appropriate image path.
