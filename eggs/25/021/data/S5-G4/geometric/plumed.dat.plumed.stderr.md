**Project ID:** [plumID:25.021]({{ '/' | absolute_url }}eggs/25/021/)  
Stderr for source:  S5-G4/geometric/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action FIT_TO_TEMPLATE with label @8 : missing input file conf_template.pdb
[runnervmeorf1:05493] *** Process received signal ***
[runnervmeorf1:05493] Signal: Aborted (6)
[runnervmeorf1:05493] Signal code:  (-6)
[runnervmeorf1:05493] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8a83645330]
[runnervmeorf1:05493] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8a8369eb2c]
[runnervmeorf1:05493] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8a8364527e]
[runnervmeorf1:05493] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8a836288ff]
[runnervmeorf1:05493] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8a83aa5ff5]
[runnervmeorf1:05493] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8a83abb0da]
[runnervmeorf1:05493] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8a83aa5a55]
[runnervmeorf1:05493] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8a83aa5a6f]
[runnervmeorf1:05493] [ 8] plumed(+0x146dd)[0x55e2043b96dd]
[runnervmeorf1:05493] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8a8362a1ca]
[runnervmeorf1:05493] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8a8362a28b]
[runnervmeorf1:05493] [11] plumed(+0x15365)[0x55e2043ba365]
[runnervmeorf1:05493] *** End of error message ***
</pre>
{% endraw %}
