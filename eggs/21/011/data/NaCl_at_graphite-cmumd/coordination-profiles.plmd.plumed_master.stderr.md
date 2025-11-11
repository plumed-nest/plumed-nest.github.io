**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/coordination-profiles.plmd   
Download: [zipped raw stdout](coordination-profiles.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](coordination-profiles.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[runnervmw9dnm:11244] *** Process received signal ***
[runnervmw9dnm:11244] Signal: Aborted (6)
[runnervmw9dnm:11244] Signal code:  (-6)
[runnervmw9dnm:11244] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f00ae445330]
[runnervmw9dnm:11244] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f00ae49eb2c]
[runnervmw9dnm:11244] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f00ae44527e]
[runnervmw9dnm:11244] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f00ae4288ff]
[runnervmw9dnm:11244] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f00ae8a5ff5]
[runnervmw9dnm:11244] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f00ae8bb0da]
[runnervmw9dnm:11244] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f00ae8a5a55]
[runnervmw9dnm:11244] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f00ae8a5a6f]
[runnervmw9dnm:11244] [ 8] plumed_master(+0x146dd)[0x55e5e26556dd]
[runnervmw9dnm:11244] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f00ae42a1ca]
[runnervmw9dnm:11244] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f00ae42a28b]
[runnervmw9dnm:11244] [11] plumed_master(+0x15365)[0x55e5e2656365]
[runnervmw9dnm:11244] *** End of error message ***
</pre>
{% endraw %}
