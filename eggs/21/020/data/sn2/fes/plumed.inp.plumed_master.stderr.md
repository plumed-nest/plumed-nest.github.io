**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  sn2/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @44 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:10686] *** Process received signal ***
[pkrvmberfyhpb9w:10686] Signal: Aborted (6)
[pkrvmberfyhpb9w:10686] Signal code:  (-6)
[pkrvmberfyhpb9w:10686] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3b07845330]
[pkrvmberfyhpb9w:10686] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3b0789eb2c]
[pkrvmberfyhpb9w:10686] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3b0784527e]
[pkrvmberfyhpb9w:10686] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3b078288ff]
[pkrvmberfyhpb9w:10686] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3b07ca5ff5]
[pkrvmberfyhpb9w:10686] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3b07cbb0da]
[pkrvmberfyhpb9w:10686] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3b07ca5a55]
[pkrvmberfyhpb9w:10686] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3b07ca5a6f]
[pkrvmberfyhpb9w:10686] [ 8] plumed_master(+0x146dd)[0x5649a7d556dd]
[pkrvmberfyhpb9w:10686] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3b0782a1ca]
[pkrvmberfyhpb9w:10686] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3b0782a28b]
[pkrvmberfyhpb9w:10686] [11] plumed_master(+0x15365)[0x5649a7d56365]
[pkrvmberfyhpb9w:10686] *** End of error message ***
</pre>
{% endraw %}
