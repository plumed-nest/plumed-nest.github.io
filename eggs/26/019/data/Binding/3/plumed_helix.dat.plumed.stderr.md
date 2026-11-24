**Project ID:** [plumID:26.019]({{ '/' | absolute_url }}eggs/26/019/)  
Stderr for source:  Binding/3/plumed_helix.dat   
Download: [zipped raw stdout](plumed_helix.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_helix.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
ERROR : in input for command line tool driver :
(tools/OFile.cpp:445) void PLMD::OFile::checkNotOpenElsewhere() const
file Kernels1.data is already open for writing by action opes1 (OPES_METAD_EXPLORE) and cannot be opened again by action opes2 (OPES_METAD_EXPLORE). Writing the same file twice would result in a corrupted file. Please use a different file name
</pre>
{% endraw %}
