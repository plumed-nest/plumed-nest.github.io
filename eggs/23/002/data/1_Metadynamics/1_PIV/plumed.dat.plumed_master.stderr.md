**Project ID:** [plumID:23.002]({{ '/' | absolute_url }}eggs/23/002/)  
Stderr for source:  1_Metadynamics/1_PIV/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action PAIRENTROPY with label @s13 : keyword GRID_BIN is compulsory for this action
[pkrvmberfyhpb9w:07500] *** Process received signal ***
[pkrvmberfyhpb9w:07500] Signal: Aborted (6)
[pkrvmberfyhpb9w:07500] Signal code:  (-6)
[pkrvmberfyhpb9w:07500] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f166da45330]
[pkrvmberfyhpb9w:07500] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f166da9eb2c]
[pkrvmberfyhpb9w:07500] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f166da4527e]
[pkrvmberfyhpb9w:07500] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f166da288ff]
[pkrvmberfyhpb9w:07500] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f166dea5ff5]
[pkrvmberfyhpb9w:07500] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f166debb0da]
[pkrvmberfyhpb9w:07500] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f166dea5a55]
[pkrvmberfyhpb9w:07500] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f166dea5a6f]
[pkrvmberfyhpb9w:07500] [ 8] plumed_master(+0x146dd)[0x564109a146dd]
[pkrvmberfyhpb9w:07500] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f166da2a1ca]
[pkrvmberfyhpb9w:07500] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f166da2a28b]
[pkrvmberfyhpb9w:07500] [11] plumed_master(+0x15365)[0x564109a15365]
[pkrvmberfyhpb9w:07500] *** End of error message ***
</pre>
{% endraw %}
