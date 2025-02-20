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
[fv-az1444-322:07490] *** Process received signal ***
[fv-az1444-322:07490] Signal: Aborted (6)
[fv-az1444-322:07490] Signal code:  (-6)
[fv-az1444-322:07490] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f62a2e45330]
[fv-az1444-322:07490] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f62a2e9eb2c]
[fv-az1444-322:07490] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f62a2e4527e]
[fv-az1444-322:07490] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f62a2e288ff]
[fv-az1444-322:07490] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f62a32a5ff5]
[fv-az1444-322:07490] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f62a32bb0da]
[fv-az1444-322:07490] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f62a32a5a55]
[fv-az1444-322:07490] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f62a32a5a6f]
[fv-az1444-322:07490] [ 8] plumed_master(+0x146dd)[0x5566fe84f6dd]
[fv-az1444-322:07490] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f62a2e2a1ca]
[fv-az1444-322:07490] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f62a2e2a28b]
[fv-az1444-322:07490] [11] plumed_master(+0x15365)[0x5566fe850365]
[fv-az1444-322:07490] *** End of error message ***
</pre>
{% endraw %}
