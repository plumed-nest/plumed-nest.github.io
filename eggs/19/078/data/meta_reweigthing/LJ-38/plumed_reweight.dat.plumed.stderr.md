**Project ID:** [plumID:19.078]({{ '/' | absolute_url }}eggs/19/078/)  
Stderr for source:  meta_reweigthing/LJ-38/plumed_reweight.dat   
Download: [zipped raw stdout](plumed_reweight.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_reweight.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action COLLECT with label cc_ns : missing TYPE keyword.  TYPE should specify whether data is to be stored as a vector or a matrix
[fv-az787-589:66243] *** Process received signal ***
[fv-az787-589:66243] Signal: Aborted (6)
[fv-az787-589:66243] Signal code:  (-6)
[fv-az787-589:66243] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd9b7845330]
[fv-az787-589:66243] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd9b789eb2c]
[fv-az787-589:66243] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd9b784527e]
[fv-az787-589:66243] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd9b78288ff]
[fv-az787-589:66243] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd9b7ca5ff5]
[fv-az787-589:66243] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd9b7cbb0da]
[fv-az787-589:66243] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd9b7ca5a55]
[fv-az787-589:66243] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd9b7ca5a6f]
[fv-az787-589:66243] [ 8] plumed(+0x146dd)[0x55c38f7236dd]
[fv-az787-589:66243] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd9b782a1ca]
[fv-az787-589:66243] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd9b782a28b]
[fv-az787-589:66243] [11] plumed(+0x15365)[0x55c38f724365]
[fv-az787-589:66243] *** End of error message ***
</pre>
{% endraw %}
