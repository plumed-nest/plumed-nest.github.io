**Project ID:** [plumID:20.026]({{ '/' | absolute_url }}eggs/20/026/)  
Stderr for source:  plumed_WTMD.dat   
Download: [zipped raw stdout](plumed_WTMD.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_WTMD.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @78 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:11950] *** Process received signal ***
[pkrvmbietmlfzoi:11950] Signal: Aborted (6)
[pkrvmbietmlfzoi:11950] Signal code:  (-6)
[pkrvmbietmlfzoi:11950] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb0d8245330]
[pkrvmbietmlfzoi:11950] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb0d829eb2c]
[pkrvmbietmlfzoi:11950] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb0d824527e]
[pkrvmbietmlfzoi:11950] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb0d82288ff]
[pkrvmbietmlfzoi:11950] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb0d86a5ff5]
[pkrvmbietmlfzoi:11950] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb0d86bb0da]
[pkrvmbietmlfzoi:11950] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb0d86a5a55]
[pkrvmbietmlfzoi:11950] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb0d86a5a6f]
[pkrvmbietmlfzoi:11950] [ 8] plumed_master(+0x146dd)[0x55fe73eaa6dd]
[pkrvmbietmlfzoi:11950] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb0d822a1ca]
[pkrvmbietmlfzoi:11950] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb0d822a28b]
[pkrvmbietmlfzoi:11950] [11] plumed_master(+0x15365)[0x55fe73eab365]
[pkrvmbietmlfzoi:11950] *** End of error message ***
</pre>
{% endraw %}
