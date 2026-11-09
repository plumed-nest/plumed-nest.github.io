**Project ID:** [plumID:19.038]({{ '/' | absolute_url }}eggs/19/038/)  
Stderr for source:  achour2019_mb2m/mb2m/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
ERROR : in input for command line tool driver :
(isdb/CS2Backbone.cpp:646) PLMD::isdb::CS2Backbone::CS2Backbone(const PLMD::ActionOptions&)
ATOMS and the TEMPLATE data_ca//template.pdb must contain the same atoms (ATOMS has 1618 atoms, the TEMPLATE 1617): write a TEMPLATE with only the atoms in ATOMS
ERROR : in input for command line tool driver :
(isdb/CS2Backbone.cpp:646) PLMD::isdb::CS2Backbone::CS2Backbone(const PLMD::ActionOptions&)
ATOMS and the TEMPLATE data_ca//template.pdb must contain the same atoms (ATOMS has 1618 atoms, the TEMPLATE 1617): write a TEMPLATE with only the atoms in ATOMS
--------------------------------------------------------------------------
Primary job  terminated normally, but 1 process returned
a non-zero exit code. Per user-direction, the job has been aborted.
--------------------------------------------------------------------------
--------------------------------------------------------------------------
mpirun detected that one or more processes exited with non-zero status, thus causing
the job to be terminated. The first process to do so was:

Process name: [[18547,1],0]
Exit code:    1
--------------------------------------------------------------------------
</pre>
{% endraw %}
