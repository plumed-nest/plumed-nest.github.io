**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT1_Methanal_and_Cyanide_and_Amoniac/OLD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmkj6or:07437] *** Process received signal ***
[runnervmkj6or:07437] Signal: Aborted (6)
[runnervmkj6or:07437] Signal code:  (-6)
[runnervmkj6or:07437] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4475245330]
[runnervmkj6or:07437] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f447529eb2c]
[runnervmkj6or:07437] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f447524527e]
[runnervmkj6or:07437] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f44752288ff]
[runnervmkj6or:07437] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f44756a5ff5]
[runnervmkj6or:07437] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f44756bb0da]
[runnervmkj6or:07437] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f44756a5a55]
[runnervmkj6or:07437] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f44756a5a6f]
[runnervmkj6or:07437] [ 8] plumed(+0x146dd)[0x55815cbd16dd]
[runnervmkj6or:07437] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f447522a1ca]
[runnervmkj6or:07437] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f447522a28b]
[runnervmkj6or:07437] [11] plumed(+0x15365)[0x55815cbd2365]
[runnervmkj6or:07437] *** End of error message ***
</pre>
{% endraw %}
