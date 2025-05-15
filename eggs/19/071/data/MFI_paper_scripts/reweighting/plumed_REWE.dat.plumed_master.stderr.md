**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_REWE.dat   
Download: [zipped raw stdout](plumed_REWE.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_REWE.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : cannot understand the following words from the input line : REWEIGHTING_NGRID=200, REWEIGHTING_NHILLS=10
[pkrvmberfyhpb9w:12367] *** Process received signal ***
[pkrvmberfyhpb9w:12367] Signal: Aborted (6)
[pkrvmberfyhpb9w:12367] Signal code:  (-6)
[pkrvmberfyhpb9w:12367] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f33a6245330]
[pkrvmberfyhpb9w:12367] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f33a629eb2c]
[pkrvmberfyhpb9w:12367] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f33a624527e]
[pkrvmberfyhpb9w:12367] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f33a62288ff]
[pkrvmberfyhpb9w:12367] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f33a66a5ff5]
[pkrvmberfyhpb9w:12367] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f33a66bb0da]
[pkrvmberfyhpb9w:12367] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f33a66a5a55]
[pkrvmberfyhpb9w:12367] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f33a66a5a6f]
[pkrvmberfyhpb9w:12367] [ 8] plumed_master(+0x146dd)[0x5638316516dd]
[pkrvmberfyhpb9w:12367] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f33a622a1ca]
[pkrvmberfyhpb9w:12367] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f33a622a28b]
[pkrvmberfyhpb9w:12367] [11] plumed_master(+0x15365)[0x563831652365]
[pkrvmberfyhpb9w:12367] *** End of error message ***
</pre>
{% endraw %}
