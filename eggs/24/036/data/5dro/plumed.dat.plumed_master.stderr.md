**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  5dro/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @30 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:05838] *** Process received signal ***
[pkrvmbietmlfzoi:05838] Signal: Aborted (6)
[pkrvmbietmlfzoi:05838] Signal code:  (-6)
[pkrvmbietmlfzoi:05838] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fcc0a245330]
[pkrvmbietmlfzoi:05838] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fcc0a29eb2c]
[pkrvmbietmlfzoi:05838] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fcc0a24527e]
[pkrvmbietmlfzoi:05838] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fcc0a2288ff]
[pkrvmbietmlfzoi:05838] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fcc0a6a5ff5]
[pkrvmbietmlfzoi:05838] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fcc0a6bb0da]
[pkrvmbietmlfzoi:05838] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fcc0a6a5a55]
[pkrvmbietmlfzoi:05838] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fcc0a6a5a6f]
[pkrvmbietmlfzoi:05838] [ 8] plumed_master(+0x146dd)[0x5576d143b6dd]
[pkrvmbietmlfzoi:05838] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fcc0a22a1ca]
[pkrvmbietmlfzoi:05838] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fcc0a22a28b]
[pkrvmbietmlfzoi:05838] [11] plumed_master(+0x15365)[0x5576d143c365]
[pkrvmbietmlfzoi:05838] *** End of error message ***
</pre>
{% endraw %}
