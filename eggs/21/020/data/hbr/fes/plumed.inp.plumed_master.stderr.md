**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @51 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:12259] *** Process received signal ***
[pkrvmbietmlfzoi:12259] Signal: Aborted (6)
[pkrvmbietmlfzoi:12259] Signal code:  (-6)
[pkrvmbietmlfzoi:12259] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbf2a245330]
[pkrvmbietmlfzoi:12259] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbf2a29eb2c]
[pkrvmbietmlfzoi:12259] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbf2a24527e]
[pkrvmbietmlfzoi:12259] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbf2a2288ff]
[pkrvmbietmlfzoi:12259] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbf2a6a5ff5]
[pkrvmbietmlfzoi:12259] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbf2a6bb0da]
[pkrvmbietmlfzoi:12259] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbf2a6a5a55]
[pkrvmbietmlfzoi:12259] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbf2a6a5a6f]
[pkrvmbietmlfzoi:12259] [ 8] plumed_master(+0x146dd)[0x55dcbd4706dd]
[pkrvmbietmlfzoi:12259] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbf2a22a1ca]
[pkrvmbietmlfzoi:12259] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbf2a22a28b]
[pkrvmbietmlfzoi:12259] [11] plumed_master(+0x15365)[0x55dcbd471365]
[pkrvmbietmlfzoi:12259] *** End of error message ***
</pre>
{% endraw %}
