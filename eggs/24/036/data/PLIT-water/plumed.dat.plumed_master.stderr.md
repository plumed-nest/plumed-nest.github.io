**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT-water/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @46 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:62758] *** Process received signal ***
[pkrvmbietmlfzoi:62758] Signal: Aborted (6)
[pkrvmbietmlfzoi:62758] Signal code:  (-6)
[pkrvmbietmlfzoi:62758] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0258e45330]
[pkrvmbietmlfzoi:62758] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0258e9eb2c]
[pkrvmbietmlfzoi:62758] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0258e4527e]
[pkrvmbietmlfzoi:62758] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0258e288ff]
[pkrvmbietmlfzoi:62758] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f02592a5ff5]
[pkrvmbietmlfzoi:62758] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f02592bb0da]
[pkrvmbietmlfzoi:62758] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f02592a5a55]
[pkrvmbietmlfzoi:62758] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f02592a5a6f]
[pkrvmbietmlfzoi:62758] [ 8] plumed_master(+0x146dd)[0x5556311e16dd]
[pkrvmbietmlfzoi:62758] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0258e2a1ca]
[pkrvmbietmlfzoi:62758] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0258e2a28b]
[pkrvmbietmlfzoi:62758] [11] plumed_master(+0x15365)[0x5556311e2365]
[pkrvmbietmlfzoi:62758] *** End of error message ***
</pre>
{% endraw %}
