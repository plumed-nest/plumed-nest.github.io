**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[fv-az1665-105:62203] *** Process received signal ***
[fv-az1665-105:62203] Signal: Aborted (6)
[fv-az1665-105:62203] Signal code:  (-6)
[fv-az1665-105:62203] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f45ee445330]
[fv-az1665-105:62203] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f45ee49eb2c]
[fv-az1665-105:62203] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f45ee44527e]
[fv-az1665-105:62203] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f45ee4288ff]
[fv-az1665-105:62203] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f45ee8a5ff5]
[fv-az1665-105:62203] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f45ee8bb0da]
[fv-az1665-105:62203] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f45ee8a5a55]
[fv-az1665-105:62203] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f45ee8a5a6f]
[fv-az1665-105:62203] [ 8] plumed(+0x146dd)[0x5648847436dd]
[fv-az1665-105:62203] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f45ee42a1ca]
[fv-az1665-105:62203] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f45ee42a28b]
[fv-az1665-105:62203] [11] plumed(+0x15365)[0x564884744365]
[fv-az1665-105:62203] *** End of error message ***
</pre>
{% endraw %}
