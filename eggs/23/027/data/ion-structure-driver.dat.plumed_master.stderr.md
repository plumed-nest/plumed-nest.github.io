**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  ion-structure-driver.dat   
Download: [zipped raw stdout](ion-structure-driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](ion-structure-driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:373) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs0l : keyword ARG is compulsory for this action
[pkrvmbietmlfzoi:08037] *** Process received signal ***
[pkrvmbietmlfzoi:08037] Signal: Aborted (6)
[pkrvmbietmlfzoi:08037] Signal code:  (-6)
[pkrvmbietmlfzoi:08037] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f63cfc45330]
[pkrvmbietmlfzoi:08037] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f63cfc9eb2c]
[pkrvmbietmlfzoi:08037] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f63cfc4527e]
[pkrvmbietmlfzoi:08037] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f63cfc288ff]
[pkrvmbietmlfzoi:08037] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f63d00a5ff5]
[pkrvmbietmlfzoi:08037] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f63d00bb0da]
[pkrvmbietmlfzoi:08037] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f63d00a5a55]
[pkrvmbietmlfzoi:08037] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f63d00a5a6f]
[pkrvmbietmlfzoi:08037] [ 8] plumed_master(+0x146dd)[0x5636b9cc26dd]
[pkrvmbietmlfzoi:08037] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f63cfc2a1ca]
[pkrvmbietmlfzoi:08037] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f63cfc2a28b]
[pkrvmbietmlfzoi:08037] [11] plumed_master(+0x15365)[0x5636b9cc3365]
[pkrvmbietmlfzoi:08037] *** End of error message ***
</pre>
{% endraw %}
