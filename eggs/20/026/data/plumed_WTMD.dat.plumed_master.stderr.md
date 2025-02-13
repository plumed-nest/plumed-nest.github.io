**Project ID:** [plumID:20.026]({{ '/' | absolute_url }}eggs/20/026/)  
Stderr for source:  plumed_WTMD.dat   
Download: [zipped raw stdout](plumed_WTMD.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_WTMD.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @79 : keyword ARG is compulsory for this action
[fv-az1280-696:12580] *** Process received signal ***
[fv-az1280-696:12580] Signal: Aborted (6)
[fv-az1280-696:12580] Signal code:  (-6)
[fv-az1280-696:12580] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f67e3045330]
[fv-az1280-696:12580] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f67e309eb2c]
[fv-az1280-696:12580] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f67e304527e]
[fv-az1280-696:12580] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f67e30288ff]
[fv-az1280-696:12580] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f67e34a5ff5]
[fv-az1280-696:12580] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f67e34bb0da]
[fv-az1280-696:12580] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f67e34a5a55]
[fv-az1280-696:12580] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f67e34a5a6f]
[fv-az1280-696:12580] [ 8] plumed_master(+0x146dd)[0x55ece27b96dd]
[fv-az1280-696:12580] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f67e302a1ca]
[fv-az1280-696:12580] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f67e302a28b]
[fv-az1280-696:12580] [11] plumed_master(+0x15365)[0x55ece27ba365]
[fv-az1280-696:12580] *** End of error message ***
</pre>
{% endraw %}
