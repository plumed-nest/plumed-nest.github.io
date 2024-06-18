**Project ID:** [plumID:21.016]({{ '/' | absolute_url }}eggs/21/016/)  
Stderr for source:  input_files/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:309) void PLMD::Action::error(const string&) const
ERROR in input to action SAXS with label saxs : cannot understand the following words from the input line : SCALEINT=1
[fv-az883-206:05870] *** Process received signal ***
[fv-az883-206:05870] Signal: Aborted (6)
[fv-az883-206:05870] Signal code:  (-6)
[fv-az883-206:05870] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f08a1842520]
[fv-az883-206:05870] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f08a18969fc]
[fv-az883-206:05870] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f08a1842476]
[fv-az883-206:05870] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f08a18287f3]
[fv-az883-206:05870] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f08a1ca2b9e]
[fv-az883-206:05870] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f08a1cae20c]
[fv-az883-206:05870] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f08a1cae277]
[fv-az883-206:05870] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f08a1cae52b]
[fv-az883-206:05870] [ 8] plumed_master(+0x14274)[0x557b4ce96274]
[fv-az883-206:05870] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f08a1829d90]
[fv-az883-206:05870] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f08a1829e40]
[fv-az883-206:05870] [11] plumed_master(+0x14ed5)[0x557b4ce96ed5]
[fv-az883-206:05870] *** End of error message ***
</pre>
{% endraw %}
