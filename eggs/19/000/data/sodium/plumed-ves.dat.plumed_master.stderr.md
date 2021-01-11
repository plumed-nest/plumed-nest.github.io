**Project ID:** [plumID:19.000]({{ '/' | absolute_url }}eggs/19/000/)  
Stderr for source:  sodium/plumed-ves.dat   
(download [zipped raw stdout](plumed-ves.dat.plumed_master.stdout.txt.zip))  
{% raw %}
<pre>
DebyeStructureFactor.cpp: In member function ‘virtual void PLMD::colvar::DebyeStructureFactor::calculate()’:
DebyeStructureFactor.cpp:489:43: warning: ‘prev_sin’ may be used uninitialized in this function [-Wmaybe-uninitialized]
           cosQR=base_cos*prev_cos-base_sin*prev_sin;
                                           ^
DebyeStructureFactor.cpp:489:25: warning: ‘prev_cos’ may be used uninitialized in this function [-Wmaybe-uninitialized]
           cosQR=base_cos*prev_cos-base_sin*prev_sin;
                         ^
DebyeStructureFactor.cpp:489:43: warning: ‘base_sin’ may be used uninitialized in this function [-Wmaybe-uninitialized]
           cosQR=base_cos*prev_cos-base_sin*prev_sin;
                                           ^
DebyeStructureFactor.cpp:489:25: warning: ‘base_cos’ may be used uninitialized in this function [-Wmaybe-uninitialized]
           cosQR=base_cos*prev_cos-base_sin*prev_sin;
                         ^
</pre>
{% endraw %}
