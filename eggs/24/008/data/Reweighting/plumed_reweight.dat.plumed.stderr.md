**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[pkrvmberfyhpb9w:06167] *** Process received signal ***
[pkrvmberfyhpb9w:06167] Signal: Aborted (6)
[pkrvmberfyhpb9w:06167] Signal code:  (-6)
[pkrvmberfyhpb9w:06167] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4b52c45330]
[pkrvmberfyhpb9w:06167] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4b52c9eb2c]
[pkrvmberfyhpb9w:06167] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4b52c4527e]
[pkrvmberfyhpb9w:06167] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4b52c288ff]
[pkrvmberfyhpb9w:06167] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4b530a5ff5]
[pkrvmberfyhpb9w:06167] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4b530bb0da]
[pkrvmberfyhpb9w:06167] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4b530a5a55]
[pkrvmberfyhpb9w:06167] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4b530a5a6f]
[pkrvmberfyhpb9w:06167] [ 8] plumed(+0x146dd)[0x55fb4c0c36dd]
[pkrvmberfyhpb9w:06167] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4b52c2a1ca]
[pkrvmberfyhpb9w:06167] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4b52c2a28b]
[pkrvmberfyhpb9w:06167] [11] plumed(+0x15365)[0x55fb4c0c4365]
[pkrvmberfyhpb9w:06167] *** End of error message ***
</pre>
{% endraw %}
