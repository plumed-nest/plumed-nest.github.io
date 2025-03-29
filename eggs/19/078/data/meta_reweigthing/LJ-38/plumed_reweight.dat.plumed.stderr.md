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
[fv-az789-879:66310] *** Process received signal ***
[fv-az789-879:66310] Signal: Aborted (6)
[fv-az789-879:66310] Signal code:  (-6)
[fv-az789-879:66310] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7c85c45330]
[fv-az789-879:66310] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7c85c9eb2c]
[fv-az789-879:66310] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7c85c4527e]
[fv-az789-879:66310] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7c85c288ff]
[fv-az789-879:66310] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7c860a5ff5]
[fv-az789-879:66310] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7c860bb0da]
[fv-az789-879:66310] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7c860a5a55]
[fv-az789-879:66310] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7c860a5a6f]
[fv-az789-879:66310] [ 8] plumed(+0x146dd)[0x55b2428636dd]
[fv-az789-879:66310] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7c85c2a1ca]
[fv-az789-879:66310] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7c85c2a28b]
[fv-az789-879:66310] [11] plumed(+0x15365)[0x55b242864365]
[fv-az789-879:66310] *** End of error message ***
</pre>
{% endraw %}
