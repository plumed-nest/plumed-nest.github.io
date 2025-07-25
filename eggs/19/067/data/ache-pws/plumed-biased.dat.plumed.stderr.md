**Project ID:** [plumID:19.067]({{ '/' | absolute_url }}eggs/19/067/)  
Stderr for source:  ache-pws/plumed-biased.dat   
Download: [zipped raw stdout](plumed-biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed-biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action METAD with label meta : When using ADAPTIVE Gaussians on a grid SIGMA_MIN must be specified
[pkrvmpptgkbjq6m:10932] *** Process received signal ***
[pkrvmpptgkbjq6m:10932] Signal: Aborted (6)
[pkrvmpptgkbjq6m:10932] Signal code:  (-6)
[pkrvmpptgkbjq6m:10932] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa109445330]
[pkrvmpptgkbjq6m:10932] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa10949eb2c]
[pkrvmpptgkbjq6m:10932] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa10944527e]
[pkrvmpptgkbjq6m:10932] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa1094288ff]
[pkrvmpptgkbjq6m:10932] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa1098a5ff5]
[pkrvmpptgkbjq6m:10932] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa1098bb0da]
[pkrvmpptgkbjq6m:10932] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa1098a5a55]
[pkrvmpptgkbjq6m:10932] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa1098a5a6f]
[pkrvmpptgkbjq6m:10932] [ 8] plumed(+0x146dd)[0x564b49e616dd]
[pkrvmpptgkbjq6m:10932] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa10942a1ca]
[pkrvmpptgkbjq6m:10932] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa10942a28b]
[pkrvmpptgkbjq6m:10932] [11] plumed(+0x15365)[0x564b49e62365]
[pkrvmpptgkbjq6m:10932] *** End of error message ***
</pre>
{% endraw %}
