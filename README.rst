# import-profiling
Some xonsh-related importe profiling.

May run with the following::

    $ env PYTHONPATH=. profimp --html "import with_pkg_resources" > with_pkg_resources.html
    $ env PYTHONPATH=. profimp --html "import without_pkg_resources" > without_pkg_resources.html

    $ profimp --html "import xonsh.pyghooks" > xpyg-withbg.html
    $ profimp --html "import xonsh.pyghooks" > xpyg-withoutbg.html

    $ profimp --html "import xonsh.ptk.shortcuts" > xptk-withbg.html
    $ profimp --html "import xonsh.ptk.shortcuts" > xptk-withoutbg.html