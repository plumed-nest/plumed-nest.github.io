**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:05981] *** Process received signal ***
[pkrvmbietmlfzoi:05981] Signal: Aborted (6)
[pkrvmbietmlfzoi:05981] Signal code:  (-6)
[pkrvmbietmlfzoi:05981] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f063e045330]
[pkrvmbietmlfzoi:05981] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f063e09eb2c]
[pkrvmbietmlfzoi:05981] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f063e04527e]
[pkrvmbietmlfzoi:05981] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f063e0288ff]
[pkrvmbietmlfzoi:05981] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f063e4a5ff5]
[pkrvmbietmlfzoi:05981] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f063e4bb0da]
[pkrvmbietmlfzoi:05981] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f063e4a5a55]
[pkrvmbietmlfzoi:05981] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f063e4a5a6f]
[pkrvmbietmlfzoi:05981] [ 8] plumed_master(+0x146dd)[0x5618b044d6dd]
[pkrvmbietmlfzoi:05981] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f063e02a1ca]
[pkrvmbietmlfzoi:05981] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f063e02a28b]
[pkrvmbietmlfzoi:05981] [11] plumed_master(+0x15365)[0x5618b044e365]
[pkrvmbietmlfzoi:05981] *** End of error message ***
</pre>
{% endraw %}
