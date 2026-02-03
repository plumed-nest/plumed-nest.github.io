**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/coordination-profiles.plmd   
Download: [zipped raw stdout](coordination-profiles.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](coordination-profiles.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[runnervmkj6or:08099] *** Process received signal ***
[runnervmkj6or:08099] Signal: Aborted (6)
[runnervmkj6or:08099] Signal code:  (-6)
[runnervmkj6or:08099] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe4f6045330]
[runnervmkj6or:08099] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe4f609eb2c]
[runnervmkj6or:08099] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe4f604527e]
[runnervmkj6or:08099] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe4f60288ff]
[runnervmkj6or:08099] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe4f64a5ff5]
[runnervmkj6or:08099] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe4f64bb0da]
[runnervmkj6or:08099] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe4f64a5a55]
[runnervmkj6or:08099] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe4f64a5a6f]
[runnervmkj6or:08099] [ 8] plumed_master(+0x146dd)[0x55a8f9d136dd]
[runnervmkj6or:08099] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe4f602a1ca]
[runnervmkj6or:08099] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe4f602a28b]
[runnervmkj6or:08099] [11] plumed_master(+0x15365)[0x55a8f9d14365]
[runnervmkj6or:08099] *** End of error message ***
</pre>
{% endraw %}
