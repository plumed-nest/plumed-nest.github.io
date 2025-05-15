**Project ID:** [plumID:24.008]({{ '/' | absolute_url }}eggs/24/008/)  
Stderr for source:  Reweighting/plumed_get_weights.dat   
Download: [zipped raw stdout](plumed_get_weights.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_get_weights.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label rho : could not find file named rtp_coord.dat
[pkrvmberfyhpb9w:06113] *** Process received signal ***
[pkrvmberfyhpb9w:06113] Signal: Aborted (6)
[pkrvmberfyhpb9w:06113] Signal code:  (-6)
[pkrvmberfyhpb9w:06113] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1d14e45330]
[pkrvmberfyhpb9w:06113] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1d14e9eb2c]
[pkrvmberfyhpb9w:06113] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1d14e4527e]
[pkrvmberfyhpb9w:06113] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1d14e288ff]
[pkrvmberfyhpb9w:06113] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1d152a5ff5]
[pkrvmberfyhpb9w:06113] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1d152bb0da]
[pkrvmberfyhpb9w:06113] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1d152a5a55]
[pkrvmberfyhpb9w:06113] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1d152a5a6f]
[pkrvmberfyhpb9w:06113] [ 8] plumed(+0x146dd)[0x55a5e339e6dd]
[pkrvmberfyhpb9w:06113] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1d14e2a1ca]
[pkrvmberfyhpb9w:06113] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1d14e2a28b]
[pkrvmberfyhpb9w:06113] [11] plumed(+0x15365)[0x55a5e339f365]
[pkrvmberfyhpb9w:06113] *** End of error message ***
</pre>
{% endraw %}
