**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  PLIT/plumed_h1h2.dat   
Download: [zipped raw stdout](plumed_h1h2.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_h1h2.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @48 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:06020] *** Process received signal ***
[pkrvmbietmlfzoi:06020] Signal: Aborted (6)
[pkrvmbietmlfzoi:06020] Signal code:  (-6)
[pkrvmbietmlfzoi:06020] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8fa7445330]
[pkrvmbietmlfzoi:06020] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8fa749eb2c]
[pkrvmbietmlfzoi:06020] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8fa744527e]
[pkrvmbietmlfzoi:06020] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8fa74288ff]
[pkrvmbietmlfzoi:06020] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8fa78a5ff5]
[pkrvmbietmlfzoi:06020] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8fa78bb0da]
[pkrvmbietmlfzoi:06020] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8fa78a5a55]
[pkrvmbietmlfzoi:06020] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8fa78a5a6f]
[pkrvmbietmlfzoi:06020] [ 8] plumed_master(+0x146dd)[0x55e74b5476dd]
[pkrvmbietmlfzoi:06020] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8fa742a1ca]
[pkrvmbietmlfzoi:06020] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8fa742a28b]
[pkrvmbietmlfzoi:06020] [11] plumed_master(+0x15365)[0x55e74b548365]
[pkrvmbietmlfzoi:06020] *** End of error message ***
</pre>
{% endraw %}
