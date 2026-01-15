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
[runnervmmtnos:34599] *** Process received signal ***
[runnervmmtnos:34599] Signal: Aborted (6)
[runnervmmtnos:34599] Signal code:  (-6)
[runnervmmtnos:34599] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb282a45330]
[runnervmmtnos:34599] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb282a9eb2c]
[runnervmmtnos:34599] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb282a4527e]
[runnervmmtnos:34599] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb282a288ff]
[runnervmmtnos:34599] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb282ea5ff5]
[runnervmmtnos:34599] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb282ebb0da]
[runnervmmtnos:34599] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb282ea5a55]
[runnervmmtnos:34599] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb282ea5a6f]
[runnervmmtnos:34599] [ 8] plumed_master(+0x146dd)[0x55febcd676dd]
[runnervmmtnos:34599] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb282a2a1ca]
[runnervmmtnos:34599] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb282a2a28b]
[runnervmmtnos:34599] [11] plumed_master(+0x15365)[0x55febcd68365]
[runnervmmtnos:34599] *** End of error message ***
</pre>
{% endraw %}
