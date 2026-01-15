**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_urea.dat   
Download: [zipped raw stdout](plumed_urea.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_urea.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX with label @s43 : missing SWITCH11 keyword
[runnervmmtnos:37746] *** Process received signal ***
[runnervmmtnos:37746] Signal: Aborted (6)
[runnervmmtnos:37746] Signal code:  (-6)
[runnervmmtnos:37746] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5c1ec45330]
[runnervmmtnos:37746] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5c1ec9eb2c]
[runnervmmtnos:37746] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5c1ec4527e]
[runnervmmtnos:37746] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5c1ec288ff]
[runnervmmtnos:37746] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5c1f0a5ff5]
[runnervmmtnos:37746] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5c1f0bb0da]
[runnervmmtnos:37746] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5c1f0a5a55]
[runnervmmtnos:37746] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5c1f0a5a6f]
[runnervmmtnos:37746] [ 8] plumed_master(+0x146dd)[0x5602adcc46dd]
[runnervmmtnos:37746] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5c1ec2a1ca]
[runnervmmtnos:37746] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5c1ec2a28b]
[runnervmmtnos:37746] [11] plumed_master(+0x15365)[0x5602adcc5365]
[runnervmmtnos:37746] *** End of error message ***
</pre>
{% endraw %}
