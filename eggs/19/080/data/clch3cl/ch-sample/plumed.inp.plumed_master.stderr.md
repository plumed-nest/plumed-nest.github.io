**Project ID:** [plumID:19.080]({{ '/' | absolute_url }}eggs/19/080/)  
Stderr for source:  clch3cl/ch-sample/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @36 : keyword ARG is compulsory for this action
[fv-az797-511:10663] *** Process received signal ***
[fv-az797-511:10663] Signal: Aborted (6)
[fv-az797-511:10663] Signal code:  (-6)
[fv-az797-511:10663] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe911c45330]
[fv-az797-511:10663] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe911c9eb2c]
[fv-az797-511:10663] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe911c4527e]
[fv-az797-511:10663] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe911c288ff]
[fv-az797-511:10663] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe9120a5ff5]
[fv-az797-511:10663] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe9120bb0da]
[fv-az797-511:10663] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe9120a5a55]
[fv-az797-511:10663] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe9120a5a6f]
[fv-az797-511:10663] [ 8] plumed_master(+0x146dd)[0x55af17c016dd]
[fv-az797-511:10663] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe911c2a1ca]
[fv-az797-511:10663] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe911c2a28b]
[fv-az797-511:10663] [11] plumed_master(+0x15365)[0x55af17c02365]
[fv-az797-511:10663] *** End of error message ***
</pre>
{% endraw %}
