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

curl https://avocado-project.org/data/repos/avocado-el.repo -o /etc/yum.repos.d/avocado.repo
yum install python-avocado

sudo dnf install -y python2 git gcc python-devel python-pip libvirt-devel libffi-devel openssl-devel libyaml-devel redhat-rpm-config xz-devel

git clone git://github.com/avocado-framework/avocado.git
cd avocado
sudo make requirements
sudo python setup.py install

cd optional_plugins/html
sudo python setup.py install



python -m virtualenv /path/to/new/virtual_environment
. /path/to/new/virtual_environment/bin/activate
pip install avocado-framework

$ avocado run /bin/true
JOB ID    : 0a7ac9321c1115a79e2e502bea30222f2f44cab0
JOB LOG   : $HOME/avocado/job-results/job-2014-08-12T15.39-381b849a/job.log
 (1/1) /bin/true: PASS (0.01 s)
RESULTS    : PASS 1 | ERROR 0 | FAIL 0 | SKIP 0 | WARN 0 | INTERRUPT 0
JOB TIME   : 0.11 s
JOB HTML  : $HOME/avocado/job-results/job-2014-08-12T15.39-381b849a/html/results.html

python-avocado-examples
python2-avocado-plugins-output-html
python2-avocado-plugins-resultsdb
python2-avocado-plugins-runner-remote
python2-avocado-plugins-runner-vm
python2-avocado-plugins-runner-docker
python-avocado-plugins-varianter-yaml-to-mux


--dry-run



