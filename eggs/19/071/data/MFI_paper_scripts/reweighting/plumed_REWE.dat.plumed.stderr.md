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
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action METAD with label metad : cannot understand the following words from the input line : REWEIGHTING_NGRID=200, REWEIGHTING_NHILLS=10
[fv-az802-461:10788] *** Process received signal ***
[fv-az802-461:10788] Signal: Aborted (6)
[fv-az802-461:10788] Signal code:  (-6)
[fv-az802-461:10788] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7fcf17642520]
[fv-az802-461:10788] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7fcf176969fc]
[fv-az802-461:10788] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7fcf17642476]
[fv-az802-461:10788] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7fcf176287f3]
[fv-az802-461:10788] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7fcf17aa2b9e]
[fv-az802-461:10788] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7fcf17aae20c]
[fv-az802-461:10788] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7fcf17aae277]
[fv-az802-461:10788] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7fcf17aae52b]
[fv-az802-461:10788] [ 8] plumed(+0x14254)[0x55a9dcf7e254]
[fv-az802-461:10788] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7fcf17629d90]
[fv-az802-461:10788] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7fcf17629e40]
[fv-az802-461:10788] [11] plumed(+0x14eb5)[0x55a9dcf7eeb5]
[fv-az802-461:10788] *** End of error message ***
</pre>
{% endraw %}
