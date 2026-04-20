**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT1_Methanal_and_Cyanide_and_Amoniac/OLD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmeorf1:06674] *** Process received signal ***
[runnervmeorf1:06674] Signal: Aborted (6)
[runnervmeorf1:06674] Signal code:  (-6)
[runnervmeorf1:06674] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5396045330]
[runnervmeorf1:06674] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f539609eb2c]
[runnervmeorf1:06674] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f539604527e]
[runnervmeorf1:06674] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f53960288ff]
[runnervmeorf1:06674] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f53964a5ff5]
[runnervmeorf1:06674] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f53964bb0da]
[runnervmeorf1:06674] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f53964a5a55]
[runnervmeorf1:06674] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f53964a5a6f]
[runnervmeorf1:06674] [ 8] plumed_master(+0x146dd)[0x55c09cfd06dd]
[runnervmeorf1:06674] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f539602a1ca]
[runnervmeorf1:06674] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f539602a28b]
[runnervmeorf1:06674] [11] plumed_master(+0x15365)[0x55c09cfd1365]
[runnervmeorf1:06674] *** End of error message ***
</pre>
{% endraw %}
