**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @52 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:10750] *** Process received signal ***
[pkrvmberfyhpb9w:10750] Signal: Aborted (6)
[pkrvmberfyhpb9w:10750] Signal code:  (-6)
[pkrvmberfyhpb9w:10750] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3548645330]
[pkrvmberfyhpb9w:10750] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f354869eb2c]
[pkrvmberfyhpb9w:10750] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f354864527e]
[pkrvmberfyhpb9w:10750] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f35486288ff]
[pkrvmberfyhpb9w:10750] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3548aa5ff5]
[pkrvmberfyhpb9w:10750] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3548abb0da]
[pkrvmberfyhpb9w:10750] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3548aa5a55]
[pkrvmberfyhpb9w:10750] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3548aa5a6f]
[pkrvmberfyhpb9w:10750] [ 8] plumed_master(+0x146dd)[0x55c3bc19e6dd]
[pkrvmberfyhpb9w:10750] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f354862a1ca]
[pkrvmberfyhpb9w:10750] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f354862a28b]
[pkrvmberfyhpb9w:10750] [11] plumed_master(+0x15365)[0x55c3bc19f365]
[pkrvmberfyhpb9w:10750] *** End of error message ***
</pre>
{% endraw %}
