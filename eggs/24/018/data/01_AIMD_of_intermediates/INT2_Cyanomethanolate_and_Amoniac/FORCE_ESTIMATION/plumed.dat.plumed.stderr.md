**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_Cyanomethanolate_and_Amoniac/FORCE_ESTIMATION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmeorf1:06761] *** Process received signal ***
[runnervmeorf1:06761] Signal: Aborted (6)
[runnervmeorf1:06761] Signal code:  (-6)
[runnervmeorf1:06761] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f086d645330]
[runnervmeorf1:06761] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f086d69eb2c]
[runnervmeorf1:06761] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f086d64527e]
[runnervmeorf1:06761] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f086d6288ff]
[runnervmeorf1:06761] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f086daa5ff5]
[runnervmeorf1:06761] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f086dabb0da]
[runnervmeorf1:06761] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f086daa5a55]
[runnervmeorf1:06761] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f086daa5a6f]
[runnervmeorf1:06761] [ 8] plumed(+0x146dd)[0x55d104bbc6dd]
[runnervmeorf1:06761] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f086d62a1ca]
[runnervmeorf1:06761] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f086d62a28b]
[runnervmeorf1:06761] [11] plumed(+0x15365)[0x55d104bbd365]
[runnervmeorf1:06761] *** End of error message ***
</pre>
{% endraw %}
