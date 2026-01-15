**Project ID:** [plumID:23.026]({{ '/' | absolute_url }}eggs/23/026/)  
Stderr for source:  plumed_model_pulling.dat   
Download: [zipped raw stdout](plumed_model_pulling.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_model_pulling.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmi13qx:35285] *** Process received signal ***
[runnervmi13qx:35285] Signal: Aborted (6)
[runnervmi13qx:35285] Signal code:  (-6)
[runnervmi13qx:35285] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbcf8045330]
[runnervmi13qx:35285] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbcf809eb2c]
[runnervmi13qx:35285] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbcf804527e]
[runnervmi13qx:35285] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbcf80288ff]
[runnervmi13qx:35285] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbcf84a5ff5]
[runnervmi13qx:35285] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbcf84bb0da]
[runnervmi13qx:35285] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbcf84a5a55]
[runnervmi13qx:35285] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbcf84a5a6f]
[runnervmi13qx:35285] [ 8] plumed_master(+0x146dd)[0x5609b0bd36dd]
[runnervmi13qx:35285] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbcf802a1ca]
[runnervmi13qx:35285] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbcf802a28b]
[runnervmi13qx:35285] [11] plumed_master(+0x15365)[0x5609b0bd4365]
[runnervmi13qx:35285] *** End of error message ***
</pre>
{% endraw %}
