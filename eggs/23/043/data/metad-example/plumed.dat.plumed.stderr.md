**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[runnervmmklqx:06294] *** Process received signal ***
[runnervmmklqx:06294] Signal: Aborted (6)
[runnervmmklqx:06294] Signal code:  (-6)
[runnervmmklqx:06294] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7ff6a45330]
[runnervmmklqx:06294] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7ff6a9eb2c]
[runnervmmklqx:06294] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7ff6a4527e]
[runnervmmklqx:06294] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7ff6a288ff]
[runnervmmklqx:06294] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7ff6ea5ff5]
[runnervmmklqx:06294] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7ff6ebb0da]
[runnervmmklqx:06294] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7ff6ea5a55]
[runnervmmklqx:06294] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7ff6ea5a6f]
[runnervmmklqx:06294] [ 8] plumed(+0x146dd)[0x55b65f4796dd]
[runnervmmklqx:06294] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7ff6a2a1ca]
[runnervmmklqx:06294] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7ff6a2a28b]
[runnervmmklqx:06294] [11] plumed(+0x15365)[0x55b65f47a365]
[runnervmmklqx:06294] *** End of error message ***
</pre>
{% endraw %}
