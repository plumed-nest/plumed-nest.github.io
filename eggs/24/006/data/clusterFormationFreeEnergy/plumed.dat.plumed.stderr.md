**Project ID:** [plumID:24.006]({{ '/' | absolute_url }}eggs/24/006/)  
Stderr for source:  clusterFormationFreeEnergy/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action CLUSTER_PROPERTIES with label @s22 : keyword ARG is compulsory for this action
[fv-az1693-957:62610] *** Process received signal ***
[fv-az1693-957:62610] Signal: Aborted (6)
[fv-az1693-957:62610] Signal code:  (-6)
[fv-az1693-957:62610] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5388045330]
[fv-az1693-957:62610] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f538809eb2c]
[fv-az1693-957:62610] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f538804527e]
[fv-az1693-957:62610] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f53880288ff]
[fv-az1693-957:62610] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f53884a5ff5]
[fv-az1693-957:62610] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f53884bb0da]
[fv-az1693-957:62610] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f53884a5a55]
[fv-az1693-957:62610] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f53884a5a6f]
[fv-az1693-957:62610] [ 8] plumed(+0x146dd)[0x5566ff0c06dd]
[fv-az1693-957:62610] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f538802a1ca]
[fv-az1693-957:62610] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f538802a28b]
[fv-az1693-957:62610] [11] plumed(+0x15365)[0x5566ff0c1365]
[fv-az1693-957:62610] *** End of error message ***
</pre>
{% endraw %}
