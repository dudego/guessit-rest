REST WebService for GuessIt
===========================

GuessIt is a python library that extracts as much information as possible from a video filename.

This is the REST WebService for `GuessIt <https://github.com/guessit-io/guessit>`_.

Install from sources
--------------------

    $ git clone https://github.com/dudego/guessit-rest

    $ cd guessit-rest

Then configure a virtualenv with [pyenv](https://github.com/yyuu/pyenv) or any virtualenv manager you may like.

    $ pyenv virtualenv ...

Then install dependencies in the virtualenv.

    $ pip install -e .

Then run guessit rest API using main module.

    $ python -m guessitrest.app

Usage
-----

(GET) Connect your browser to `http://localhost:5000/?filename=test.avi <http://localhost:5000/?filename=test.avi>`_

        OR

(POST) Post a json to `http://localhost:5000 <http://localhost:5000>`_
{"one":"test.avi", "two":"file2.avi", "2424":"scorpion.222.avi"}

License
-------

GuessIt is licensed under the `LGPLv3 license <http://www.gnu.org/licenses/lgpl.html>`_.
