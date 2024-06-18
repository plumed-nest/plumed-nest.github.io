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
[fv-az1215-453:09016] *** Process received signal ***
[fv-az1215-453:09016] Signal: Aborted (6)
[fv-az1215-453:09016] Signal code:  (-6)
[fv-az1215-453:09016] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7ff6fa042520]
[fv-az1215-453:09016] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7ff6fa0969fc]
[fv-az1215-453:09016] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7ff6fa042476]
[fv-az1215-453:09016] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7ff6fa0287f3]
[fv-az1215-453:09016] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7ff6fa4a2b9e]
[fv-az1215-453:09016] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7ff6fa4ae20c]
[fv-az1215-453:09016] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7ff6fa4ae277]
[fv-az1215-453:09016] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7ff6fa4ae52b]
[fv-az1215-453:09016] [ 8] plumed(+0x12f48)[0x558706028f48]
[fv-az1215-453:09016] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7ff6fa029d90]
[fv-az1215-453:09016] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7ff6fa029e40]
[fv-az1215-453:09016] [11] plumed(+0x131e5)[0x5587060291e5]
[fv-az1215-453:09016] *** End of error message ***
</pre>
{% endraw %}
