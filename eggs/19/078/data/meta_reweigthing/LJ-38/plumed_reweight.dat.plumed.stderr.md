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
[fv-az1680-626:12355] *** Process received signal ***
[fv-az1680-626:12355] Signal: Aborted (6)
[fv-az1680-626:12355] Signal code:  (-6)
[fv-az1680-626:12355] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff152645330]
[fv-az1680-626:12355] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff15269eb2c]
[fv-az1680-626:12355] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff15264527e]
[fv-az1680-626:12355] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff1526288ff]
[fv-az1680-626:12355] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff152aa5ff5]
[fv-az1680-626:12355] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff152abb0da]
[fv-az1680-626:12355] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff152aa5a55]
[fv-az1680-626:12355] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff152aa5a6f]
[fv-az1680-626:12355] [ 8] plumed(+0x146dd)[0x55f482ac06dd]
[fv-az1680-626:12355] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff15262a1ca]
[fv-az1680-626:12355] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff15262a28b]
[fv-az1680-626:12355] [11] plumed(+0x15365)[0x55f482ac1365]
[fv-az1680-626:12355] *** End of error message ***
</pre>
{% endraw %}
