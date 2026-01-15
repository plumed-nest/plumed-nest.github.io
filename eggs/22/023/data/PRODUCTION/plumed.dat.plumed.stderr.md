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
[runnervmmtnos:34584] *** Process received signal ***
[runnervmmtnos:34584] Signal: Aborted (6)
[runnervmmtnos:34584] Signal code:  (-6)
[runnervmmtnos:34584] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdf06a45330]
[runnervmmtnos:34584] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdf06a9eb2c]
[runnervmmtnos:34584] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdf06a4527e]
[runnervmmtnos:34584] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdf06a288ff]
[runnervmmtnos:34584] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdf06ea5ff5]
[runnervmmtnos:34584] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdf06ebb0da]
[runnervmmtnos:34584] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdf06ea5a55]
[runnervmmtnos:34584] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdf06ea5a6f]
[runnervmmtnos:34584] [ 8] plumed(+0x146dd)[0x55867ea646dd]
[runnervmmtnos:34584] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdf06a2a1ca]
[runnervmmtnos:34584] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdf06a2a28b]
[runnervmmtnos:34584] [11] plumed(+0x15365)[0x55867ea65365]
[runnervmmtnos:34584] *** End of error message ***
</pre>
{% endraw %}
