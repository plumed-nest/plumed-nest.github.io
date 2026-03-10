**Project ID:** [plumID:21.011]({{ '/' | absolute_url }}eggs/21/011/)  
Stderr for source:  NaCl_at_graphite-cmumd/coordination-profiles.plmd   
Download: [zipped raw stdout](coordination-profiles.plmd.plumed_master.stdout.txt.zip) - [zipped raw stderr](coordination-profiles.plmd.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'std::out_of_range'
what():  map::at
[runnervm0kj6c:11057] *** Process received signal ***
[runnervm0kj6c:11057] Signal: Aborted (6)
[runnervm0kj6c:11057] Signal code:  (-6)
[runnervm0kj6c:11057] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4e23a45330]
[runnervm0kj6c:11057] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4e23a9eb2c]
[runnervm0kj6c:11057] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4e23a4527e]
[runnervm0kj6c:11057] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4e23a288ff]
[runnervm0kj6c:11057] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4e23ea5ff5]
[runnervm0kj6c:11057] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4e23ebb0da]
[runnervm0kj6c:11057] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4e23ea5a55]
[runnervm0kj6c:11057] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4e23ea5a6f]
[runnervm0kj6c:11057] [ 8] plumed_master(+0x146dd)[0x55586d64c6dd]
[runnervm0kj6c:11057] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4e23a2a1ca]
[runnervm0kj6c:11057] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4e23a2a28b]
[runnervm0kj6c:11057] [11] plumed_master(+0x15365)[0x55586d64d365]
[runnervm0kj6c:11057] *** End of error message ***
</pre>
{% endraw %}
