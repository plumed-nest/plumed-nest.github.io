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
[fv-az1665-105:62323] *** Process received signal ***
[fv-az1665-105:62323] Signal: Aborted (6)
[fv-az1665-105:62323] Signal code:  (-6)
[fv-az1665-105:62323] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f859dc45330]
[fv-az1665-105:62323] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f859dc9eb2c]
[fv-az1665-105:62323] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f859dc4527e]
[fv-az1665-105:62323] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f859dc288ff]
[fv-az1665-105:62323] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f859e0a5ff5]
[fv-az1665-105:62323] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f859e0bb0da]
[fv-az1665-105:62323] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f859e0a5a55]
[fv-az1665-105:62323] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f859e0a5a6f]
[fv-az1665-105:62323] [ 8] plumed_master(+0x146dd)[0x564951f6e6dd]
[fv-az1665-105:62323] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f859dc2a1ca]
[fv-az1665-105:62323] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f859dc2a28b]
[fv-az1665-105:62323] [11] plumed_master(+0x15365)[0x564951f6f365]
[fv-az1665-105:62323] *** End of error message ***
</pre>
{% endraw %}
