**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/coordination-profiles.plmd   
Download: [zipped raw stdout](coordination-profiles.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](coordination-profiles.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[fv-az1344-582:65471] *** Process received signal ***
[fv-az1344-582:65471] Signal: Aborted (6)
[fv-az1344-582:65471] Signal code:  (-6)
[fv-az1344-582:65471] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f77b1845330]
[fv-az1344-582:65471] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f77b189eb2c]
[fv-az1344-582:65471] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f77b184527e]
[fv-az1344-582:65471] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f77b18288ff]
[fv-az1344-582:65471] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f77b1ca5ff5]
[fv-az1344-582:65471] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f77b1cbb0da]
[fv-az1344-582:65471] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f77b1ca5a55]
[fv-az1344-582:65471] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f77b1ca5a6f]
[fv-az1344-582:65471] [ 8] plumed_master(+0x146dd)[0x55db574966dd]
[fv-az1344-582:65471] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f77b182a1ca]
[fv-az1344-582:65471] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f77b182a28b]
[fv-az1344-582:65471] [11] plumed_master(+0x15365)[0x55db57497365]
[fv-az1344-582:65471] *** End of error message ***
</pre>
{% endraw %}
