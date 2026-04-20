**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[runnervmeorf1:09747] *** Process received signal ***
[runnervmeorf1:09747] Signal: Aborted (6)
[runnervmeorf1:09747] Signal code:  (-6)
[runnervmeorf1:09747] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff43b645330]
[runnervmeorf1:09747] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff43b69eb2c]
[runnervmeorf1:09747] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff43b64527e]
[runnervmeorf1:09747] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff43b6288ff]
[runnervmeorf1:09747] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff43baa5ff5]
[runnervmeorf1:09747] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff43babb0da]
[runnervmeorf1:09747] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff43baa5a55]
[runnervmeorf1:09747] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff43baa5a6f]
[runnervmeorf1:09747] [ 8] plumed(+0x146dd)[0x555d9cd226dd]
[runnervmeorf1:09747] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff43b62a1ca]
[runnervmeorf1:09747] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff43b62a28b]
[runnervmeorf1:09747] [11] plumed(+0x15365)[0x555d9cd23365]
[runnervmeorf1:09747] *** End of error message ***
</pre>
{% endraw %}
