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
[pkrvmbietmlfzoi:06086] *** Process received signal ***
[pkrvmbietmlfzoi:06086] Signal: Aborted (6)
[pkrvmbietmlfzoi:06086] Signal code:  (-6)
[pkrvmbietmlfzoi:06086] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6d3b845330]
[pkrvmbietmlfzoi:06086] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6d3b89eb2c]
[pkrvmbietmlfzoi:06086] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6d3b84527e]
[pkrvmbietmlfzoi:06086] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6d3b8288ff]
[pkrvmbietmlfzoi:06086] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6d3bca5ff5]
[pkrvmbietmlfzoi:06086] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6d3bcbb0da]
[pkrvmbietmlfzoi:06086] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6d3bca5a55]
[pkrvmbietmlfzoi:06086] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6d3bca5a6f]
[pkrvmbietmlfzoi:06086] [ 8] plumed_master(+0x146dd)[0x55f5e62df6dd]
[pkrvmbietmlfzoi:06086] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6d3b82a1ca]
[pkrvmbietmlfzoi:06086] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6d3b82a28b]
[pkrvmbietmlfzoi:06086] [11] plumed_master(+0x15365)[0x55f5e62e0365]
[pkrvmbietmlfzoi:06086] *** End of error message ***
</pre>
{% endraw %}
