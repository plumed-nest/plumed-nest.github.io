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
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action METAD with label metad : cannot understand the following words from the input line : REWEIGHTING_NGRID=200, REWEIGHTING_NHILLS=10
[fv-az802-461:10796] *** Process received signal ***
[fv-az802-461:10796] Signal: Aborted (6)
[fv-az802-461:10796] Signal code:  (-6)
[fv-az802-461:10796] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7efc24042520]
[fv-az802-461:10796] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7efc240969fc]
[fv-az802-461:10796] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7efc24042476]
[fv-az802-461:10796] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7efc240287f3]
[fv-az802-461:10796] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7efc244a2b9e]
[fv-az802-461:10796] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7efc244ae20c]
[fv-az802-461:10796] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7efc244ae277]
[fv-az802-461:10796] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7efc244ae52b]
[fv-az802-461:10796] [ 8] plumed_master(+0x14254)[0x5599b6a84254]
[fv-az802-461:10796] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7efc24029d90]
[fv-az802-461:10796] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7efc24029e40]
[fv-az802-461:10796] [11] plumed_master(+0x14eb5)[0x5599b6a84eb5]
[fv-az802-461:10796] *** End of error message ***
</pre>
{% endraw %}
