======================
Cookiecutter PyPackage
======================

.. image:: https://readthedocs.org/projects/cookiecutter-pypackage/badge/?version=latest
    :target: https://cookiecutter-pypackage.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status

Features
--------
* Installing: Install package-dependencies on venv using poetry.
* UnitTesting: Perform unit tests.
* pre-commit: Perform code checks before committing to github.
* Sphinx docs: Generate and publish documentation using readthedocs and sphinx.
* (bumpy-my-version)<https://github.com/callowayproject/bump-my-version>: automatically bump the version number up when committing


Using the project-template online
---------------------------------
1. Install the latest Cookiecutter if you haven't installed it yet (this requires
Cookiecutter 1.4.0 or higher)::

    pip install -U cookiecutter


2. Go into the directory where you want to put your package::

    cd path/to/your/directory

2. Generate a Python package project and following the instructions in the command line::

    cookiecutter https://github.com/VakantieModus/template-project.git

3. Go into the generated project::

    cd path/to/your/directory/project-name

4. Generate the venv using the following command::

  project-name/scripts/install_venv.bat
    

Using the project-template offline
---------------------------------
1. Clone the repository by downloading the zip-file and extracting the contents or running the following command::

    git clone https://github.com/VakantieModus/template-project

2. Install the latest Cookiecutter if you haven't installed it yet (this requires
Cookiecutter 1.4.0 or higher)::

    pip install -U cookiecutter

3. Go into the directory where you want to put your package::

    cd path/to/your/directory

4. Generate a Python package project and following the instructions in the command line::

    cookiecutter https://github.com/VakantieModus/template-project.git

5. Go into the generated project::

    cd path/to/your/directory/project-name

6. Generate the venv using the following command::

  project-name/scripts/install_venv.bat


Fork This / Create Your Own
~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you have differences in your preferred setup, I encourage you to fork this
to create your own version. Or create your own; it doesn't strictly have to
be a fork.

* Once you have your own version working, add it to the Similar Cookiecutter
  Templates list above with a brief description.

* Settings are easily adjusted using the cookiecutter.json file

* It's up to you whether or not to rename your fork/own version. Do whatever
  you think sounds good.

For more details, see the `cookiecutter-pypackage tutorial`_.
.. _`cookiecutter-pypackage tutorial`: https://cookiecutter-pypackage.readthedocs.io/en/latest/tutorial.html
