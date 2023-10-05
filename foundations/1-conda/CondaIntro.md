# Conda

# Introduction to Conda Environments

One of the essential tools we'll be using is **Conda**, a package manager and environment management system. In this README, we'll introduce you to the concept of virtual environments, how to install and update packages using Conda, conda-forge, and pip.

## What is a Virtual Environment?

A virtual environment is an isolated workspace on your computer where you can install and manage the software packages needed for your specific project without affecting the rest of your system. This is helpful because different projects might require different versions of the same package, and managing them in separate environments prevents any conflicts or issues.

## Why Use Conda Environments?

Conda is a powerful tool that simplifies package management and environment management for various programming languages, including Python, R, and others. It allows you to create, save, load, and switch between environments easily. Some benefits of using Conda environments include:

*   Isolated workspaces for your projects, preventing package conflicts
*   Easy installation and management of packages and their dependencies
*   Reproducible environment setup, making it easy to share your project with others

## Installing Packages with Conda

To install a package using Conda, you can use the following command:

```plain
conda install package-name  
```

For example, to install the popular data manipulation library Pandas, you would run:

```plain
conda install pandas  
```

Conda will automatically handle the installation of the package and any dependencies it requires.

## Using Conda-Forge

Conda-Forge is a community-driven repository of Conda packages. It contains many packages that may not be available in the default Conda repository. To install a package from Conda-Forge, you can use the following command:

```plain
conda install -c conda-forge package-name  
```

For example, to install the Plotly library for creating interactive plots, you would run:

```plain
conda install -c conda-forge plotly  
```

## Installing Packages with Pip

Pip is another package manager for Python. Although Conda is recommended for managing packages in your Conda environment, you might encounter situations where a package is only available through pip. To install a package using pip, you can use the following command:

```plain
pip install package-name  
```

For example, to install the Flask web framework, you would run:

```plain
pip install flask  
```

## Updating Packages

To update a package to its latest version, you can use the following command:

```plain
conda update package-name  
```

Or, if you installed a package using pip:

```plain
pip install --upgrade package-name  
```

Now that you have an understanding of Conda environments and how to manage packages, you're ready to dive into the world of Data & AI!

  

Before we can do that though, we will need to learn about activating and deactivating conda environments.

  

## Activating and Deactivating Environments

Working with multiple environments requires you to switch between them depending on the project you are working on. Activating an environment sets it as the active environment, making its packages and settings available for use. Deactivating an environment returns you to the base Conda environment or the previously active environment.

### Creating a New Environment

Before you can activate an environment, you need to create one.

To create a new environment, use the following command:

```plain
conda create --name myenv  
```

Replace `myenv` with the name you want to give your new environment.

### Activating an Environment

To activate an environment, use the following command:

```plain
conda activate myenv  
```

Replace `myenv` with the name of the environment you want to activate. Once the environment is active, your command prompt or terminal should display the environment name, like this:

```plain
(myenv) $  
```

  

### Deactivating an Environment

To deactivate the currently active environment and return to the base Conda environment or the previously active environment, use the following command:

```plain
conda deactivate  
```

After deactivating the environment, your command prompt should no longer display the environment name, but instead you will see 'base', which indicates you are in the default environment:

  

```plain
(base) $  
```

Remember to activate the appropriate environment before working on a project to ensure you have access to the correct packages and settings. When you're done working on a project, deactivate the environment to free up system resources and avoid potential conflicts.

  

Now - let's activate our ```storehouse``` environment! View the steps in [README.md](./README.md) to activate your environment.