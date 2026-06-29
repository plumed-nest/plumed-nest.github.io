**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[runnervmmklqx:06311] *** Process received signal ***
[runnervmmklqx:06311] Signal: Aborted (6)
[runnervmmklqx:06311] Signal code:  (-6)
[runnervmmklqx:06311] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcf57645330]
[runnervmmklqx:06311] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcf5769eb2c]
[runnervmmklqx:06311] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcf5764527e]
[runnervmmklqx:06311] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcf576288ff]
[runnervmmklqx:06311] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcf57aa5ff5]
[runnervmmklqx:06311] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcf57abb0da]
[runnervmmklqx:06311] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcf57aa5a55]
[runnervmmklqx:06311] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcf57aa5a6f]
[runnervmmklqx:06311] [ 8] plumed_master(+0x146dd)[0x55edf22516dd]
[runnervmmklqx:06311] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcf5762a1ca]
[runnervmmklqx:06311] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcf5762a28b]
[runnervmmklqx:06311] [11] plumed_master(+0x15365)[0x55edf2252365]
[runnervmmklqx:06311] *** End of error message ***
</pre>
{% endraw %}
