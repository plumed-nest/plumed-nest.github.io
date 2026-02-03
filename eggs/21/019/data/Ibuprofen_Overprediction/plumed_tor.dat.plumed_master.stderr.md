**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
Download: [zipped raw stdout](plumed_tor.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_tor.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS141=9314,9319,9310,9313" is not known.
[runnervmkj6or:07732] *** Process received signal ***
[runnervmkj6or:07732] Signal: Aborted (6)
[runnervmkj6or:07732] Signal code:  (-6)
[runnervmkj6or:07732] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa4c0445330]
[runnervmkj6or:07732] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa4c049eb2c]
[runnervmkj6or:07732] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa4c044527e]
[runnervmkj6or:07732] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa4c04288ff]
[runnervmkj6or:07732] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa4c08a5ff5]
[runnervmkj6or:07732] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa4c08bb0da]
[runnervmkj6or:07732] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa4c08a5a55]
[runnervmkj6or:07732] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa4c08a5a6f]
[runnervmkj6or:07732] [ 8] plumed_master(+0x146dd)[0x5608026446dd]
[runnervmkj6or:07732] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa4c042a1ca]
[runnervmkj6or:07732] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa4c042a28b]
[runnervmkj6or:07732] [11] plumed_master(+0x15365)[0x560802645365]
[runnervmkj6or:07732] *** End of error message ***
</pre>
{% endraw %}
