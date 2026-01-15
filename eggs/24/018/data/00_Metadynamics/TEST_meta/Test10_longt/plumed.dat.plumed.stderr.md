**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test10_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmi13qx:32104] *** Process received signal ***
[runnervmi13qx:32104] Signal: Aborted (6)
[runnervmi13qx:32104] Signal code:  (-6)
[runnervmi13qx:32104] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd25ea45330]
[runnervmi13qx:32104] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd25ea9eb2c]
[runnervmi13qx:32104] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd25ea4527e]
[runnervmi13qx:32104] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd25ea288ff]
[runnervmi13qx:32104] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd25eea5ff5]
[runnervmi13qx:32104] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd25eebb0da]
[runnervmi13qx:32104] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd25eea5a55]
[runnervmi13qx:32104] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd25eea5a6f]
[runnervmi13qx:32104] [ 8] plumed(+0x146dd)[0x56352a8ff6dd]
[runnervmi13qx:32104] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd25ea2a1ca]
[runnervmi13qx:32104] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd25ea2a28b]
[runnervmi13qx:32104] [11] plumed(+0x15365)[0x56352a900365]
[runnervmi13qx:32104] *** End of error message ***
</pre>
{% endraw %}
