**Project ID:** [plumID:22.028]({{ '/' | absolute_url }}eggs/22/028/)  
Stderr for source:  plumed_pucker.dat   
Download: [zipped raw stdout](plumed_pucker.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_pucker.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action READ with label puck1 : could not find file named COLVAR_theta.0
[fv-az797-511:07089] *** Process received signal ***
[fv-az797-511:07089] Signal: Aborted (6)
[fv-az797-511:07089] Signal code:  (-6)
[fv-az797-511:07089] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdef9c45330]
[fv-az797-511:07089] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdef9c9eb2c]
[fv-az797-511:07089] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdef9c4527e]
[fv-az797-511:07089] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdef9c288ff]
[fv-az797-511:07089] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdefa0a5ff5]
[fv-az797-511:07089] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdefa0bb0da]
[fv-az797-511:07089] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdefa0a5a55]
[fv-az797-511:07089] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdefa0a5a6f]
[fv-az797-511:07089] [ 8] plumed_master(+0x146dd)[0x561699bff6dd]
[fv-az797-511:07089] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdef9c2a1ca]
[fv-az797-511:07089] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdef9c2a28b]
[fv-az797-511:07089] [11] plumed_master(+0x15365)[0x561699c00365]
[fv-az797-511:07089] *** End of error message ***
</pre>
{% endraw %}
