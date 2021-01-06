# Environemnt Setup
Author:  David Yerrington

> Please take the time to set up your Python environment ahead of time.  Even seasoned Python experts may run into a library problem and need more time to work it out.  Our timeline for this session won't allow me to help everyone personally, so please take advantage of this guide before attending our session together.

It's ideal to set up a Python environment for each project you work on. Having a separate environment for each independent Python project or domain allows:

- Fewer library inconsistencies 
- Minimal library complexity
- Maximum project portability

For example, you might have a Python environment specifically for Jupyter and a specific analysis or one for a dashboard application. I recommend that you set up an environment, especially for this session, mainly for these reasons:

- We all run the same libraries and versions
- Any problems we encounter are more likely to be shared amongst everyone
- It's easier to support each other in chat when we have the same problems

So with this in mind, you can choose to install the following libraries in your environment, but it's strongly recommended that you setup a new environment!

- Pandas v1.1.x
- Jupyter Lab v2.3.x

> The "x" is any version in this version sequence or greater.

<br><br>

![](https://upload.wikimedia.org/wikipedia/en/c/cd/Anaconda_Logo.png)
## 1. Anaconda Environments
It's recommended to use Anaconda to install the Python environment because it's easy to install a specific Python version along with the required packages in our [requirements.txt](./requirements.txt) file.  You can also use [virtualenv](https://docs.python-guide.org/dev/virtualenvs/), but the setup is a bit trickier to use a specific version of Python with.
> If you're already hip to setting up and managing your Python environments, you can move on to the next step in setup and configuration.


## 1. Anaconda Environments

I recommend using Anaconda to install the Python environment because it's easy to install a specific Python version along with the required packages in our [requirements.txt](./requirements.txt) file.  You can also use [virtualenv](https://docs.python-guide.org/dev/virtualenvs/), but the setup is a bit trickier to use a specific version of Python with.
> If you're already hip to setting up and managing your Python environments, you can move on to the next step in setup and configuration.


### 1.1 Anaconda

![](https://snipboard.io/7hOoz3.jpg)

Using [Anaconda Individual](https://www.anaconda.com/products/individual) for your chosen platform, create an environemnt called `ai-pandas` with the appropriate packages using Python `3.8.5` with the following command from this cloned repo:

```bash
conda create --name ai-pandas pandas jupyterlab python=3.8.5
```

![](https://snipboard.io/Ke9Z8d.jpg)

> After you create the environment `ai-pandas`, it will give you instructions on how to activate it.

![](https://snipboard.io/VYEPo3.jpg)

Activate the environment prior to using Jupyter lab:

```bash
conda activate ai-pandas
```

## 2. Jupyter Lab

With your `ai-pandas` environment activated, start a Jupyter Lab session in the repo directory for this project.  If you already have a session running, simply navigate to the [notebooks](/notebooks) directory and open the first notebook in sequence.

From the command line:

```bash
jupyter lab
```

![](https://snipboard.io/4XlmLU.jpg)


## 3. Summary

That's it!  Install Anaconda Individual, create an environement with the `pandas` and `jupyterlab` Python packages then start Jupyter:  `jupyter lab`.  From here, we will start with a bit of review before we dive into the main parts of our exploration into advanced Pandas.
