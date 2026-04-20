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
[runnervmeorf1:12335] *** Process received signal ***
[runnervmeorf1:12335] Signal: Aborted (6)
[runnervmeorf1:12335] Signal code:  (-6)
[runnervmeorf1:12335] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f15e9645330]
[runnervmeorf1:12335] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f15e969eb2c]
[runnervmeorf1:12335] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f15e964527e]
[runnervmeorf1:12335] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f15e96288ff]
[runnervmeorf1:12335] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f15e9aa5ff5]
[runnervmeorf1:12335] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f15e9abb0da]
[runnervmeorf1:12335] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f15e9aa5a55]
[runnervmeorf1:12335] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f15e9aa5a6f]
[runnervmeorf1:12335] [ 8] plumed(+0x146dd)[0x5646138076dd]
[runnervmeorf1:12335] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f15e962a1ca]
[runnervmeorf1:12335] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f15e962a28b]
[runnervmeorf1:12335] [11] plumed(+0x15365)[0x564613808365]
[runnervmeorf1:12335] *** End of error message ***
</pre>
{% endraw %}
