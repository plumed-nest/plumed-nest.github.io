**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/coordination-profiles.plmd   
Download: [zipped raw stdout](coordination-profiles.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](coordination-profiles.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[runnervmeorf1:09430] *** Process received signal ***
[runnervmeorf1:09430] Signal: Aborted (6)
[runnervmeorf1:09430] Signal code:  (-6)
[runnervmeorf1:09430] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f71f0c45330]
[runnervmeorf1:09430] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f71f0c9eb2c]
[runnervmeorf1:09430] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f71f0c4527e]
[runnervmeorf1:09430] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f71f0c288ff]
[runnervmeorf1:09430] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f71f10a5ff5]
[runnervmeorf1:09430] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f71f10bb0da]
[runnervmeorf1:09430] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f71f10a5a55]
[runnervmeorf1:09430] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f71f10a5a6f]
[runnervmeorf1:09430] [ 8] plumed_master(+0x146dd)[0x55f2bb2176dd]
[runnervmeorf1:09430] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f71f0c2a1ca]
[runnervmeorf1:09430] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f71f0c2a28b]
[runnervmeorf1:09430] [11] plumed_master(+0x15365)[0x55f2bb218365]
[runnervmeorf1:09430] *** End of error message ***
</pre>
{% endraw %}
