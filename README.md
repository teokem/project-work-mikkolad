# Project work: readgad

Here are some instructions on what you need to do to run this notebook. 

## Downloading and setting up

Start by downloading the project and installing the environment
```
$ git clone https://github.com/teokem/project-work-mikkolad.git
$ cd project-work-mikkolad
$ conda env create -f readgadenv.yml
$ source activate readgadenv
(readgadenv) $ 
```
This will place you in the environment. It can be deactivated with `source deactivate readgadenv`.

In the environment you will need to install [`pynbody`](https://github.com/pynbody/pynbody). The recommended way of installing is by either doing the following:

```
$ git clone https://github.com/pynbody/pynbody
$ cd pynbody
$ python setup.py install
```

or

```
pip install git+git://github.com/pynbody/pynbody.git
```

With this done you should be able to run the notebook. Start it by writing `jupyter notebook` in the terminal. 
