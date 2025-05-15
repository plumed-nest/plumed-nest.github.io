**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[pkrvmberfyhpb9w:08090] *** Process received signal ***
[pkrvmberfyhpb9w:08090] Signal: Aborted (6)
[pkrvmberfyhpb9w:08090] Signal code:  (-6)
[pkrvmberfyhpb9w:08090] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6f0b645330]
[pkrvmberfyhpb9w:08090] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6f0b69eb2c]
[pkrvmberfyhpb9w:08090] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6f0b64527e]
[pkrvmberfyhpb9w:08090] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6f0b6288ff]
[pkrvmberfyhpb9w:08090] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6f0baa5ff5]
[pkrvmberfyhpb9w:08090] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6f0babb0da]
[pkrvmberfyhpb9w:08090] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6f0baa5a55]
[pkrvmberfyhpb9w:08090] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6f0baa5a6f]
[pkrvmberfyhpb9w:08090] [ 8] plumed(+0x146dd)[0x562c1f0616dd]
[pkrvmberfyhpb9w:08090] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6f0b62a1ca]
[pkrvmberfyhpb9w:08090] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6f0b62a28b]
[pkrvmberfyhpb9w:08090] [11] plumed(+0x15365)[0x562c1f062365]
[pkrvmberfyhpb9w:08090] *** End of error message ***
</pre>
{% endraw %}
