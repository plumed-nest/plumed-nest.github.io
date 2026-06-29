**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
Download: [zipped raw stdout](plumed_tor.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_tor.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS141=9314,9319,9310,9313" is not known.
[runnervmmklqx:09450] *** Process received signal ***
[runnervmmklqx:09450] Signal: Aborted (6)
[runnervmmklqx:09450] Signal code:  (-6)
[runnervmmklqx:09450] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fba4d445330]
[runnervmmklqx:09450] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fba4d49eb2c]
[runnervmmklqx:09450] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fba4d44527e]
[runnervmmklqx:09450] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fba4d4288ff]
[runnervmmklqx:09450] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fba4d8a5ff5]
[runnervmmklqx:09450] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fba4d8bb0da]
[runnervmmklqx:09450] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fba4d8a5a55]
[runnervmmklqx:09450] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fba4d8a5a6f]
[runnervmmklqx:09450] [ 8] plumed_master(+0x146dd)[0x559801e346dd]
[runnervmmklqx:09450] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fba4d42a1ca]
[runnervmmklqx:09450] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fba4d42a28b]
[runnervmmklqx:09450] [11] plumed_master(+0x15365)[0x559801e35365]
[runnervmmklqx:09450] *** End of error message ***
</pre>
{% endraw %}
