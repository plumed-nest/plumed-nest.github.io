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
[runnervmi13qx:32722] *** Process received signal ***
[runnervmi13qx:32722] Signal: Aborted (6)
[runnervmi13qx:32722] Signal code:  (-6)
[runnervmi13qx:32722] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8540445330]
[runnervmi13qx:32722] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f854049eb2c]
[runnervmi13qx:32722] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f854044527e]
[runnervmi13qx:32722] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f85404288ff]
[runnervmi13qx:32722] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f85408a5ff5]
[runnervmi13qx:32722] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f85408bb0da]
[runnervmi13qx:32722] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f85408a5a55]
[runnervmi13qx:32722] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f85408a5a6f]
[runnervmi13qx:32722] [ 8] plumed(+0x146dd)[0x55b1f1d366dd]
[runnervmi13qx:32722] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f854042a1ca]
[runnervmi13qx:32722] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f854042a28b]
[runnervmi13qx:32722] [11] plumed(+0x15365)[0x55b1f1d37365]
[runnervmi13qx:32722] *** End of error message ***
</pre>
{% endraw %}
