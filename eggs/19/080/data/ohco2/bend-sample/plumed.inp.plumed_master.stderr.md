**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  ohco2/bend-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @33 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:12751] *** Process received signal ***
[pkrvmberfyhpb9w:12751] Signal: Aborted (6)
[pkrvmberfyhpb9w:12751] Signal code:  (-6)
[pkrvmberfyhpb9w:12751] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff3f8245330]
[pkrvmberfyhpb9w:12751] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff3f829eb2c]
[pkrvmberfyhpb9w:12751] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff3f824527e]
[pkrvmberfyhpb9w:12751] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff3f82288ff]
[pkrvmberfyhpb9w:12751] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff3f86a5ff5]
[pkrvmberfyhpb9w:12751] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff3f86bb0da]
[pkrvmberfyhpb9w:12751] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff3f86a5a55]
[pkrvmberfyhpb9w:12751] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff3f86a5a6f]
[pkrvmberfyhpb9w:12751] [ 8] plumed_master(+0x146dd)[0x55ba723d36dd]
[pkrvmberfyhpb9w:12751] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff3f822a1ca]
[pkrvmberfyhpb9w:12751] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff3f822a28b]
[pkrvmberfyhpb9w:12751] [11] plumed_master(+0x15365)[0x55ba723d4365]
[pkrvmberfyhpb9w:12751] *** End of error message ***
</pre>
{% endraw %}
