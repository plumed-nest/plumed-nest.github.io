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
[fv-az1267-279:66831] *** Process received signal ***
[fv-az1267-279:66831] Signal: Aborted (6)
[fv-az1267-279:66831] Signal code:  (-6)
[fv-az1267-279:66831] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2ef5245330]
[fv-az1267-279:66831] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2ef529eb2c]
[fv-az1267-279:66831] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2ef524527e]
[fv-az1267-279:66831] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2ef52288ff]
[fv-az1267-279:66831] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2ef56a5ff5]
[fv-az1267-279:66831] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2ef56bb0da]
[fv-az1267-279:66831] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2ef56a5a55]
[fv-az1267-279:66831] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2ef56a5a6f]
[fv-az1267-279:66831] [ 8] plumed(+0x146dd)[0x55c3c463b6dd]
[fv-az1267-279:66831] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2ef522a1ca]
[fv-az1267-279:66831] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2ef522a28b]
[fv-az1267-279:66831] [11] plumed(+0x15365)[0x55c3c463c365]
[fv-az1267-279:66831] *** End of error message ***
</pre>
{% endraw %}
