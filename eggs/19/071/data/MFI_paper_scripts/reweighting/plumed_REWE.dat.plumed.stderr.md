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
[fv-az1719-476:13155] *** Process received signal ***
[fv-az1719-476:13155] Signal: Aborted (6)
[fv-az1719-476:13155] Signal code:  (-6)
[fv-az1719-476:13155] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4316845330]
[fv-az1719-476:13155] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f431689eb2c]
[fv-az1719-476:13155] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f431684527e]
[fv-az1719-476:13155] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f43168288ff]
[fv-az1719-476:13155] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4316ca5ff5]
[fv-az1719-476:13155] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4316cbb0da]
[fv-az1719-476:13155] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4316ca5a55]
[fv-az1719-476:13155] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4316ca5a6f]
[fv-az1719-476:13155] [ 8] plumed(+0x146dd)[0x55ac43cc16dd]
[fv-az1719-476:13155] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f431682a1ca]
[fv-az1719-476:13155] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f431682a28b]
[fv-az1719-476:13155] [11] plumed(+0x15365)[0x55ac43cc2365]
[fv-az1719-476:13155] *** End of error message ***
</pre>
{% endraw %}
