**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../structure.pdb
[fv-az1390-170:09397] *** Process received signal ***
[fv-az1390-170:09397] Signal: Aborted (6)
[fv-az1390-170:09397] Signal code:  (-6)
[fv-az1390-170:09397] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff119e45330]
[fv-az1390-170:09397] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff119e9eb2c]
[fv-az1390-170:09397] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff119e4527e]
[fv-az1390-170:09397] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff119e288ff]
[fv-az1390-170:09397] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff11a2a5ff5]
[fv-az1390-170:09397] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff11a2bb0da]
[fv-az1390-170:09397] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff11a2a5a55]
[fv-az1390-170:09397] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff11a2a5a6f]
[fv-az1390-170:09397] [ 8] plumed_master(+0x146dd)[0x55d1cc8c16dd]
[fv-az1390-170:09397] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff119e2a1ca]
[fv-az1390-170:09397] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff119e2a28b]
[fv-az1390-170:09397] [11] plumed_master(+0x15365)[0x55d1cc8c2365]
[fv-az1390-170:09397] *** End of error message ***
</pre>
{% endraw %}
