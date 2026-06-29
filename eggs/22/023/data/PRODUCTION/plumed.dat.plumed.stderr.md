**Project ID:** [plumID:22.023]({{ '/' | absolute_url }}eggs/22/023/)  
Stderr for source:  PRODUCTION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/GenericMolInfo.cpp:93) PLMD::GenericMolInfo::GenericMolInfo(const PLMD::ActionOptions&)
missing input file ../structure.pdb
[runnervmmklqx:09394] *** Process received signal ***
[runnervmmklqx:09394] Signal: Aborted (6)
[runnervmmklqx:09394] Signal code:  (-6)
[runnervmmklqx:09394] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efd38045330]
[runnervmmklqx:09394] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efd3809eb2c]
[runnervmmklqx:09394] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efd3804527e]
[runnervmmklqx:09394] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efd380288ff]
[runnervmmklqx:09394] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efd384a5ff5]
[runnervmmklqx:09394] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efd384bb0da]
[runnervmmklqx:09394] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efd384a5a55]
[runnervmmklqx:09394] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efd384a5a6f]
[runnervmmklqx:09394] [ 8] plumed(+0x146dd)[0x559651e056dd]
[runnervmmklqx:09394] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efd3802a1ca]
[runnervmmklqx:09394] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efd3802a28b]
[runnervmmklqx:09394] [11] plumed(+0x15365)[0x559651e06365]
[runnervmmklqx:09394] *** End of error message ***
</pre>
{% endraw %}
