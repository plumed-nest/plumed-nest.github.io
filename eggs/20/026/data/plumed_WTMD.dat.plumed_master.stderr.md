**Project ID:** [plumID:20.026]({{ '/' | absolute_url }}eggs/20/026/)  
Stderr for source:  plumed_WTMD.dat   
Download: [zipped raw stdout](plumed_WTMD.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_WTMD.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @69 : keyword ARG is compulsory for this action
[runnervmmtnos:36603] *** Process received signal ***
[runnervmmtnos:36603] Signal: Aborted (6)
[runnervmmtnos:36603] Signal code:  (-6)
[runnervmmtnos:36603] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5578e45330]
[runnervmmtnos:36603] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5578e9eb2c]
[runnervmmtnos:36603] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5578e4527e]
[runnervmmtnos:36603] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5578e288ff]
[runnervmmtnos:36603] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f55792a5ff5]
[runnervmmtnos:36603] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f55792bb0da]
[runnervmmtnos:36603] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f55792a5a55]
[runnervmmtnos:36603] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f55792a5a6f]
[runnervmmtnos:36603] [ 8] plumed_master(+0x146dd)[0x555613b3b6dd]
[runnervmmtnos:36603] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5578e2a1ca]
[runnervmmtnos:36603] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5578e2a28b]
[runnervmmtnos:36603] [11] plumed_master(+0x15365)[0x555613b3c365]
[runnervmmtnos:36603] *** End of error message ***
</pre>
{% endraw %}
