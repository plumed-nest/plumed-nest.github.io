**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-3/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmi13qx:38812] *** Process received signal ***
[runnervmi13qx:38812] Signal: Aborted (6)
[runnervmi13qx:38812] Signal code:  (-6)
[runnervmi13qx:38812] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f814bc45330]
[runnervmi13qx:38812] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f814bc9eb2c]
[runnervmi13qx:38812] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f814bc4527e]
[runnervmi13qx:38812] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f814bc288ff]
[runnervmi13qx:38812] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f814c0a5ff5]
[runnervmi13qx:38812] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f814c0bb0da]
[runnervmi13qx:38812] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f814c0a5a55]
[runnervmi13qx:38812] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f814c0a5a6f]
[runnervmi13qx:38812] [ 8] plumed(+0x146dd)[0x5566a5fd26dd]
[runnervmi13qx:38812] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f814bc2a1ca]
[runnervmi13qx:38812] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f814bc2a28b]
[runnervmi13qx:38812] [11] plumed(+0x15365)[0x5566a5fd3365]
[runnervmi13qx:38812] *** End of error message ***
</pre>
{% endraw %}
