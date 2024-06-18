**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:240) void PLMD::Action::error(const string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[fv-az883-206:05862] *** Process received signal ***
[fv-az883-206:05862] Signal: Aborted (6)
[fv-az883-206:05862] Signal code:  (-6)
[fv-az883-206:05862] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f6177c42520]
[fv-az883-206:05862] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f6177c969fc]
[fv-az883-206:05862] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f6177c42476]
[fv-az883-206:05862] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f6177c287f3]
[fv-az883-206:05862] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f61780a2b9e]
[fv-az883-206:05862] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f61780ae20c]
[fv-az883-206:05862] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f61780ae277]
[fv-az883-206:05862] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f61780ae52b]
[fv-az883-206:05862] [ 8] plumed(+0x12f48)[0x55e4d4724f48]
[fv-az883-206:05862] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f6177c29d90]
[fv-az883-206:05862] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f6177c29e40]
[fv-az883-206:05862] [11] plumed(+0x131e5)[0x55e4d47251e5]
[fv-az883-206:05862] *** End of error message ***
</pre>
{% endraw %}
