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
[runnervmkj6or:06810] *** Process received signal ***
[runnervmkj6or:06810] Signal: Aborted (6)
[runnervmkj6or:06810] Signal code:  (-6)
[runnervmkj6or:06810] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f069a245330]
[runnervmkj6or:06810] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f069a29eb2c]
[runnervmkj6or:06810] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f069a24527e]
[runnervmkj6or:06810] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f069a2288ff]
[runnervmkj6or:06810] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f069a6a5ff5]
[runnervmkj6or:06810] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f069a6bb0da]
[runnervmkj6or:06810] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f069a6a5a55]
[runnervmkj6or:06810] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f069a6a5a6f]
[runnervmkj6or:06810] [ 8] plumed_master(+0x146dd)[0x5630d88e46dd]
[runnervmkj6or:06810] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f069a22a1ca]
[runnervmkj6or:06810] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f069a22a28b]
[runnervmkj6or:06810] [11] plumed_master(+0x15365)[0x5630d88e5365]
[runnervmkj6or:06810] *** End of error message ***
</pre>
{% endraw %}
