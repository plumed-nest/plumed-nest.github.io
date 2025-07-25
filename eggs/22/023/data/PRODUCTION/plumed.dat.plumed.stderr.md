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
[pkrvmpptgkbjq6m:09344] *** Process received signal ***
[pkrvmpptgkbjq6m:09344] Signal: Aborted (6)
[pkrvmpptgkbjq6m:09344] Signal code:  (-6)
[pkrvmpptgkbjq6m:09344] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4b4b445330]
[pkrvmpptgkbjq6m:09344] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4b4b49eb2c]
[pkrvmpptgkbjq6m:09344] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4b4b44527e]
[pkrvmpptgkbjq6m:09344] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4b4b4288ff]
[pkrvmpptgkbjq6m:09344] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4b4b8a5ff5]
[pkrvmpptgkbjq6m:09344] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4b4b8bb0da]
[pkrvmpptgkbjq6m:09344] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4b4b8a5a55]
[pkrvmpptgkbjq6m:09344] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4b4b8a5a6f]
[pkrvmpptgkbjq6m:09344] [ 8] plumed(+0x146dd)[0x55eb90da96dd]
[pkrvmpptgkbjq6m:09344] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4b4b42a1ca]
[pkrvmpptgkbjq6m:09344] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4b4b42a28b]
[pkrvmpptgkbjq6m:09344] [11] plumed(+0x15365)[0x55eb90daa365]
[pkrvmpptgkbjq6m:09344] *** End of error message ***
</pre>
{% endraw %}
