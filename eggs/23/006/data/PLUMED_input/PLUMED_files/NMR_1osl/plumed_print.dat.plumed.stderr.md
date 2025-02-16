**Project ID:** [plumID:23.006]({{ '/' | absolute_url }}eggs/23/006/)  
Stderr for source:  PLUMED_input/PLUMED_files/NMR_1osl/plumed_print.dat   
Download: [zipped raw stdout](plumed_print.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_print.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file 1osl_C52V_GMX_new_numbering.pdb
[fv-az1665-105:61582] *** Process received signal ***
[fv-az1665-105:61582] Signal: Aborted (6)
[fv-az1665-105:61582] Signal code:  (-6)
[fv-az1665-105:61582] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd7e3a45330]
[fv-az1665-105:61582] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd7e3a9eb2c]
[fv-az1665-105:61582] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd7e3a4527e]
[fv-az1665-105:61582] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd7e3a288ff]
[fv-az1665-105:61582] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd7e3ea5ff5]
[fv-az1665-105:61582] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd7e3ebb0da]
[fv-az1665-105:61582] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd7e3ea5a55]
[fv-az1665-105:61582] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd7e3ea5a6f]
[fv-az1665-105:61582] [ 8] plumed(+0x146dd)[0x55ca6f7a56dd]
[fv-az1665-105:61582] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd7e3a2a1ca]
[fv-az1665-105:61582] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd7e3a2a28b]
[fv-az1665-105:61582] [11] plumed(+0x15365)[0x55ca6f7a6365]
[fv-az1665-105:61582] *** End of error message ***
</pre>
{% endraw %}
