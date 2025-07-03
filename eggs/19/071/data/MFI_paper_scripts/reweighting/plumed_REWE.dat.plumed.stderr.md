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
[pkrvmbietmlfzoi:12386] *** Process received signal ***
[pkrvmbietmlfzoi:12386] Signal: Aborted (6)
[pkrvmbietmlfzoi:12386] Signal code:  (-6)
[pkrvmbietmlfzoi:12386] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1ada045330]
[pkrvmbietmlfzoi:12386] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1ada09eb2c]
[pkrvmbietmlfzoi:12386] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1ada04527e]
[pkrvmbietmlfzoi:12386] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1ada0288ff]
[pkrvmbietmlfzoi:12386] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1ada4a5ff5]
[pkrvmbietmlfzoi:12386] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1ada4bb0da]
[pkrvmbietmlfzoi:12386] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1ada4a5a55]
[pkrvmbietmlfzoi:12386] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1ada4a5a6f]
[pkrvmbietmlfzoi:12386] [ 8] plumed(+0x146dd)[0x5624fb7806dd]
[pkrvmbietmlfzoi:12386] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1ada02a1ca]
[pkrvmbietmlfzoi:12386] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1ada02a28b]
[pkrvmbietmlfzoi:12386] [11] plumed(+0x15365)[0x5624fb781365]
[pkrvmbietmlfzoi:12386] *** End of error message ***
</pre>
{% endraw %}
