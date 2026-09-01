**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/coordination-profiles.plmd   
Download: [zipped raw stdout](coordination-profiles.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](coordination-profiles.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[runnervmgx7h7:11851] *** Process received signal ***
[runnervmgx7h7:11851] Signal: Aborted (6)
[runnervmgx7h7:11851] Signal code:  (-6)
[runnervmgx7h7:11851] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f13f6045330]
[runnervmgx7h7:11851] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f13f609ec0c]
[runnervmgx7h7:11851] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f13f604527e]
[runnervmgx7h7:11851] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f13f60288ff]
[runnervmgx7h7:11851] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f13f64a5ff5]
[runnervmgx7h7:11851] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f13f64bb0da]
[runnervmgx7h7:11851] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f13f64a5a55]
[runnervmgx7h7:11851] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f13f64a5a6f]
[runnervmgx7h7:11851] [ 8] plumed_master(+0x146dd)[0x5617374f76dd]
[runnervmgx7h7:11851] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f13f602a1ca]
[runnervmgx7h7:11851] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f13f602a28b]
[runnervmgx7h7:11851] [11] plumed_master(+0x15365)[0x5617374f8365]
[runnervmgx7h7:11851] *** End of error message ***
</pre>
{% endraw %}
