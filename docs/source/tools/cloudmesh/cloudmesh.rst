Cloudmesh
=========
something to do with cloudmesh::

    which pip
    pip --version

    sudo apt-get install build-essential autoconf libtool pkg-config python-opengl python-imaging python-pyrex python-pyside.qtopengl idle-python2.7 qt4-dev-tools qt4-designer libqtgui4 libqtcore4 libqt4-xml libqt4-test libqt4-script libqt4-network libqt4-dbus python-qt4 python-qt4-gl libgle3 python-dev

    sudo easy_install greenlet
    sudo easy_install gevent
    sudo apt-get install libffi-dev
    sudo apt-get install libssl-dev

    emacs ~/.cloudmesh/cloudmesh.yaml (change active from kilo to chameleon)

    cm info
    cm secgroup upload
    cm cloud activate chameleon
    ls
    cm vm boot

Cloudmesh installation process::

    ...

Setting up a virtual environment or virtualenv for installing and running the cloudmesh client.
Within the terminal enter the following:::

    pwd (to check if in the home directory
    cd .. (if not in the home directory apply until you are)
    which virtualenv
    virtualenv ENV
    ls ENV
    ls ENV/bin
    source ENV/bin/activate

Cloudmesh installation process for virtualenv.
Within the terminal enter the following:::

    which pip
    pip --version
    cd github
    ls
    git clone https://github.com/cloudmesh/client.git
    ls
    cd client
    git checkout dev
    ls
    python setup.py install
    pip install -r requirements.txt
    cm help
    cm register chameleon
    ... to be continued ...

words go here