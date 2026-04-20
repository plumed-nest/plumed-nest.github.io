**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2pr_Hydroxydeacetonitrile_and_Amoniac/FORCE_ESTIMATION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmeorf1:06917] *** Process received signal ***
[runnervmeorf1:06917] Signal: Aborted (6)
[runnervmeorf1:06917] Signal code:  (-6)
[runnervmeorf1:06917] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4d85e45330]
[runnervmeorf1:06917] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4d85e9eb2c]
[runnervmeorf1:06917] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4d85e4527e]
[runnervmeorf1:06917] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4d85e288ff]
[runnervmeorf1:06917] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4d862a5ff5]
[runnervmeorf1:06917] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4d862bb0da]
[runnervmeorf1:06917] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4d862a5a55]
[runnervmeorf1:06917] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4d862a5a6f]
[runnervmeorf1:06917] [ 8] plumed(+0x146dd)[0x564b99bf76dd]
[runnervmeorf1:06917] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4d85e2a1ca]
[runnervmeorf1:06917] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4d85e2a28b]
[runnervmeorf1:06917] [11] plumed(+0x15365)[0x564b99bf8365]
[runnervmeorf1:06917] *** End of error message ***
</pre>
{% endraw %}
