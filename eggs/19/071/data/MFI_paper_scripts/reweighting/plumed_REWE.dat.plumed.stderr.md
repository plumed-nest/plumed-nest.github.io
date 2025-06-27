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
[pkrvmbietmlfzoi:65660] *** Process received signal ***
[pkrvmbietmlfzoi:65660] Signal: Aborted (6)
[pkrvmbietmlfzoi:65660] Signal code:  (-6)
[pkrvmbietmlfzoi:65660] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9b95e45330]
[pkrvmbietmlfzoi:65660] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9b95e9eb2c]
[pkrvmbietmlfzoi:65660] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9b95e4527e]
[pkrvmbietmlfzoi:65660] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9b95e288ff]
[pkrvmbietmlfzoi:65660] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9b962a5ff5]
[pkrvmbietmlfzoi:65660] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9b962bb0da]
[pkrvmbietmlfzoi:65660] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9b962a5a55]
[pkrvmbietmlfzoi:65660] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9b962a5a6f]
[pkrvmbietmlfzoi:65660] [ 8] plumed(+0x146dd)[0x56174cbec6dd]
[pkrvmbietmlfzoi:65660] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9b95e2a1ca]
[pkrvmbietmlfzoi:65660] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9b95e2a28b]
[pkrvmbietmlfzoi:65660] [11] plumed(+0x15365)[0x56174cbed365]
[pkrvmbietmlfzoi:65660] *** End of error message ***
</pre>
{% endraw %}
