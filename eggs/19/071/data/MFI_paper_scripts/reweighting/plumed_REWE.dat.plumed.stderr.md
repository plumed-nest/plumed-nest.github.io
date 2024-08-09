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
[fv-az1567-223:09613] *** Process received signal ***
[fv-az1567-223:09613] Signal: Aborted (6)
[fv-az1567-223:09613] Signal code:  (-6)
[fv-az1567-223:09613] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f5f18842520]
[fv-az1567-223:09613] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f5f188969fc]
[fv-az1567-223:09613] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f5f18842476]
[fv-az1567-223:09613] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f5f188287f3]
[fv-az1567-223:09613] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f5f18ca2b9e]
[fv-az1567-223:09613] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f5f18cae20c]
[fv-az1567-223:09613] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f5f18cae277]
[fv-az1567-223:09613] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f5f18cae52b]
[fv-az1567-223:09613] [ 8] plumed(+0x12f48)[0x561b34981f48]
[fv-az1567-223:09613] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f5f18829d90]
[fv-az1567-223:09613] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f5f18829e40]
[fv-az1567-223:09613] [11] plumed(+0x131e5)[0x561b349821e5]
[fv-az1567-223:09613] *** End of error message ***
</pre>
{% endraw %}
