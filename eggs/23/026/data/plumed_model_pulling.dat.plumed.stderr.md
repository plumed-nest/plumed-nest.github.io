**Project ID:** [plumID:23.026]({{ '/' | absolute_url }}eggs/23/026/)  
Stderr for source:  plumed_model_pulling.dat   
Download: [zipped raw stdout](plumed_model_pulling.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_model_pulling.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmi13qx:35269] *** Process received signal ***
[runnervmi13qx:35269] Signal: Aborted (6)
[runnervmi13qx:35269] Signal code:  (-6)
[runnervmi13qx:35269] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fec1d445330]
[runnervmi13qx:35269] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fec1d49eb2c]
[runnervmi13qx:35269] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fec1d44527e]
[runnervmi13qx:35269] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fec1d4288ff]
[runnervmi13qx:35269] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fec1d8a5ff5]
[runnervmi13qx:35269] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fec1d8bb0da]
[runnervmi13qx:35269] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fec1d8a5a55]
[runnervmi13qx:35269] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fec1d8a5a6f]
[runnervmi13qx:35269] [ 8] plumed(+0x146dd)[0x55df3f86a6dd]
[runnervmi13qx:35269] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fec1d42a1ca]
[runnervmi13qx:35269] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fec1d42a28b]
[runnervmi13qx:35269] [11] plumed(+0x15365)[0x55df3f86b365]
[runnervmi13qx:35269] *** End of error message ***
</pre>
{% endraw %}
