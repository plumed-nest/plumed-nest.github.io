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
[fv-az1720-841:10882] *** Process received signal ***
[fv-az1720-841:10882] Signal: Aborted (6)
[fv-az1720-841:10882] Signal code:  (-6)
[fv-az1720-841:10882] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc85a045330]
[fv-az1720-841:10882] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc85a09eb2c]
[fv-az1720-841:10882] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc85a04527e]
[fv-az1720-841:10882] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc85a0288ff]
[fv-az1720-841:10882] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc85a4a5ff5]
[fv-az1720-841:10882] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc85a4bb0da]
[fv-az1720-841:10882] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc85a4a5a55]
[fv-az1720-841:10882] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc85a4a5a6f]
[fv-az1720-841:10882] [ 8] plumed(+0x146dd)[0x55ccd02e46dd]
[fv-az1720-841:10882] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc85a02a1ca]
[fv-az1720-841:10882] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc85a02a28b]
[fv-az1720-841:10882] [11] plumed(+0x15365)[0x55ccd02e5365]
[fv-az1720-841:10882] *** End of error message ***
</pre>
{% endraw %}
