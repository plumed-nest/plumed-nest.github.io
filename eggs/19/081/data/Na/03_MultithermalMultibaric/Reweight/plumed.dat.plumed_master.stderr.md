**Project ID:** [plumID:19.081]({{ '/' | absolute_url }}eggs/19/081/)  
Stderr for source:  Na/03_MultithermalMultibaric/Reweight/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @40 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:12360] *** Process received signal ***
[pkrvmberfyhpb9w:12360] Signal: Aborted (6)
[pkrvmberfyhpb9w:12360] Signal code:  (-6)
[pkrvmberfyhpb9w:12360] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f200f645330]
[pkrvmberfyhpb9w:12360] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f200f69eb2c]
[pkrvmberfyhpb9w:12360] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f200f64527e]
[pkrvmberfyhpb9w:12360] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f200f6288ff]
[pkrvmberfyhpb9w:12360] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f200faa5ff5]
[pkrvmberfyhpb9w:12360] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f200fabb0da]
[pkrvmberfyhpb9w:12360] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f200faa5a55]
[pkrvmberfyhpb9w:12360] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f200faa5a6f]
[pkrvmberfyhpb9w:12360] [ 8] plumed_master(+0x146dd)[0x5612f65e46dd]
[pkrvmberfyhpb9w:12360] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f200f62a1ca]
[pkrvmberfyhpb9w:12360] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f200f62a28b]
[pkrvmberfyhpb9w:12360] [11] plumed_master(+0x15365)[0x5612f65e5365]
[pkrvmberfyhpb9w:12360] *** End of error message ***
</pre>
{% endraw %}
