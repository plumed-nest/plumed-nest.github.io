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
[pkrvmxyh4eaekms:13450] *** Process received signal ***
[pkrvmxyh4eaekms:13450] Signal: Aborted (6)
[pkrvmxyh4eaekms:13450] Signal code:  (-6)
[pkrvmxyh4eaekms:13450] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff139c45330]
[pkrvmxyh4eaekms:13450] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff139c9eb2c]
[pkrvmxyh4eaekms:13450] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff139c4527e]
[pkrvmxyh4eaekms:13450] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff139c288ff]
[pkrvmxyh4eaekms:13450] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff13a0a5ff5]
[pkrvmxyh4eaekms:13450] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff13a0bb0da]
[pkrvmxyh4eaekms:13450] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff13a0a5a55]
[pkrvmxyh4eaekms:13450] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff13a0a5a6f]
[pkrvmxyh4eaekms:13450] [ 8] plumed(+0x146dd)[0x55c92722c6dd]
[pkrvmxyh4eaekms:13450] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff139c2a1ca]
[pkrvmxyh4eaekms:13450] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff139c2a28b]
[pkrvmxyh4eaekms:13450] [11] plumed(+0x15365)[0x55c92722d365]
[pkrvmxyh4eaekms:13450] *** End of error message ***
</pre>
{% endraw %}
