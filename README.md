# Exercises on GAN

These notebook are based on this article: [Generative Adversarial Networks: Build Your FIrst Models - Real Python](https://realpython.com/generative-adversarial-networks/#the-architecture-of-generative-adversarial-networks).

In the article was suggested to use Pytorch 1.4.0, but I want to try with latest version of Pytorch (Pytorch 1.12.0) and latest CUDA drivers (CUDA 11.6).

# About the environment

The article suggested to configure environment with these commands:

> `conda create --name gan`
>
> `conda activate gan`

and to install these librraries:

> `conda install -c pytorch pytorch=1.4.0`
>
> `conda install matplotlib jupyter`
>
> `conda install -c pytorch torchvision=0.5.0`

and finally to register the new environment with Jupyter (to use Jupyter Notebboks with it) with this command:

> `python -m ipykernel install --user --name gan`

But I prefer to use actual latest version of Python and Pytorch and to installa additional libraries to experiment with other notebooks.
So I've created the environment with these commands:

> `conda create --name gan`
> 
> `conda activate gan`
>
> `conda install pip # To install packages not available with conda`
>
> `conda install matplotlib ipykernel`
>
> `conda install pytorch torchvision torchaudio cudatoolkit=11.6 -c pytorch -c conda-forge`
