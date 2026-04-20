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
[runnervmeorf1:08778] *** Process received signal ***
[runnervmeorf1:08778] Signal: Aborted (6)
[runnervmeorf1:08778] Signal code:  (-6)
[runnervmeorf1:08778] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2a24845330]
[runnervmeorf1:08778] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2a2489eb2c]
[runnervmeorf1:08778] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2a2484527e]
[runnervmeorf1:08778] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2a248288ff]
[runnervmeorf1:08778] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2a24ca5ff5]
[runnervmeorf1:08778] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2a24cbb0da]
[runnervmeorf1:08778] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2a24ca5a55]
[runnervmeorf1:08778] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2a24ca5a6f]
[runnervmeorf1:08778] [ 8] plumed_master(+0x146dd)[0x564a2595b6dd]
[runnervmeorf1:08778] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2a2482a1ca]
[runnervmeorf1:08778] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2a2482a28b]
[runnervmeorf1:08778] [11] plumed_master(+0x15365)[0x564a2595c365]
[runnervmeorf1:08778] *** End of error message ***
</pre>
{% endraw %}
