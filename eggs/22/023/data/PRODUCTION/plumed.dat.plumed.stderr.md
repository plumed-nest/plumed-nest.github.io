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
[pkrvmxyh4eaekms:07428] *** Process received signal ***
[pkrvmxyh4eaekms:07428] Signal: Aborted (6)
[pkrvmxyh4eaekms:07428] Signal code:  (-6)
[pkrvmxyh4eaekms:07428] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f00e4e45330]
[pkrvmxyh4eaekms:07428] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f00e4e9eb2c]
[pkrvmxyh4eaekms:07428] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f00e4e4527e]
[pkrvmxyh4eaekms:07428] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f00e4e288ff]
[pkrvmxyh4eaekms:07428] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f00e52a5ff5]
[pkrvmxyh4eaekms:07428] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f00e52bb0da]
[pkrvmxyh4eaekms:07428] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f00e52a5a55]
[pkrvmxyh4eaekms:07428] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f00e52a5a6f]
[pkrvmxyh4eaekms:07428] [ 8] plumed(+0x146dd)[0x5575231066dd]
[pkrvmxyh4eaekms:07428] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f00e4e2a1ca]
[pkrvmxyh4eaekms:07428] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f00e4e2a28b]
[pkrvmxyh4eaekms:07428] [11] plumed(+0x15365)[0x557523107365]
[pkrvmxyh4eaekms:07428] *** End of error message ***
</pre>
{% endraw %}
