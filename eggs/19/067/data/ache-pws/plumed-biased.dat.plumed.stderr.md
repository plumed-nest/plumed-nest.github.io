**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmberfyhpb9w:11994] *** Process received signal ***
[pkrvmberfyhpb9w:11994] Signal: Aborted (6)
[pkrvmberfyhpb9w:11994] Signal code:  (-6)
[pkrvmberfyhpb9w:11994] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f053d845330]
[pkrvmberfyhpb9w:11994] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f053d89eb2c]
[pkrvmberfyhpb9w:11994] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f053d84527e]
[pkrvmberfyhpb9w:11994] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f053d8288ff]
[pkrvmberfyhpb9w:11994] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f053dca5ff5]
[pkrvmberfyhpb9w:11994] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f053dcbb0da]
[pkrvmberfyhpb9w:11994] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f053dca5a55]
[pkrvmberfyhpb9w:11994] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f053dca5a6f]
[pkrvmberfyhpb9w:11994] [ 8] plumed(+0x146dd)[0x556358eac6dd]
[pkrvmberfyhpb9w:11994] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f053d82a1ca]
[pkrvmberfyhpb9w:11994] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f053d82a28b]
[pkrvmberfyhpb9w:11994] [11] plumed(+0x15365)[0x556358ead365]
[pkrvmberfyhpb9w:11994] *** End of error message ***
</pre>
{% endraw %}
