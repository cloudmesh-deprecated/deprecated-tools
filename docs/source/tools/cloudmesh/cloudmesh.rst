Cloudmesh
=========


Preapare the system (Ubuntu)
-------------------
(Ubuntu Xenial) desktop

Prepare using the terminal::

    which pip
    pip --version

    MUST BE 8.1.2 OR HIGHER
    install pip

    pip install -U pip
    pip instal virtualenv


    sudo apt-get install build-essential autoconf libtool pkg-config
    # sudo apt-get install python-opengl python-imaging python-pyrex
    sudo apt-get install libgle3 python-dev



    #? sudo easy_install greenlet
    sudo apt-get install libffi-dev
    sudo apt-get install libssl-dev

    sudo apt-get install sqlite3 libsqlite3-dev

Setting up a virtual environment or virtualenv for installing and running the cloudmesh client::

    virtualenv ~/ENV
    source ~/ENV/bin/activate

Production version
-------------------

Set up cloudmesh::

    pip install cloudmesh_client

    emacs ~/.cloudmesh/cloudmesh.yaml (change active from kilo to chameleon)

    cm cloud activate chameleon

    cm key add --ssh
    cm key upload
    cm secgroup upload
    cm info

Boot a virtual machine::

    cm vm boot

Development version
------------------------

Cloudmesh installation process for virtualenv::

    mkdir ~/github
    cd ~/github
    git clone https://github.com/cloudmesh/client.git
    cd client
    git checkout dev
    pip install -r requirements.txt
    pip install .


    cm help
    cm register chameleon
    ... to be continued ...
