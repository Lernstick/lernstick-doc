# Lernstick Documentation

## Edit the documentation

To contribute tothe documentation, you need to clone this repository (or a fork thereof)

    git clone https://github.com/Lernstick/lernstick-doc.git

and change to the directory

    cd lernstick-doc

To build html files locally, install the required python modules

    pip install -r requirements.txt

Now you are ready to build the documentation via

    sphinx-build -M html . build

All the html files are now in the `build/html/` directory.

