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
[fv-az789-879:61107] *** Process received signal ***
[fv-az789-879:61107] Signal: Aborted (6)
[fv-az789-879:61107] Signal code:  (-6)
[fv-az789-879:61107] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8bb4e45330]
[fv-az789-879:61107] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8bb4e9eb2c]
[fv-az789-879:61107] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8bb4e4527e]
[fv-az789-879:61107] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8bb4e288ff]
[fv-az789-879:61107] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8bb52a5ff5]
[fv-az789-879:61107] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8bb52bb0da]
[fv-az789-879:61107] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8bb52a5a55]
[fv-az789-879:61107] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8bb52a5a6f]
[fv-az789-879:61107] [ 8] plumed_master(+0x146dd)[0x55e2abeec6dd]
[fv-az789-879:61107] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8bb4e2a1ca]
[fv-az789-879:61107] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8bb4e2a28b]
[fv-az789-879:61107] [11] plumed_master(+0x15365)[0x55e2abeed365]
[fv-az789-879:61107] *** End of error message ***
</pre>
{% endraw %}
