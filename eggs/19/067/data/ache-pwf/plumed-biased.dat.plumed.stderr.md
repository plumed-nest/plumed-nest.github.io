**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pwf/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmberfyhpb9w:11915] *** Process received signal ***
[pkrvmberfyhpb9w:11915] Signal: Aborted (6)
[pkrvmberfyhpb9w:11915] Signal code:  (-6)
[pkrvmberfyhpb9w:11915] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7c5f645330]
[pkrvmberfyhpb9w:11915] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7c5f69eb2c]
[pkrvmberfyhpb9w:11915] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7c5f64527e]
[pkrvmberfyhpb9w:11915] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7c5f6288ff]
[pkrvmberfyhpb9w:11915] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7c5faa5ff5]
[pkrvmberfyhpb9w:11915] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7c5fabb0da]
[pkrvmberfyhpb9w:11915] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7c5faa5a55]
[pkrvmberfyhpb9w:11915] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7c5faa5a6f]
[pkrvmberfyhpb9w:11915] [ 8] plumed(+0x146dd)[0x55f37114b6dd]
[pkrvmberfyhpb9w:11915] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7c5f62a1ca]
[pkrvmberfyhpb9w:11915] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7c5f62a28b]
[pkrvmberfyhpb9w:11915] [11] plumed(+0x15365)[0x55f37114c365]
[pkrvmberfyhpb9w:11915] *** End of error message ***
</pre>
{% endraw %}
