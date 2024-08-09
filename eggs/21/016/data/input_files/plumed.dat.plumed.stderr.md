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
[fv-az1269-668:05821] *** Process received signal ***
[fv-az1269-668:05821] Signal: Aborted (6)
[fv-az1269-668:05821] Signal code:  (-6)
[fv-az1269-668:05821] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f40fda42520]
[fv-az1269-668:05821] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f40fda969fc]
[fv-az1269-668:05821] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f40fda42476]
[fv-az1269-668:05821] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f40fda287f3]
[fv-az1269-668:05821] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f40fdea2b9e]
[fv-az1269-668:05821] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f40fdeae20c]
[fv-az1269-668:05821] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f40fdeae277]
[fv-az1269-668:05821] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f40fdeae52b]
[fv-az1269-668:05821] [ 8] plumed(+0x12f48)[0x55a799187f48]
[fv-az1269-668:05821] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f40fda29d90]
[fv-az1269-668:05821] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f40fda29e40]
[fv-az1269-668:05821] [11] plumed(+0x131e5)[0x55a7991881e5]
[fv-az1269-668:05821] *** End of error message ***
</pre>
{% endraw %}
