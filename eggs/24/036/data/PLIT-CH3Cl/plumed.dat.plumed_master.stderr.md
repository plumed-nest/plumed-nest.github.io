**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-CH3Cl/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[runnervmmklqx:05833] *** Process received signal ***
[runnervmmklqx:05833] Signal: Aborted (6)
[runnervmmklqx:05833] Signal code:  (-6)
[runnervmmklqx:05833] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f22cae45330]
[runnervmmklqx:05833] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f22cae9eb2c]
[runnervmmklqx:05833] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f22cae4527e]
[runnervmmklqx:05833] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f22cae288ff]
[runnervmmklqx:05833] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f22cb2a5ff5]
[runnervmmklqx:05833] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f22cb2bb0da]
[runnervmmklqx:05833] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f22cb2a5a55]
[runnervmmklqx:05833] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f22cb2a5a6f]
[runnervmmklqx:05833] [ 8] plumed_master(+0x146dd)[0x55d738bca6dd]
[runnervmmklqx:05833] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f22cae2a1ca]
[runnervmmklqx:05833] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f22cae2a28b]
[runnervmmklqx:05833] [11] plumed_master(+0x15365)[0x55d738bcb365]
[runnervmmklqx:05833] *** End of error message ***
</pre>
{% endraw %}
