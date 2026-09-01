**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../structure.pdb
[runnervmgx7h7:08014] *** Process received signal ***
[runnervmgx7h7:08014] Signal: Aborted (6)
[runnervmgx7h7:08014] Signal code:  (-6)
[runnervmgx7h7:08014] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f03aea45330]
[runnervmgx7h7:08014] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f03aea9ec0c]
[runnervmgx7h7:08014] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f03aea4527e]
[runnervmgx7h7:08014] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f03aea288ff]
[runnervmgx7h7:08014] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f03aeea5ff5]
[runnervmgx7h7:08014] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f03aeebb0da]
[runnervmgx7h7:08014] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f03aeea5a55]
[runnervmgx7h7:08014] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f03aeea5a6f]
[runnervmgx7h7:08014] [ 8] plumed_master(+0x146dd)[0x55c33d2d06dd]
[runnervmgx7h7:08014] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f03aea2a1ca]
[runnervmgx7h7:08014] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f03aea2a28b]
[runnervmgx7h7:08014] [11] plumed_master(+0x15365)[0x55c33d2d1365]
[runnervmgx7h7:08014] *** End of error message ***
</pre>
{% endraw %}
