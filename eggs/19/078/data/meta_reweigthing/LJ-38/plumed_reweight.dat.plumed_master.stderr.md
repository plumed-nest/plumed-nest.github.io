**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/LJ-38/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COLLECT with label cc_ns : missing TYPE keyword.  TYPE should specify whether data is to be stored as a vector or a matrix
[fv-az790-36:69812] *** Process received signal ***
[fv-az790-36:69812] Signal: Aborted (6)
[fv-az790-36:69812] Signal code:  (-6)
[fv-az790-36:69812] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6833445330]
[fv-az790-36:69812] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f683349eb2c]
[fv-az790-36:69812] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f683344527e]
[fv-az790-36:69812] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f68334288ff]
[fv-az790-36:69812] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f68338a5ff5]
[fv-az790-36:69812] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f68338bb0da]
[fv-az790-36:69812] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f68338a5a55]
[fv-az790-36:69812] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f68338a5a6f]
[fv-az790-36:69812] [ 8] plumed_master(+0x146dd)[0x55e77c4e86dd]
[fv-az790-36:69812] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f683342a1ca]
[fv-az790-36:69812] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f683342a28b]
[fv-az790-36:69812] [11] plumed_master(+0x15365)[0x55e77c4e9365]
[fv-az790-36:69812] *** End of error message ***
</pre>
{% endraw %}
