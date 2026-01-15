**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT1_Methanal_and_Cyanide_and_Amoniac/FORCE_ESTIMATION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmi13qx:32568] *** Process received signal ***
[runnervmi13qx:32568] Signal: Aborted (6)
[runnervmi13qx:32568] Signal code:  (-6)
[runnervmi13qx:32568] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6d26245330]
[runnervmi13qx:32568] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6d2629eb2c]
[runnervmi13qx:32568] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6d2624527e]
[runnervmi13qx:32568] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6d262288ff]
[runnervmi13qx:32568] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6d266a5ff5]
[runnervmi13qx:32568] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6d266bb0da]
[runnervmi13qx:32568] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6d266a5a55]
[runnervmi13qx:32568] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6d266a5a6f]
[runnervmi13qx:32568] [ 8] plumed(+0x146dd)[0x55cf8a83e6dd]
[runnervmi13qx:32568] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6d2622a1ca]
[runnervmi13qx:32568] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6d2622a28b]
[runnervmi13qx:32568] [11] plumed(+0x15365)[0x55cf8a83f365]
[runnervmi13qx:32568] *** End of error message ***
</pre>
{% endraw %}
