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
[pkrvmbietmlfzoi:65675] *** Process received signal ***
[pkrvmbietmlfzoi:65675] Signal: Aborted (6)
[pkrvmbietmlfzoi:65675] Signal code:  (-6)
[pkrvmbietmlfzoi:65675] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8d31645330]
[pkrvmbietmlfzoi:65675] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8d3169eb2c]
[pkrvmbietmlfzoi:65675] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8d3164527e]
[pkrvmbietmlfzoi:65675] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8d316288ff]
[pkrvmbietmlfzoi:65675] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8d31aa5ff5]
[pkrvmbietmlfzoi:65675] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8d31abb0da]
[pkrvmbietmlfzoi:65675] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8d31aa5a55]
[pkrvmbietmlfzoi:65675] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8d31aa5a6f]
[pkrvmbietmlfzoi:65675] [ 8] plumed_master(+0x146dd)[0x55e4597596dd]
[pkrvmbietmlfzoi:65675] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8d3162a1ca]
[pkrvmbietmlfzoi:65675] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8d3162a28b]
[pkrvmbietmlfzoi:65675] [11] plumed_master(+0x15365)[0x55e45975a365]
[pkrvmbietmlfzoi:65675] *** End of error message ***
</pre>
{% endraw %}
