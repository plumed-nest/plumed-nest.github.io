**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/coordination-profiles.plmd   
Download: [zipped raw stdout](coordination-profiles.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](coordination-profiles.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[fv-az1280-696:12132] *** Process received signal ***
[fv-az1280-696:12132] Signal: Aborted (6)
[fv-az1280-696:12132] Signal code:  (-6)
[fv-az1280-696:12132] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa25d245330]
[fv-az1280-696:12132] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa25d29eb2c]
[fv-az1280-696:12132] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa25d24527e]
[fv-az1280-696:12132] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa25d2288ff]
[fv-az1280-696:12132] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa25d6a5ff5]
[fv-az1280-696:12132] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa25d6bb0da]
[fv-az1280-696:12132] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa25d6a5a55]
[fv-az1280-696:12132] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa25d6a5a6f]
[fv-az1280-696:12132] [ 8] plumed_master(+0x146dd)[0x55fe9ab666dd]
[fv-az1280-696:12132] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa25d22a1ca]
[fv-az1280-696:12132] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa25d22a28b]
[fv-az1280-696:12132] [11] plumed_master(+0x15365)[0x55fe9ab67365]
[fv-az1280-696:12132] *** End of error message ***
</pre>
{% endraw %}
