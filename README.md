# AVO
AVOcado
name is ``python-avocado``, and can be installed with::

    dnf install python-avocado

Other available packages (depending on the Avocado version) may include:
can install the RPM packages by running the following commands::

    dnf install python-avocado

sudo curl https://repos-avocadoproject.rhcloud.com/static/avocado-fedora.repo-o/etc/yum.repos.d/avocado.repo

sudo dnf repolist avocado avocado-lts
...
repo id      repo name                          status
avocado      Avocado                            50
avocado-lts  Avocado LTS (Long Term Stability)  disabled

dnf install python-avocado

python -m virtualenv /path/to/new/virtual_environment
. /path/to/new/virtual_environment/bin/activate
pip install avocado-framework

$ avocado run /bin/true
JOB ID    : 381b849a62784228d2fd208d929cc49f310412dc
JOB LOG   : $HOME/avocado/job-results/job-2014-08-12T15.39-381b849a/job.log
 (1/1) /bin/true: PASS (0.01 s)
RESULTS    : PASS 1 | ERROR 0 | FAIL 0 | SKIP 0 | WARN 0 | INTERRUPT 0
JOB TIME   : 0.11 s
JOB HTML  : $HOME/avocado/job-results/job-2014-08-12T15.39-381b849a/html/results.html
