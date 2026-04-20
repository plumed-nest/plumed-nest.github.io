**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmeorf1:09540] *** Process received signal ***
[runnervmeorf1:09540] Signal: Aborted (6)
[runnervmeorf1:09540] Signal code:  (-6)
[runnervmeorf1:09540] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb608e45330]
[runnervmeorf1:09540] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb608e9eb2c]
[runnervmeorf1:09540] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb608e4527e]
[runnervmeorf1:09540] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb608e288ff]
[runnervmeorf1:09540] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb6092a5ff5]
[runnervmeorf1:09540] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb6092bb0da]
[runnervmeorf1:09540] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb6092a5a55]
[runnervmeorf1:09540] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb6092a5a6f]
[runnervmeorf1:09540] [ 8] plumed(+0x146dd)[0x5624c43ce6dd]
[runnervmeorf1:09540] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb608e2a1ca]
[runnervmeorf1:09540] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb608e2a28b]
[runnervmeorf1:09540] [11] plumed(+0x15365)[0x5624c43cf365]
[runnervmeorf1:09540] *** End of error message ***
</pre>
{% endraw %}
