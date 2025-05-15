**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT_A399V/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @35 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:06041] *** Process received signal ***
[pkrvmberfyhpb9w:06041] Signal: Aborted (6)
[pkrvmberfyhpb9w:06041] Signal code:  (-6)
[pkrvmberfyhpb9w:06041] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff695645330]
[pkrvmberfyhpb9w:06041] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff69569eb2c]
[pkrvmberfyhpb9w:06041] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff69564527e]
[pkrvmberfyhpb9w:06041] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff6956288ff]
[pkrvmberfyhpb9w:06041] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff695aa5ff5]
[pkrvmberfyhpb9w:06041] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff695abb0da]
[pkrvmberfyhpb9w:06041] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff695aa5a55]
[pkrvmberfyhpb9w:06041] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff695aa5a6f]
[pkrvmberfyhpb9w:06041] [ 8] plumed_master(+0x146dd)[0x55c0309236dd]
[pkrvmberfyhpb9w:06041] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff69562a1ca]
[pkrvmberfyhpb9w:06041] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff69562a28b]
[pkrvmberfyhpb9w:06041] [11] plumed_master(+0x15365)[0x55c030924365]
[pkrvmberfyhpb9w:06041] *** End of error message ***
</pre>
{% endraw %}
