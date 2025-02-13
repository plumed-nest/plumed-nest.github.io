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
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : cannot understand the following words from the input line : REWEIGHTING_NGRID=200, REWEIGHTING_NHILLS=10
[fv-az2035-366:12031] *** Process received signal ***
[fv-az2035-366:12031] Signal: Aborted (6)
[fv-az2035-366:12031] Signal code:  (-6)
[fv-az2035-366:12031] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f85df845330]
[fv-az2035-366:12031] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f85df89eb2c]
[fv-az2035-366:12031] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f85df84527e]
[fv-az2035-366:12031] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f85df8288ff]
[fv-az2035-366:12031] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f85dfca5ff5]
[fv-az2035-366:12031] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f85dfcbb0da]
[fv-az2035-366:12031] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f85dfca5a55]
[fv-az2035-366:12031] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f85dfca5a6f]
[fv-az2035-366:12031] [ 8] plumed(+0x146dd)[0x55b1826b26dd]
[fv-az2035-366:12031] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f85df82a1ca]
[fv-az2035-366:12031] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f85df82a28b]
[fv-az2035-366:12031] [11] plumed(+0x15365)[0x55b1826b3365]
[fv-az2035-366:12031] *** End of error message ***
</pre>
{% endraw %}
