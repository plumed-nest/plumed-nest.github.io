**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_REWE.dat   
Download: [zipped raw stdout](plumed_REWE.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_REWE.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : cannot understand the following words from the input line : REWEIGHTING_NGRID=200, REWEIGHTING_NHILLS=10
[pkrvmberfyhpb9w:12352] *** Process received signal ***
[pkrvmberfyhpb9w:12352] Signal: Aborted (6)
[pkrvmberfyhpb9w:12352] Signal code:  (-6)
[pkrvmberfyhpb9w:12352] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0f63045330]
[pkrvmberfyhpb9w:12352] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0f6309eb2c]
[pkrvmberfyhpb9w:12352] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0f6304527e]
[pkrvmberfyhpb9w:12352] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0f630288ff]
[pkrvmberfyhpb9w:12352] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0f634a5ff5]
[pkrvmberfyhpb9w:12352] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0f634bb0da]
[pkrvmberfyhpb9w:12352] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0f634a5a55]
[pkrvmberfyhpb9w:12352] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0f634a5a6f]
[pkrvmberfyhpb9w:12352] [ 8] plumed(+0x146dd)[0x562f31c296dd]
[pkrvmberfyhpb9w:12352] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0f6302a1ca]
[pkrvmberfyhpb9w:12352] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0f6302a28b]
[pkrvmberfyhpb9w:12352] [11] plumed(+0x15365)[0x562f31c2a365]
[pkrvmberfyhpb9w:12352] *** End of error message ***
</pre>
{% endraw %}
