**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT1_Methanal_and_Cyanide_and_Amoniac/FORCE_ESTIMATION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmklqx:06240] *** Process received signal ***
[runnervmmklqx:06240] Signal: Aborted (6)
[runnervmmklqx:06240] Signal code:  (-6)
[runnervmmklqx:06240] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f62bc245330]
[runnervmmklqx:06240] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f62bc29eb2c]
[runnervmmklqx:06240] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f62bc24527e]
[runnervmmklqx:06240] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f62bc2288ff]
[runnervmmklqx:06240] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f62bc6a5ff5]
[runnervmmklqx:06240] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f62bc6bb0da]
[runnervmmklqx:06240] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f62bc6a5a55]
[runnervmmklqx:06240] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f62bc6a5a6f]
[runnervmmklqx:06240] [ 8] plumed(+0x146dd)[0x559c09e736dd]
[runnervmmklqx:06240] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f62bc22a1ca]
[runnervmmklqx:06240] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f62bc22a28b]
[runnervmmklqx:06240] [11] plumed(+0x15365)[0x559c09e74365]
[runnervmmklqx:06240] *** End of error message ***
</pre>
{% endraw %}
