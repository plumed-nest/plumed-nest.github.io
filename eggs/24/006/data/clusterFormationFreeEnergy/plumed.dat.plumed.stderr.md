**Project ID:** [plumID:24.006]({{ '/' | absolute_url }}eggs/24/006/)  
Stderr for source:  clusterFormationFreeEnergy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CLUSTER_PROPERTIES with label @s22 : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:06182] *** Process received signal ***
[pkrvmbietmlfzoi:06182] Signal: Aborted (6)
[pkrvmbietmlfzoi:06182] Signal code:  (-6)
[pkrvmbietmlfzoi:06182] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb9d9e45330]
[pkrvmbietmlfzoi:06182] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb9d9e9eb2c]
[pkrvmbietmlfzoi:06182] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb9d9e4527e]
[pkrvmbietmlfzoi:06182] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb9d9e288ff]
[pkrvmbietmlfzoi:06182] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb9da2a5ff5]
[pkrvmbietmlfzoi:06182] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb9da2bb0da]
[pkrvmbietmlfzoi:06182] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb9da2a5a55]
[pkrvmbietmlfzoi:06182] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb9da2a5a6f]
[pkrvmbietmlfzoi:06182] [ 8] plumed(+0x146dd)[0x556a92c766dd]
[pkrvmbietmlfzoi:06182] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb9d9e2a1ca]
[pkrvmbietmlfzoi:06182] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb9d9e2a28b]
[pkrvmbietmlfzoi:06182] [11] plumed(+0x15365)[0x556a92c77365]
[pkrvmbietmlfzoi:06182] *** End of error message ***
</pre>
{% endraw %}
