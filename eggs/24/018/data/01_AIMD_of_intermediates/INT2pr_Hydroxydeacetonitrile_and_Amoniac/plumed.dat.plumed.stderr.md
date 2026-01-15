**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2pr_Hydroxydeacetonitrile_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmi13qx:32927] *** Process received signal ***
[runnervmi13qx:32927] Signal: Aborted (6)
[runnervmi13qx:32927] Signal code:  (-6)
[runnervmi13qx:32927] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f718a445330]
[runnervmi13qx:32927] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f718a49eb2c]
[runnervmi13qx:32927] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f718a44527e]
[runnervmi13qx:32927] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f718a4288ff]
[runnervmi13qx:32927] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f718a8a5ff5]
[runnervmi13qx:32927] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f718a8bb0da]
[runnervmi13qx:32927] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f718a8a5a55]
[runnervmi13qx:32927] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f718a8a5a6f]
[runnervmi13qx:32927] [ 8] plumed(+0x146dd)[0x5615c44d36dd]
[runnervmi13qx:32927] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f718a42a1ca]
[runnervmi13qx:32927] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f718a42a28b]
[runnervmi13qx:32927] [11] plumed(+0x15365)[0x5615c44d4365]
[runnervmi13qx:32927] *** End of error message ***
</pre>
{% endraw %}
