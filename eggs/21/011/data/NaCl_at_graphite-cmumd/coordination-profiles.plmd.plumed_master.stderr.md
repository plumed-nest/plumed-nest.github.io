**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/coordination-profiles.plmd   
Download: [zipped raw stdout](coordination-profiles.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](coordination-profiles.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[fv-az1921-959:67596] *** Process received signal ***
[fv-az1921-959:67596] Signal: Aborted (6)
[fv-az1921-959:67596] Signal code:  (-6)
[fv-az1921-959:67596] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9fcba45330]
[fv-az1921-959:67596] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9fcba9eb2c]
[fv-az1921-959:67596] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9fcba4527e]
[fv-az1921-959:67596] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9fcba288ff]
[fv-az1921-959:67596] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9fcbea5ff5]
[fv-az1921-959:67596] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9fcbebb0da]
[fv-az1921-959:67596] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9fcbea5a55]
[fv-az1921-959:67596] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9fcbea5a6f]
[fv-az1921-959:67596] [ 8] plumed_master(+0x146dd)[0x563f3fe246dd]
[fv-az1921-959:67596] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9fcba2a1ca]
[fv-az1921-959:67596] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9fcba2a28b]
[fv-az1921-959:67596] [11] plumed_master(+0x15365)[0x563f3fe25365]
[fv-az1921-959:67596] *** End of error message ***
</pre>
{% endraw %}
