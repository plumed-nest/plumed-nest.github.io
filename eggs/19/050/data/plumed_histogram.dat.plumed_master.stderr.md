**Project ID:** [plumID:19.050]({{ '/' | absolute_url }}eggs/19/050/)  
Stderr for source:  plumed_histogram.dat   
Download: [zipped raw stdout](plumed_histogram.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_histogram.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
WARNING: IFile closed in the middle of reading. seems strange!
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @32 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:68924] *** Process received signal ***
[pkrvmbietmlfzoi:68924] Signal: Aborted (6)
[pkrvmbietmlfzoi:68924] Signal code:  (-6)
[pkrvmbietmlfzoi:68924] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f68c3245330]
[pkrvmbietmlfzoi:68924] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f68c329eb2c]
[pkrvmbietmlfzoi:68924] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f68c324527e]
[pkrvmbietmlfzoi:68924] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f68c32288ff]
[pkrvmbietmlfzoi:68924] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f68c36a5ff5]
[pkrvmbietmlfzoi:68924] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f68c36bb0da]
[pkrvmbietmlfzoi:68924] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f68c36a5a55]
[pkrvmbietmlfzoi:68924] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f68c36a5a6f]
[pkrvmbietmlfzoi:68924] [ 8] plumed_master(+0x146dd)[0x563225a1b6dd]
[pkrvmbietmlfzoi:68924] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f68c322a1ca]
[pkrvmbietmlfzoi:68924] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f68c322a28b]
[pkrvmbietmlfzoi:68924] [11] plumed_master(+0x15365)[0x563225a1c365]
[pkrvmbietmlfzoi:68924] *** End of error message ***
</pre>
{% endraw %}
