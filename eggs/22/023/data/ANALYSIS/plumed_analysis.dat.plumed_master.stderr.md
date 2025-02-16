**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  ANALYSIS/plumed_analysis.dat   
Download: [zipped raw stdout](plumed_analysis.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_analysis.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file structure.pdb
[fv-az1665-105:62219] *** Process received signal ***
[fv-az1665-105:62219] Signal: Aborted (6)
[fv-az1665-105:62219] Signal code:  (-6)
[fv-az1665-105:62219] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdc3b645330]
[fv-az1665-105:62219] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdc3b69eb2c]
[fv-az1665-105:62219] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdc3b64527e]
[fv-az1665-105:62219] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdc3b6288ff]
[fv-az1665-105:62219] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdc3baa5ff5]
[fv-az1665-105:62219] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdc3babb0da]
[fv-az1665-105:62219] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdc3baa5a55]
[fv-az1665-105:62219] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdc3baa5a6f]
[fv-az1665-105:62219] [ 8] plumed_master(+0x146dd)[0x556a222d36dd]
[fv-az1665-105:62219] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdc3b62a1ca]
[fv-az1665-105:62219] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdc3b62a28b]
[fv-az1665-105:62219] [11] plumed_master(+0x15365)[0x556a222d4365]
[fv-az1665-105:62219] *** End of error message ***
</pre>
{% endraw %}
