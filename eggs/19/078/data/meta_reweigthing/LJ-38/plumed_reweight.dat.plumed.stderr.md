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
[fv-az2035-366:11398] *** Process received signal ***
[fv-az2035-366:11398] Signal: Aborted (6)
[fv-az2035-366:11398] Signal code:  (-6)
[fv-az2035-366:11398] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5011e45330]
[fv-az2035-366:11398] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5011e9eb2c]
[fv-az2035-366:11398] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5011e4527e]
[fv-az2035-366:11398] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5011e288ff]
[fv-az2035-366:11398] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f50122a5ff5]
[fv-az2035-366:11398] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f50122bb0da]
[fv-az2035-366:11398] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f50122a5a55]
[fv-az2035-366:11398] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f50122a5a6f]
[fv-az2035-366:11398] [ 8] plumed(+0x146dd)[0x559b3bbc06dd]
[fv-az2035-366:11398] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5011e2a1ca]
[fv-az2035-366:11398] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5011e2a28b]
[fv-az2035-366:11398] [11] plumed(+0x15365)[0x559b3bbc1365]
[fv-az2035-366:11398] *** End of error message ***
</pre>
{% endraw %}
