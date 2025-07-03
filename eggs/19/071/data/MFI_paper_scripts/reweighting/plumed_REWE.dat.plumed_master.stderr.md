**Project ID:** [plumID:19.071]({{ '/' | absolute_url }}eggs/19/071/)  
Stderr for source:  MFI_paper_scripts/reweighting/plumed_REWE.dat   
Download: [zipped raw stdout](plumed_REWE.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_REWE.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : cannot understand the following words from the input line : REWEIGHTING_NGRID=200, REWEIGHTING_NHILLS=10
[pkrvmbietmlfzoi:12402] *** Process received signal ***
[pkrvmbietmlfzoi:12402] Signal: Aborted (6)
[pkrvmbietmlfzoi:12402] Signal code:  (-6)
[pkrvmbietmlfzoi:12402] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f30cea45330]
[pkrvmbietmlfzoi:12402] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f30cea9eb2c]
[pkrvmbietmlfzoi:12402] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f30cea4527e]
[pkrvmbietmlfzoi:12402] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f30cea288ff]
[pkrvmbietmlfzoi:12402] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f30ceea5ff5]
[pkrvmbietmlfzoi:12402] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f30ceebb0da]
[pkrvmbietmlfzoi:12402] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f30ceea5a55]
[pkrvmbietmlfzoi:12402] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f30ceea5a6f]
[pkrvmbietmlfzoi:12402] [ 8] plumed_master(+0x146dd)[0x558a920d36dd]
[pkrvmbietmlfzoi:12402] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f30cea2a1ca]
[pkrvmbietmlfzoi:12402] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f30cea2a28b]
[pkrvmbietmlfzoi:12402] [11] plumed_master(+0x15365)[0x558a920d4365]
[pkrvmbietmlfzoi:12402] *** End of error message ***
</pre>
{% endraw %}
