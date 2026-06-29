**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_REWE.dat   
Download: [zipped raw stdout](plumed_REWE.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_REWE.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:372) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : cannot understand the following words from the input line : REWEIGHTING_NGRID, REWEIGHTING_NHILLS
[runnervmmklqx:10096] *** Process received signal ***
[runnervmmklqx:10096] Signal: Aborted (6)
[runnervmmklqx:10096] Signal code:  (-6)
[runnervmmklqx:10096] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff18ae45330]
[runnervmmklqx:10096] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff18ae9eb2c]
[runnervmmklqx:10096] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff18ae4527e]
[runnervmmklqx:10096] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff18ae288ff]
[runnervmmklqx:10096] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff18b2a5ff5]
[runnervmmklqx:10096] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff18b2bb0da]
[runnervmmklqx:10096] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff18b2a5a55]
[runnervmmklqx:10096] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff18b2a5a6f]
[runnervmmklqx:10096] [ 8] plumed_master(+0x146dd)[0x555a056d06dd]
[runnervmmklqx:10096] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff18ae2a1ca]
[runnervmmklqx:10096] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff18ae2a28b]
[runnervmmklqx:10096] [11] plumed_master(+0x15365)[0x555a056d1365]
[runnervmmklqx:10096] *** End of error message ***
</pre>
{% endraw %}
