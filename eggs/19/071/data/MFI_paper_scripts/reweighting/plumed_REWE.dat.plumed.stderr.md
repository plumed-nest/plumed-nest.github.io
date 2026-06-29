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
[runnervmmklqx:10080] *** Process received signal ***
[runnervmmklqx:10080] Signal: Aborted (6)
[runnervmmklqx:10080] Signal code:  (-6)
[runnervmmklqx:10080] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fca00e45330]
[runnervmmklqx:10080] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fca00e9eb2c]
[runnervmmklqx:10080] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fca00e4527e]
[runnervmmklqx:10080] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fca00e288ff]
[runnervmmklqx:10080] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fca012a5ff5]
[runnervmmklqx:10080] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fca012bb0da]
[runnervmmklqx:10080] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fca012a5a55]
[runnervmmklqx:10080] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fca012a5a6f]
[runnervmmklqx:10080] [ 8] plumed(+0x146dd)[0x5650940346dd]
[runnervmmklqx:10080] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fca00e2a1ca]
[runnervmmklqx:10080] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fca00e2a28b]
[runnervmmklqx:10080] [11] plumed(+0x15365)[0x565094035365]
[runnervmmklqx:10080] *** End of error message ***
</pre>
{% endraw %}
