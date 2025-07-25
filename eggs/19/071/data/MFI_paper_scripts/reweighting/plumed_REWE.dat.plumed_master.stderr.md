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
[pkrvmpptgkbjq6m:10810] *** Process received signal ***
[pkrvmpptgkbjq6m:10810] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10810] Signal code:  (-6)
[pkrvmpptgkbjq6m:10810] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f76a5845330]
[pkrvmpptgkbjq6m:10810] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f76a589eb2c]
[pkrvmpptgkbjq6m:10810] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f76a584527e]
[pkrvmpptgkbjq6m:10810] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f76a58288ff]
[pkrvmpptgkbjq6m:10810] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f76a5ca5ff5]
[pkrvmpptgkbjq6m:10810] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f76a5cbb0da]
[pkrvmpptgkbjq6m:10810] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f76a5ca5a55]
[pkrvmpptgkbjq6m:10810] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f76a5ca5a6f]
[pkrvmpptgkbjq6m:10810] [ 8] plumed_master(+0x146dd)[0x562a58d4b6dd]
[pkrvmpptgkbjq6m:10810] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f76a582a1ca]
[pkrvmpptgkbjq6m:10810] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f76a582a28b]
[pkrvmpptgkbjq6m:10810] [11] plumed_master(+0x15365)[0x562a58d4c365]
[pkrvmpptgkbjq6m:10810] *** End of error message ***
</pre>
{% endraw %}
