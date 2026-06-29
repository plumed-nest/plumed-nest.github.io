**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_Cyanomethanolate_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmklqx:06452] *** Process received signal ***
[runnervmmklqx:06452] Signal: Aborted (6)
[runnervmmklqx:06452] Signal code:  (-6)
[runnervmmklqx:06452] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f23be845330]
[runnervmmklqx:06452] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f23be89eb2c]
[runnervmmklqx:06452] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f23be84527e]
[runnervmmklqx:06452] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f23be8288ff]
[runnervmmklqx:06452] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f23beca5ff5]
[runnervmmklqx:06452] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f23becbb0da]
[runnervmmklqx:06452] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f23beca5a55]
[runnervmmklqx:06452] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f23beca5a6f]
[runnervmmklqx:06452] [ 8] plumed(+0x146dd)[0x55eb6cff16dd]
[runnervmmklqx:06452] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f23be82a1ca]
[runnervmmklqx:06452] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f23be82a28b]
[runnervmmklqx:06452] [11] plumed(+0x15365)[0x55eb6cff2365]
[runnervmmklqx:06452] *** End of error message ***
</pre>
{% endraw %}
