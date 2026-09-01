**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_REWE.dat   
Download: [zipped raw stdout](plumed_REWE.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_REWE.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : cannot understand the following words from the input line : REWEIGHTING_NGRID=200, REWEIGHTING_NHILLS=10
[runnervmgx7h7:10890] *** Process received signal ***
[runnervmgx7h7:10890] Signal: Aborted (6)
[runnervmgx7h7:10890] Signal code:  (-6)
[runnervmgx7h7:10890] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb063245330]
[runnervmgx7h7:10890] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb06329ec0c]
[runnervmgx7h7:10890] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb06324527e]
[runnervmgx7h7:10890] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb0632288ff]
[runnervmgx7h7:10890] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb0636a5ff5]
[runnervmgx7h7:10890] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb0636bb0da]
[runnervmgx7h7:10890] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb0636a5a55]
[runnervmgx7h7:10890] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb0636a5a6f]
[runnervmgx7h7:10890] [ 8] plumed(+0x146dd)[0x5617d0cde6dd]
[runnervmgx7h7:10890] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb06322a1ca]
[runnervmgx7h7:10890] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb06322a28b]
[runnervmgx7h7:10890] [11] plumed(+0x15365)[0x5617d0cdf365]
[runnervmgx7h7:10890] *** End of error message ***
</pre>
{% endraw %}
