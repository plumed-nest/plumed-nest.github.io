**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-CH3Cl/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @44 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:62720] *** Process received signal ***
[pkrvmbietmlfzoi:62720] Signal: Aborted (6)
[pkrvmbietmlfzoi:62720] Signal code:  (-6)
[pkrvmbietmlfzoi:62720] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4cb3245330]
[pkrvmbietmlfzoi:62720] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4cb329eb2c]
[pkrvmbietmlfzoi:62720] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4cb324527e]
[pkrvmbietmlfzoi:62720] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4cb32288ff]
[pkrvmbietmlfzoi:62720] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f4cb36a5ff5]
[pkrvmbietmlfzoi:62720] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f4cb36bb0da]
[pkrvmbietmlfzoi:62720] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f4cb36a5a55]
[pkrvmbietmlfzoi:62720] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f4cb36a5a6f]
[pkrvmbietmlfzoi:62720] [ 8] plumed_master(+0x146dd)[0x558c704296dd]
[pkrvmbietmlfzoi:62720] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4cb322a1ca]
[pkrvmbietmlfzoi:62720] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4cb322a28b]
[pkrvmbietmlfzoi:62720] [11] plumed_master(+0x15365)[0x558c7042a365]
[pkrvmbietmlfzoi:62720] *** End of error message ***
</pre>
{% endraw %}
