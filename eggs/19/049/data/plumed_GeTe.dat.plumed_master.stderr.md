**Project ID:** [plumID:19.049]({{ '/' | absolute_url }}eggs/19/049/)  
Stderr for source:  plumed_GeTe.dat   
Download: [zipped raw stdout](plumed_GeTe.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_GeTe.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CONTACT_MATRIX_PROPER with label cc_cmat : it was not possible to interpret atom name flq6
[pkrvmberfyhpb9w:11060] *** Process received signal ***
[pkrvmberfyhpb9w:11060] Signal: Aborted (6)
[pkrvmberfyhpb9w:11060] Signal code:  (-6)
[pkrvmberfyhpb9w:11060] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc56ea45330]
[pkrvmberfyhpb9w:11060] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc56ea9eb2c]
[pkrvmberfyhpb9w:11060] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc56ea4527e]
[pkrvmberfyhpb9w:11060] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc56ea288ff]
[pkrvmberfyhpb9w:11060] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc56eea5ff5]
[pkrvmberfyhpb9w:11060] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc56eebb0da]
[pkrvmberfyhpb9w:11060] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc56eea5a55]
[pkrvmberfyhpb9w:11060] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc56eea5a6f]
[pkrvmberfyhpb9w:11060] [ 8] plumed_master(+0x146dd)[0x55a2f9b4f6dd]
[pkrvmberfyhpb9w:11060] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc56ea2a1ca]
[pkrvmberfyhpb9w:11060] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc56ea2a28b]
[pkrvmberfyhpb9w:11060] [11] plumed_master(+0x15365)[0x55a2f9b50365]
[pkrvmberfyhpb9w:11060] *** End of error message ***
</pre>
{% endraw %}
