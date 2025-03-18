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
[fv-az1267-279:64562] *** Process received signal ***
[fv-az1267-279:64562] Signal: Aborted (6)
[fv-az1267-279:64562] Signal code:  (-6)
[fv-az1267-279:64562] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ffb60445330]
[fv-az1267-279:64562] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ffb6049eb2c]
[fv-az1267-279:64562] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ffb6044527e]
[fv-az1267-279:64562] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ffb604288ff]
[fv-az1267-279:64562] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ffb608a5ff5]
[fv-az1267-279:64562] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ffb608bb0da]
[fv-az1267-279:64562] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ffb608a5a55]
[fv-az1267-279:64562] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ffb608a5a6f]
[fv-az1267-279:64562] [ 8] plumed_master(+0x146dd)[0x55d5bce856dd]
[fv-az1267-279:64562] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ffb6042a1ca]
[fv-az1267-279:64562] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ffb6042a28b]
[fv-az1267-279:64562] [11] plumed_master(+0x15365)[0x55d5bce86365]
[fv-az1267-279:64562] *** End of error message ***
</pre>
{% endraw %}
