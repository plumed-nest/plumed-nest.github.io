**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  DIDE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @34 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:62513] *** Process received signal ***
[pkrvmbietmlfzoi:62513] Signal: Aborted (6)
[pkrvmbietmlfzoi:62513] Signal code:  (-6)
[pkrvmbietmlfzoi:62513] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f711e645330]
[pkrvmbietmlfzoi:62513] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f711e69eb2c]
[pkrvmbietmlfzoi:62513] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f711e64527e]
[pkrvmbietmlfzoi:62513] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f711e6288ff]
[pkrvmbietmlfzoi:62513] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f711eaa5ff5]
[pkrvmbietmlfzoi:62513] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f711eabb0da]
[pkrvmbietmlfzoi:62513] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f711eaa5a55]
[pkrvmbietmlfzoi:62513] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f711eaa5a6f]
[pkrvmbietmlfzoi:62513] [ 8] plumed_master(+0x146dd)[0x561d4e6ab6dd]
[pkrvmbietmlfzoi:62513] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f711e62a1ca]
[pkrvmbietmlfzoi:62513] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f711e62a28b]
[pkrvmbietmlfzoi:62513] [11] plumed_master(+0x15365)[0x561d4e6ac365]
[pkrvmbietmlfzoi:62513] *** End of error message ***
</pre>
{% endraw %}
