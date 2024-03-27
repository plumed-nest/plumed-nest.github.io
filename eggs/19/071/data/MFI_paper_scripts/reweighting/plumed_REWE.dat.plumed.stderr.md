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
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action METAD with label metad : cannot understand the following words from the input line : REWEIGHTING_NGRID=200, REWEIGHTING_NHILLS=10
[fv-az1535-957:72358] *** Process received signal ***
[fv-az1535-957:72358] Signal: Aborted (6)
[fv-az1535-957:72358] Signal code:  (-6)
[fv-az1535-957:72358] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7ff5eb642520]
[fv-az1535-957:72358] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7ff5eb6969fc]
[fv-az1535-957:72358] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7ff5eb642476]
[fv-az1535-957:72358] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7ff5eb6287f3]
[fv-az1535-957:72358] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa4f26)[0x7ff5ebaa4f26]
[fv-az1535-957:72358] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6d9c)[0x7ff5ebab6d9c]
[fv-az1535-957:72358] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xb6e07)[0x7ff5ebab6e07]
[fv-az1535-957:72358] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7ff5ebab70bb]
[fv-az1535-957:72358] [ 8] plumed(+0x12f48)[0x555a6de51f48]
[fv-az1535-957:72358] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7ff5eb629d90]
[fv-az1535-957:72358] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7ff5eb629e40]
[fv-az1535-957:72358] [11] plumed(+0x131e5)[0x555a6de521e5]
[fv-az1535-957:72358] *** End of error message ***
</pre>
{% endraw %}
