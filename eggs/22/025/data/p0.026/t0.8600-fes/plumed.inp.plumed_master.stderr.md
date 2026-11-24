**Project ID:** [plumID:22.025]({{ '/' | absolute_url }}eggs/22/025/)  
Stderr for source:  p0.026/t0.8600-fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
../../code/ReweightGeomFES.WL6K8u.cpp: In member function ‘virtual double PLMD::bias::ReweightGeomFES::getLogWeight()’:
../../code/ReweightGeomFES.WL6K8u.cpp:137:14: warning: ‘val’ may be used uninitialized [-Wmaybe-uninitialized]
137 |   return val/2.0;
|              ^~~
../../code/ReweightGeomFES.WL6K8u.cpp:128:10: note: ‘val’ was declared here
128 |   double val;
|          ^~~
ERROR : in input for command line tool driver :
(tools/Keywords.cpp:383) void PLMD::Keywords::use(std::string_view)
+++ assertion failed: reserved(k)
the ARG keyword is not reserved
</pre>
{% endraw %}
