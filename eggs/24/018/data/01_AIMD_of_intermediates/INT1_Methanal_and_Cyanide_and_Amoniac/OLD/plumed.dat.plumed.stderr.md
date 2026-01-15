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
[runnervmi13qx:32619] *** Process received signal ***
[runnervmi13qx:32619] Signal: Aborted (6)
[runnervmi13qx:32619] Signal code:  (-6)
[runnervmi13qx:32619] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6721c45330]
[runnervmi13qx:32619] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6721c9eb2c]
[runnervmi13qx:32619] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6721c4527e]
[runnervmi13qx:32619] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6721c288ff]
[runnervmi13qx:32619] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f67220a5ff5]
[runnervmi13qx:32619] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f67220bb0da]
[runnervmi13qx:32619] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f67220a5a55]
[runnervmi13qx:32619] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f67220a5a6f]
[runnervmi13qx:32619] [ 8] plumed(+0x146dd)[0x55a28908b6dd]
[runnervmi13qx:32619] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6721c2a1ca]
[runnervmi13qx:32619] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6721c2a28b]
[runnervmi13qx:32619] [11] plumed(+0x15365)[0x55a28908c365]
[runnervmi13qx:32619] *** End of error message ***
</pre>
{% endraw %}
