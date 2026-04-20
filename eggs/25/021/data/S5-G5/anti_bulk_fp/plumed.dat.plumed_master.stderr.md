**Project ID:** [plumID:25.021]({{ '/' | absolute_url }}eggs/25/021/)  
Stderr for source:  S5-G5/anti_bulk_fp/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action FIT_TO_TEMPLATE with label @8 : missing input file conf_template.pdb
[runnervmeorf1:05560] *** Process received signal ***
[runnervmeorf1:05560] Signal: Aborted (6)
[runnervmeorf1:05560] Signal code:  (-6)
[runnervmeorf1:05560] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f56e2645330]
[runnervmeorf1:05560] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f56e269eb2c]
[runnervmeorf1:05560] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f56e264527e]
[runnervmeorf1:05560] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f56e26288ff]
[runnervmeorf1:05560] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f56e2aa5ff5]
[runnervmeorf1:05560] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f56e2abb0da]
[runnervmeorf1:05560] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f56e2aa5a55]
[runnervmeorf1:05560] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f56e2aa5a6f]
[runnervmeorf1:05560] [ 8] plumed_master(+0x146dd)[0x55e82bdf96dd]
[runnervmeorf1:05560] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f56e262a1ca]
[runnervmeorf1:05560] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f56e262a28b]
[runnervmeorf1:05560] [11] plumed_master(+0x15365)[0x55e82bdfa365]
[runnervmeorf1:05560] *** End of error message ***
</pre>
{% endraw %}
