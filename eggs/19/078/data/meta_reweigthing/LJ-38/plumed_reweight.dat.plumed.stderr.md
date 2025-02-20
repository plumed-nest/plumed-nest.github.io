**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/LJ-38/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action COLLECT with label cc_ns : missing TYPE keyword.  TYPE should specify whether data is to be stored as a vector or a matrix
[fv-az1720-841:10301] *** Process received signal ***
[fv-az1720-841:10301] Signal: Aborted (6)
[fv-az1720-841:10301] Signal code:  (-6)
[fv-az1720-841:10301] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3928845330]
[fv-az1720-841:10301] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f392889eb2c]
[fv-az1720-841:10301] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f392884527e]
[fv-az1720-841:10301] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f39288288ff]
[fv-az1720-841:10301] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3928ca5ff5]
[fv-az1720-841:10301] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3928cbb0da]
[fv-az1720-841:10301] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3928ca5a55]
[fv-az1720-841:10301] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3928ca5a6f]
[fv-az1720-841:10301] [ 8] plumed(+0x146dd)[0x5561126276dd]
[fv-az1720-841:10301] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f392882a1ca]
[fv-az1720-841:10301] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f392882a28b]
[fv-az1720-841:10301] [11] plumed(+0x15365)[0x556112628365]
[fv-az1720-841:10301] *** End of error message ***
</pre>
{% endraw %}
