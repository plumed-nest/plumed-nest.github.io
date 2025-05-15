**Project ID:** [plumID:19.032]({{ '/' | absolute_url }}eggs/19/032/)  
Stderr for source:  plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PDB2CONSTANT with label @s95 : argument O1O_lessthan was not set in pdb input
[pkrvmberfyhpb9w:12649] *** Process received signal ***
[pkrvmberfyhpb9w:12649] Signal: Aborted (6)
[pkrvmberfyhpb9w:12649] Signal code:  (-6)
[pkrvmberfyhpb9w:12649] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe320a45330]
[pkrvmberfyhpb9w:12649] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe320a9eb2c]
[pkrvmberfyhpb9w:12649] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe320a4527e]
[pkrvmberfyhpb9w:12649] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe320a288ff]
[pkrvmberfyhpb9w:12649] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe320ea5ff5]
[pkrvmberfyhpb9w:12649] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe320ebb0da]
[pkrvmberfyhpb9w:12649] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe320ea5a55]
[pkrvmberfyhpb9w:12649] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe320ea5a6f]
[pkrvmberfyhpb9w:12649] [ 8] plumed_master(+0x146dd)[0x55eef0b476dd]
[pkrvmberfyhpb9w:12649] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe320a2a1ca]
[pkrvmberfyhpb9w:12649] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe320a2a28b]
[pkrvmberfyhpb9w:12649] [11] plumed_master(+0x15365)[0x55eef0b48365]
[pkrvmberfyhpb9w:12649] *** End of error message ***
</pre>
{% endraw %}
