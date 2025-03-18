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
[fv-az1341-704:61870] *** Process received signal ***
[fv-az1341-704:61870] Signal: Aborted (6)
[fv-az1341-704:61870] Signal code:  (-6)
[fv-az1341-704:61870] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f59b9245330]
[fv-az1341-704:61870] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f59b929eb2c]
[fv-az1341-704:61870] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f59b924527e]
[fv-az1341-704:61870] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f59b92288ff]
[fv-az1341-704:61870] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f59b96a5ff5]
[fv-az1341-704:61870] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f59b96bb0da]
[fv-az1341-704:61870] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f59b96a5a55]
[fv-az1341-704:61870] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f59b96a5a6f]
[fv-az1341-704:61870] [ 8] plumed_master(+0x146dd)[0x55c5b2adf6dd]
[fv-az1341-704:61870] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f59b922a1ca]
[fv-az1341-704:61870] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f59b922a28b]
[fv-az1341-704:61870] [11] plumed_master(+0x15365)[0x55c5b2ae0365]
[fv-az1341-704:61870] *** End of error message ***
</pre>
{% endraw %}
