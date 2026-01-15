**Project ID:** [plumID:25.030]({{ '/' | absolute_url }}eggs/25/030/)  
Stderr for source:  plumed_pulling.dat   
Download: [zipped raw stdout](plumed_pulling.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_pulling.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmi13qx:31652] *** Process received signal ***
[runnervmi13qx:31652] Signal: Aborted (6)
[runnervmi13qx:31652] Signal code:  (-6)
[runnervmi13qx:31652] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f69d1045330]
[runnervmi13qx:31652] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f69d109eb2c]
[runnervmi13qx:31652] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f69d104527e]
[runnervmi13qx:31652] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f69d10288ff]
[runnervmi13qx:31652] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f69d14a5ff5]
[runnervmi13qx:31652] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f69d14bb0da]
[runnervmi13qx:31652] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f69d14a5a55]
[runnervmi13qx:31652] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f69d14a5a6f]
[runnervmi13qx:31652] [ 8] plumed(+0x146dd)[0x55c095ab16dd]
[runnervmi13qx:31652] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f69d102a1ca]
[runnervmi13qx:31652] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f69d102a28b]
[runnervmi13qx:31652] [11] plumed(+0x15365)[0x55c095ab2365]
[runnervmi13qx:31652] *** End of error message ***
</pre>
{% endraw %}
