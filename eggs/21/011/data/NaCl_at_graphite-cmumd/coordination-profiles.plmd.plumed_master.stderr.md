**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/coordination-profiles.plmd   
Download: [zipped raw stdout](coordination-profiles.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](coordination-profiles.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[fv-az805-507:11819] *** Process received signal ***
[fv-az805-507:11819] Signal: Aborted (6)
[fv-az805-507:11819] Signal code:  (-6)
[fv-az805-507:11819] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f84b7c45330]
[fv-az805-507:11819] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f84b7c9eb2c]
[fv-az805-507:11819] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f84b7c4527e]
[fv-az805-507:11819] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f84b7c288ff]
[fv-az805-507:11819] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f84b80a5ff5]
[fv-az805-507:11819] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f84b80bb0da]
[fv-az805-507:11819] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f84b80a5a55]
[fv-az805-507:11819] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f84b80a5a6f]
[fv-az805-507:11819] [ 8] plumed_master(+0x146dd)[0x55d111d476dd]
[fv-az805-507:11819] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f84b7c2a1ca]
[fv-az805-507:11819] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f84b7c2a28b]
[fv-az805-507:11819] [11] plumed_master(+0x15365)[0x55d111d48365]
[fv-az805-507:11819] *** End of error message ***
</pre>
{% endraw %}
