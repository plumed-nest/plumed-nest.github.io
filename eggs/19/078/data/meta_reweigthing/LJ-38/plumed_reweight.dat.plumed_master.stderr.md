**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/LJ-38/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COLLECT with label cc_ns : missing TYPE keyword.  TYPE should specify whether data is to be stored as a vector or a matrix
[pkrvmberfyhpb9w:11894] *** Process received signal ***
[pkrvmberfyhpb9w:11894] Signal: Aborted (6)
[pkrvmberfyhpb9w:11894] Signal code:  (-6)
[pkrvmberfyhpb9w:11894] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4590a45330]
[pkrvmberfyhpb9w:11894] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4590a9eb2c]
[pkrvmberfyhpb9w:11894] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4590a4527e]
[pkrvmberfyhpb9w:11894] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4590a288ff]
[pkrvmberfyhpb9w:11894] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4590ea5ff5]
[pkrvmberfyhpb9w:11894] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4590ebb0da]
[pkrvmberfyhpb9w:11894] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4590ea5a55]
[pkrvmberfyhpb9w:11894] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4590ea5a6f]
[pkrvmberfyhpb9w:11894] [ 8] plumed_master(+0x146dd)[0x55d33c43b6dd]
[pkrvmberfyhpb9w:11894] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4590a2a1ca]
[pkrvmberfyhpb9w:11894] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4590a2a28b]
[pkrvmberfyhpb9w:11894] [11] plumed_master(+0x15365)[0x55d33c43c365]
[pkrvmberfyhpb9w:11894] *** End of error message ***
</pre>
{% endraw %}
