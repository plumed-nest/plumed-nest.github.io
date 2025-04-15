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
[fv-az1047-397:65998] *** Process received signal ***
[fv-az1047-397:65998] Signal: Aborted (6)
[fv-az1047-397:65998] Signal code:  (-6)
[fv-az1047-397:65998] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa921a45330]
[fv-az1047-397:65998] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa921a9eb2c]
[fv-az1047-397:65998] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa921a4527e]
[fv-az1047-397:65998] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa921a288ff]
[fv-az1047-397:65998] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa921ea5ff5]
[fv-az1047-397:65998] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa921ebb0da]
[fv-az1047-397:65998] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa921ea5a55]
[fv-az1047-397:65998] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa921ea5a6f]
[fv-az1047-397:65998] [ 8] plumed(+0x146dd)[0x55bc659486dd]
[fv-az1047-397:65998] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa921a2a1ca]
[fv-az1047-397:65998] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa921a2a28b]
[fv-az1047-397:65998] [11] plumed(+0x15365)[0x55bc65949365]
[fv-az1047-397:65998] *** End of error message ***
</pre>
{% endraw %}
