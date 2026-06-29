**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
Download: [zipped raw stdout](plumed_mo.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_mo.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS285=9378,9382" is not known.
[runnervmmklqx:09383] *** Process received signal ***
[runnervmmklqx:09383] Signal: Aborted (6)
[runnervmmklqx:09383] Signal code:  (-6)
[runnervmmklqx:09383] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3cc3a45330]
[runnervmmklqx:09383] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3cc3a9eb2c]
[runnervmmklqx:09383] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3cc3a4527e]
[runnervmmklqx:09383] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3cc3a288ff]
[runnervmmklqx:09383] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3cc3ea5ff5]
[runnervmmklqx:09383] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3cc3ebb0da]
[runnervmmklqx:09383] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3cc3ea5a55]
[runnervmmklqx:09383] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3cc3ea5a6f]
[runnervmmklqx:09383] [ 8] plumed(+0x146dd)[0x55b61b6b96dd]
[runnervmmklqx:09383] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3cc3a2a1ca]
[runnervmmklqx:09383] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3cc3a2a28b]
[runnervmmklqx:09383] [11] plumed(+0x15365)[0x55b61b6ba365]
[runnervmmklqx:09383] *** End of error message ***
</pre>
{% endraw %}
