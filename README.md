LoanDynamics-SWIG: language bindings for Andrew-Davidson LoanDynamics Models
============================================================================

---

LoanDynamics-SWIG provides the means to use LoanDynamics from a number of
languages; currently their list includes Python, C#, and Java.

LoanDynamics Model is required in order to compile the module.


Download and usage
------------------

On Linux/Unix, you can run:

    ./configure
    make
    make check
    sudo make install

to build, test and install al modules. If you're only interested in a
specific language, you can tell make to only work in its subdirectory,
as in:

    make -C Python

Alternatively, you can cd to a specific subdirectory and follow the
instructions in its README file. This is also the procedure for
Windows users.


Questions and feedback
----------------------

Bugs can be reported as a GitHub issue at
<https://github.com/quantum-ml-geek/loan-dynamics/issues>; if you have a
patch available, you can open a pull request instead (see
"Contributing" below).


Contributing
------------

The easiest way to contribute is through pull requests on GitHub.  Get
a GitHub account if you don't have it already and clone the repository
at <https://github.com/quantum-ml-geek/loan-dynamics> with the "Fork" button
in the top right corner of the page. Check out your clone to your
machine, code away, push your changes to your clone and submit a pull
request; instructions are available at
<https://help.github.com/articles/fork-a-repo>.  (In case you need
them, more detailed instructions for creating pull requests are at
<https://help.github.com/articles/using-pull-requests>, and a basic
guide to GitHub is at
<https://guides.github.com/activities/hello-world/>.

It's likely that we won't merge your code right away, and we'll ask
for some changes instead. Don't be discouraged! 

We're looking forward to your contributions.
