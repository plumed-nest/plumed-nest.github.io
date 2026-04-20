**Project ID:** [plumID:25.021]({{ '/' | absolute_url }}eggs/25/021/)  
Stderr for source:  S5-G4/geometric/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action FIT_TO_TEMPLATE with label @8 : missing input file conf_template.pdb
[runnervmeorf1:05509] *** Process received signal ***
[runnervmeorf1:05509] Signal: Aborted (6)
[runnervmeorf1:05509] Signal code:  (-6)
[runnervmeorf1:05509] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f10e2e45330]
[runnervmeorf1:05509] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f10e2e9eb2c]
[runnervmeorf1:05509] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f10e2e4527e]
[runnervmeorf1:05509] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f10e2e288ff]
[runnervmeorf1:05509] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f10e32a5ff5]
[runnervmeorf1:05509] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f10e32bb0da]
[runnervmeorf1:05509] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f10e32a5a55]
[runnervmeorf1:05509] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f10e32a5a6f]
[runnervmeorf1:05509] [ 8] plumed_master(+0x146dd)[0x5598b09036dd]
[runnervmeorf1:05509] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f10e2e2a1ca]
[runnervmeorf1:05509] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f10e2e2a28b]
[runnervmeorf1:05509] [11] plumed_master(+0x15365)[0x5598b0904365]
[runnervmeorf1:05509] *** End of error message ***
</pre>
{% endraw %}
