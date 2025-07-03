**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  water-structure-driver.dat   
Download: [zipped raw stdout](water-structure-driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](water-structure-driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @179 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:07999] *** Process received signal ***
[pkrvmbietmlfzoi:07999] Signal: Aborted (6)
[pkrvmbietmlfzoi:07999] Signal code:  (-6)
[pkrvmbietmlfzoi:07999] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3308645330]
[pkrvmbietmlfzoi:07999] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f330869eb2c]
[pkrvmbietmlfzoi:07999] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f330864527e]
[pkrvmbietmlfzoi:07999] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f33086288ff]
[pkrvmbietmlfzoi:07999] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3308aa5ff5]
[pkrvmbietmlfzoi:07999] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3308abb0da]
[pkrvmbietmlfzoi:07999] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3308aa5a55]
[pkrvmbietmlfzoi:07999] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3308aa5a6f]
[pkrvmbietmlfzoi:07999] [ 8] plumed_master(+0x146dd)[0x5594c7c776dd]
[pkrvmbietmlfzoi:07999] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f330862a1ca]
[pkrvmbietmlfzoi:07999] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f330862a28b]
[pkrvmbietmlfzoi:07999] [11] plumed_master(+0x15365)[0x5594c7c78365]
[pkrvmbietmlfzoi:07999] *** End of error message ***
</pre>
{% endraw %}
