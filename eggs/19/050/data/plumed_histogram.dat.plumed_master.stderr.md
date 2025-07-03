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
[pkrvmbietmlfzoi:13956] *** Process received signal ***
[pkrvmbietmlfzoi:13956] Signal: Aborted (6)
[pkrvmbietmlfzoi:13956] Signal code:  (-6)
[pkrvmbietmlfzoi:13956] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1bca245330]
[pkrvmbietmlfzoi:13956] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1bca29eb2c]
[pkrvmbietmlfzoi:13956] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1bca24527e]
[pkrvmbietmlfzoi:13956] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1bca2288ff]
[pkrvmbietmlfzoi:13956] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1bca6a5ff5]
[pkrvmbietmlfzoi:13956] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1bca6bb0da]
[pkrvmbietmlfzoi:13956] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1bca6a5a55]
[pkrvmbietmlfzoi:13956] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1bca6a5a6f]
[pkrvmbietmlfzoi:13956] [ 8] plumed_master(+0x146dd)[0x55c3b9cd86dd]
[pkrvmbietmlfzoi:13956] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1bca22a1ca]
[pkrvmbietmlfzoi:13956] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1bca22a28b]
[pkrvmbietmlfzoi:13956] [11] plumed_master(+0x15365)[0x55c3b9cd9365]
[pkrvmbietmlfzoi:13956] *** End of error message ***
</pre>
{% endraw %}
