**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/coordination-profiles.plmd   
Download: [zipped raw stdout](coordination-profiles.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](coordination-profiles.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[fv-az1391-351:64614] *** Process received signal ***
[fv-az1391-351:64614] Signal: Aborted (6)
[fv-az1391-351:64614] Signal code:  (-6)
[fv-az1391-351:64614] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1f13845330]
[fv-az1391-351:64614] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1f1389eb2c]
[fv-az1391-351:64614] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1f1384527e]
[fv-az1391-351:64614] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1f138288ff]
[fv-az1391-351:64614] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1f13ca5ff5]
[fv-az1391-351:64614] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1f13cbb0da]
[fv-az1391-351:64614] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1f13ca5a55]
[fv-az1391-351:64614] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1f13ca5a6f]
[fv-az1391-351:64614] [ 8] plumed_master(+0x146dd)[0x556c93ef86dd]
[fv-az1391-351:64614] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1f1382a1ca]
[fv-az1391-351:64614] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1f1382a28b]
[fv-az1391-351:64614] [11] plumed_master(+0x15365)[0x556c93ef9365]
[fv-az1391-351:64614] *** End of error message ***
</pre>
{% endraw %}
