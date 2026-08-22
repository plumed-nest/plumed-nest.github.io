**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/coordination-profiles.plmd   
Download: [zipped raw stdout](coordination-profiles.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](coordination-profiles.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[runnervm76f27:09337] *** Process received signal ***
[runnervm76f27:09337] Signal: Aborted (6)
[runnervm76f27:09337] Signal code:  (-6)
[runnervm76f27:09337] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb01b445330]
[runnervm76f27:09337] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb01b49ec0c]
[runnervm76f27:09337] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb01b44527e]
[runnervm76f27:09337] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb01b4288ff]
[runnervm76f27:09337] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb01b8a5ff5]
[runnervm76f27:09337] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb01b8bb0da]
[runnervm76f27:09337] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb01b8a5a55]
[runnervm76f27:09337] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb01b8a5a6f]
[runnervm76f27:09337] [ 8] plumed_master(+0x146dd)[0x5584a92e46dd]
[runnervm76f27:09337] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb01b42a1ca]
[runnervm76f27:09337] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb01b42a28b]
[runnervm76f27:09337] [11] plumed_master(+0x15365)[0x5584a92e5365]
[runnervm76f27:09337] *** End of error message ***
</pre>
{% endraw %}
