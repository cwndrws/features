## Using Conda

This Feature includes [the `conda` package manager](https://docs.conda.io/projects/conda/en/latest/index.html) which is a part of the [Anaconda Distribution](https://repo.anaconda.com). Additional packages installed using Conda will be downloaded from Anaconda or another repository if you configure one. To reconfigure Conda in this container to access an alternative repository, please see information on [configuring Conda channels here](https://docs.conda.io/projects/conda/en/latest/user-guide/concepts/channels.html ).

Access to the Anaconda repository is covered by the [Anaconda Terms of Service](https://legal.anaconda.com/policies/en/?name=terms-of-service), which may require some organizations to obtain a commercial license from Anaconda. **However**, when used with GitHub Codespaces or GitHub Actions, **all users are permitted** to use the Anaconda Repository through the service, including organizations normally required by Anaconda to obtain a paid license for commercial activities. Note that third-party packages may be licensed by their publishers in ways that impact your intellectual property, and are used at your own risk.

## Installing a different version of Python

As covered in the [user FAQ](https://docs.anaconda.com/anaconda/user-guide/faq) for Anaconda, you can install different versions of Python than the one in this image by running the following from a terminal:

```bash
conda install python=3.7
```
