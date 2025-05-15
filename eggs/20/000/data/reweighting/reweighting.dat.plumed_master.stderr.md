**Project ID:** [plumID:20.000]({{ '/' | absolute_url }}eggs/20/000/)  
Stderr for source:  reweighting/reweighting.dat   
Download: [zipped raw stdout](reweighting.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](reweighting.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @17 : keyword ARG is compulsory for this action
[pkrvmberfyhpb9w:10310] *** Process received signal ***
[pkrvmberfyhpb9w:10310] Signal: Aborted (6)
[pkrvmberfyhpb9w:10310] Signal code:  (-6)
[pkrvmberfyhpb9w:10310] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3128845330]
[pkrvmberfyhpb9w:10310] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f312889eb2c]
[pkrvmberfyhpb9w:10310] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f312884527e]
[pkrvmberfyhpb9w:10310] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f31288288ff]
[pkrvmberfyhpb9w:10310] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3128ca5ff5]
[pkrvmberfyhpb9w:10310] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3128cbb0da]
[pkrvmberfyhpb9w:10310] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3128ca5a55]
[pkrvmberfyhpb9w:10310] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3128ca5a6f]
[pkrvmberfyhpb9w:10310] [ 8] plumed_master(+0x146dd)[0x55c20f3c76dd]
[pkrvmberfyhpb9w:10310] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f312882a1ca]
[pkrvmberfyhpb9w:10310] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f312882a28b]
[pkrvmberfyhpb9w:10310] [11] plumed_master(+0x15365)[0x55c20f3c8365]
[pkrvmberfyhpb9w:10310] *** End of error message ***
</pre>
{% endraw %}
