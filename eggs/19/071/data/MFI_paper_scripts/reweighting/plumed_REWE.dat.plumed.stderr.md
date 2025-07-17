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
[pkrvmq0rgcvqdmg:12289] *** Process received signal ***
[pkrvmq0rgcvqdmg:12289] Signal: Aborted (6)
[pkrvmq0rgcvqdmg:12289] Signal code:  (-6)
[pkrvmq0rgcvqdmg:12289] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f91f5045330]
[pkrvmq0rgcvqdmg:12289] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f91f509eb2c]
[pkrvmq0rgcvqdmg:12289] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f91f504527e]
[pkrvmq0rgcvqdmg:12289] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f91f50288ff]
[pkrvmq0rgcvqdmg:12289] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f91f54a5ff5]
[pkrvmq0rgcvqdmg:12289] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f91f54bb0da]
[pkrvmq0rgcvqdmg:12289] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f91f54a5a55]
[pkrvmq0rgcvqdmg:12289] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f91f54a5a6f]
[pkrvmq0rgcvqdmg:12289] [ 8] plumed(+0x146dd)[0x56201762d6dd]
[pkrvmq0rgcvqdmg:12289] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f91f502a1ca]
[pkrvmq0rgcvqdmg:12289] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f91f502a28b]
[pkrvmq0rgcvqdmg:12289] [11] plumed(+0x15365)[0x56201762e365]
[pkrvmq0rgcvqdmg:12289] *** End of error message ***
</pre>
{% endraw %}
