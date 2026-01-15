**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[runnervmi13qx:38867] *** Process received signal ***
[runnervmi13qx:38867] Signal: Aborted (6)
[runnervmi13qx:38867] Signal code:  (-6)
[runnervmi13qx:38867] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8acb445330]
[runnervmi13qx:38867] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8acb49eb2c]
[runnervmi13qx:38867] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8acb44527e]
[runnervmi13qx:38867] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8acb4288ff]
[runnervmi13qx:38867] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8acb8a5ff5]
[runnervmi13qx:38867] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8acb8bb0da]
[runnervmi13qx:38867] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8acb8a5a55]
[runnervmi13qx:38867] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8acb8a5a6f]
[runnervmi13qx:38867] [ 8] plumed(+0x146dd)[0x55b492bbc6dd]
[runnervmi13qx:38867] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8acb42a1ca]
[runnervmi13qx:38867] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8acb42a28b]
[runnervmi13qx:38867] [11] plumed(+0x15365)[0x55b492bbd365]
[runnervmi13qx:38867] *** End of error message ***
</pre>
{% endraw %}
