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
[fv-az790-36:69737] *** Process received signal ***
[fv-az790-36:69737] Signal: Aborted (6)
[fv-az790-36:69737] Signal code:  (-6)
[fv-az790-36:69737] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7633a45330]
[fv-az790-36:69737] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7633a9eb2c]
[fv-az790-36:69737] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7633a4527e]
[fv-az790-36:69737] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7633a288ff]
[fv-az790-36:69737] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7633ea5ff5]
[fv-az790-36:69737] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7633ebb0da]
[fv-az790-36:69737] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7633ea5a55]
[fv-az790-36:69737] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7633ea5a6f]
[fv-az790-36:69737] [ 8] plumed(+0x146dd)[0x562a23b6b6dd]
[fv-az790-36:69737] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7633a2a1ca]
[fv-az790-36:69737] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7633a2a28b]
[fv-az790-36:69737] [11] plumed(+0x15365)[0x562a23b6c365]
[fv-az790-36:69737] *** End of error message ***
</pre>
{% endraw %}
