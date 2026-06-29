**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
Download: [zipped raw stdout](plumed_tor.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_tor.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS141=9314,9319,9310,9313" is not known.
[runnervmmklqx:09434] *** Process received signal ***
[runnervmmklqx:09434] Signal: Aborted (6)
[runnervmmklqx:09434] Signal code:  (-6)
[runnervmmklqx:09434] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd340845330]
[runnervmmklqx:09434] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd34089eb2c]
[runnervmmklqx:09434] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd34084527e]
[runnervmmklqx:09434] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd3408288ff]
[runnervmmklqx:09434] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd340ca5ff5]
[runnervmmklqx:09434] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd340cbb0da]
[runnervmmklqx:09434] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd340ca5a55]
[runnervmmklqx:09434] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd340ca5a6f]
[runnervmmklqx:09434] [ 8] plumed(+0x146dd)[0x564fa2dd36dd]
[runnervmmklqx:09434] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd34082a1ca]
[runnervmmklqx:09434] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd34082a28b]
[runnervmmklqx:09434] [11] plumed(+0x15365)[0x564fa2dd4365]
[runnervmmklqx:09434] *** End of error message ***
</pre>
{% endraw %}
