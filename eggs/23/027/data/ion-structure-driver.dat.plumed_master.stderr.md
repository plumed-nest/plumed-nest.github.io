**Project ID:** [plumID:23.027]({{ '/' | absolute_url }}eggs/23/027/)  
Stderr for source:  ion-structure-driver.dat   
Download: [zipped raw stdout](ion-structure-driver.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](ion-structure-driver.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DFSCLUSTERING with label dfs0l : keyword ARG is compulsory for this action
[pkrvmf6wy0o8zjz:62387] *** Process received signal ***
[pkrvmf6wy0o8zjz:62387] Signal: Aborted (6)
[pkrvmf6wy0o8zjz:62387] Signal code:  (-6)
[pkrvmf6wy0o8zjz:62387] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f672fe45330]
[pkrvmf6wy0o8zjz:62387] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f672fe9eb2c]
[pkrvmf6wy0o8zjz:62387] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f672fe4527e]
[pkrvmf6wy0o8zjz:62387] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f672fe288ff]
[pkrvmf6wy0o8zjz:62387] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f67302a5ff5]
[pkrvmf6wy0o8zjz:62387] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f67302bb0da]
[pkrvmf6wy0o8zjz:62387] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f67302a5a55]
[pkrvmf6wy0o8zjz:62387] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f67302a5a6f]
[pkrvmf6wy0o8zjz:62387] [ 8] plumed_master(+0x146dd)[0x5601a3c0c6dd]
[pkrvmf6wy0o8zjz:62387] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f672fe2a1ca]
[pkrvmf6wy0o8zjz:62387] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f672fe2a28b]
[pkrvmf6wy0o8zjz:62387] [11] plumed_master(+0x15365)[0x5601a3c0d365]
[pkrvmf6wy0o8zjz:62387] *** End of error message ***
</pre>
{% endraw %}
