**Project ID:** [plumID:21.013]({{ '/' | absolute_url }}eggs/21/013/)  
Stderr for source:  h2-base/sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @29 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:11916] *** Process received signal ***
[pkrvmberfyhpb9w:11916] Signal: Aborted (6)
[pkrvmberfyhpb9w:11916] Signal code:  (-6)
[pkrvmberfyhpb9w:11916] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fba3aa45330]
[pkrvmberfyhpb9w:11916] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fba3aa9eb2c]
[pkrvmberfyhpb9w:11916] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fba3aa4527e]
[pkrvmberfyhpb9w:11916] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fba3aa288ff]
[pkrvmberfyhpb9w:11916] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fba3aea5ff5]
[pkrvmberfyhpb9w:11916] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fba3aebb0da]
[pkrvmberfyhpb9w:11916] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fba3aea5a55]
[pkrvmberfyhpb9w:11916] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fba3aea5a6f]
[pkrvmberfyhpb9w:11916] [ 8] plumed_master(+0x146dd)[0x5629ad4fa6dd]
[pkrvmberfyhpb9w:11916] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fba3aa2a1ca]
[pkrvmberfyhpb9w:11916] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fba3aa2a28b]
[pkrvmberfyhpb9w:11916] [11] plumed_master(+0x15365)[0x5629ad4fb365]
[pkrvmberfyhpb9w:11916] *** End of error message ***
</pre>
{% endraw %}
