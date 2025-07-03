**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.start.dat   
Download: [zipped raw stdout](plumed.start.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.start.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[pkrvmbietmlfzoi:07112] *** Process received signal ***
[pkrvmbietmlfzoi:07112] Signal: Aborted (6)
[pkrvmbietmlfzoi:07112] Signal code:  (-6)
[pkrvmbietmlfzoi:07112] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1aa6e45330]
[pkrvmbietmlfzoi:07112] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1aa6e9eb2c]
[pkrvmbietmlfzoi:07112] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1aa6e4527e]
[pkrvmbietmlfzoi:07112] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1aa6e288ff]
[pkrvmbietmlfzoi:07112] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1aa72a5ff5]
[pkrvmbietmlfzoi:07112] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1aa72bb0da]
[pkrvmbietmlfzoi:07112] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1aa72a5a55]
[pkrvmbietmlfzoi:07112] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1aa72a5a6f]
[pkrvmbietmlfzoi:07112] [ 8] plumed(+0x146dd)[0x562f2a9bf6dd]
[pkrvmbietmlfzoi:07112] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1aa6e2a1ca]
[pkrvmbietmlfzoi:07112] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1aa6e2a28b]
[pkrvmbietmlfzoi:07112] [11] plumed(+0x15365)[0x562f2a9c0365]
[pkrvmbietmlfzoi:07112] *** End of error message ***
</pre>
{% endraw %}
