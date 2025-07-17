**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../structure.pdb
[pkrvmq0rgcvqdmg:09077] *** Process received signal ***
[pkrvmq0rgcvqdmg:09077] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:09077] Signal code:  (-6)
[pkrvmq0rgcvqdmg:09077] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fec6e045330]
[pkrvmq0rgcvqdmg:09077] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fec6e09eb2c]
[pkrvmq0rgcvqdmg:09077] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fec6e04527e]
[pkrvmq0rgcvqdmg:09077] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fec6e0288ff]
[pkrvmq0rgcvqdmg:09077] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fec6e4a5ff5]
[pkrvmq0rgcvqdmg:09077] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fec6e4bb0da]
[pkrvmq0rgcvqdmg:09077] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fec6e4a5a55]
[pkrvmq0rgcvqdmg:09077] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fec6e4a5a6f]
[pkrvmq0rgcvqdmg:09077] [ 8] plumed(+0x146dd)[0x5593b12fd6dd]
[pkrvmq0rgcvqdmg:09077] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fec6e02a1ca]
[pkrvmq0rgcvqdmg:09077] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fec6e02a28b]
[pkrvmq0rgcvqdmg:09077] [11] plumed(+0x15365)[0x5593b12fe365]
[pkrvmq0rgcvqdmg:09077] *** End of error message ***
</pre>
{% endraw %}
