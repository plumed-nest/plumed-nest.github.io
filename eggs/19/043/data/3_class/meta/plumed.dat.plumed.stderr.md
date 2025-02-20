**Project ID:** [plumID:19.043]({{ '/' | absolute_url }}eggs/19/043/)  
Stderr for source:  3_class/meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label metad : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[fv-az797-511:11242] *** Process received signal ***
[fv-az797-511:11242] Signal: Aborted (6)
[fv-az797-511:11242] Signal code:  (-6)
[fv-az797-511:11242] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9135045330]
[fv-az797-511:11242] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f913509eb2c]
[fv-az797-511:11242] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f913504527e]
[fv-az797-511:11242] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f91350288ff]
[fv-az797-511:11242] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f91354a5ff5]
[fv-az797-511:11242] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f91354bb0da]
[fv-az797-511:11242] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f91354a5a55]
[fv-az797-511:11242] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f91354a5a6f]
[fv-az797-511:11242] [ 8] plumed(+0x146dd)[0x55af351c66dd]
[fv-az797-511:11242] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f913502a1ca]
[fv-az797-511:11242] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f913502a28b]
[fv-az797-511:11242] [11] plumed(+0x15365)[0x55af351c7365]
[fv-az797-511:11242] *** End of error message ***
</pre>
{% endraw %}
