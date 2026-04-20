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
[runnervmeorf1:08650] *** Process received signal ***
[runnervmeorf1:08650] Signal: Aborted (6)
[runnervmeorf1:08650] Signal code:  (-6)
[runnervmeorf1:08650] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f914ce45330]
[runnervmeorf1:08650] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f914ce9eb2c]
[runnervmeorf1:08650] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f914ce4527e]
[runnervmeorf1:08650] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f914ce288ff]
[runnervmeorf1:08650] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f914d2a5ff5]
[runnervmeorf1:08650] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f914d2bb0da]
[runnervmeorf1:08650] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f914d2a5a55]
[runnervmeorf1:08650] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f914d2a5a6f]
[runnervmeorf1:08650] [ 8] plumed_master(+0x146dd)[0x5640e5bcf6dd]
[runnervmeorf1:08650] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f914ce2a1ca]
[runnervmeorf1:08650] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f914ce2a28b]
[runnervmeorf1:08650] [11] plumed_master(+0x15365)[0x5640e5bd0365]
[runnervmeorf1:08650] *** End of error message ***
</pre>
{% endraw %}
