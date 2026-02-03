**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
Download: [zipped raw stdout](plumed_tor.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_tor.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS141=9314,9319,9310,9313" is not known.
[runnervmkj6or:07716] *** Process received signal ***
[runnervmkj6or:07716] Signal: Aborted (6)
[runnervmkj6or:07716] Signal code:  (-6)
[runnervmkj6or:07716] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fec54e45330]
[runnervmkj6or:07716] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fec54e9eb2c]
[runnervmkj6or:07716] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fec54e4527e]
[runnervmkj6or:07716] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fec54e288ff]
[runnervmkj6or:07716] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fec552a5ff5]
[runnervmkj6or:07716] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fec552bb0da]
[runnervmkj6or:07716] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fec552a5a55]
[runnervmkj6or:07716] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fec552a5a6f]
[runnervmkj6or:07716] [ 8] plumed(+0x146dd)[0x56103e1716dd]
[runnervmkj6or:07716] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fec54e2a1ca]
[runnervmkj6or:07716] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fec54e2a28b]
[runnervmkj6or:07716] [11] plumed(+0x15365)[0x56103e172365]
[runnervmkj6or:07716] *** End of error message ***
</pre>
{% endraw %}
