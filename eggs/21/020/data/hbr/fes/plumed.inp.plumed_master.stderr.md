**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/fes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @52 : keyword ARG is compulsory for this action
[fv-az1267-279:67233] *** Process received signal ***
[fv-az1267-279:67233] Signal: Aborted (6)
[fv-az1267-279:67233] Signal code:  (-6)
[fv-az1267-279:67233] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f939ee45330]
[fv-az1267-279:67233] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f939ee9eb2c]
[fv-az1267-279:67233] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f939ee4527e]
[fv-az1267-279:67233] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f939ee288ff]
[fv-az1267-279:67233] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f939f2a5ff5]
[fv-az1267-279:67233] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f939f2bb0da]
[fv-az1267-279:67233] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f939f2a5a55]
[fv-az1267-279:67233] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f939f2a5a6f]
[fv-az1267-279:67233] [ 8] plumed_master(+0x146dd)[0x558006e466dd]
[fv-az1267-279:67233] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f939ee2a1ca]
[fv-az1267-279:67233] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f939ee2a28b]
[fv-az1267-279:67233] [11] plumed_master(+0x15365)[0x558006e47365]
[fv-az1267-279:67233] *** End of error message ***
</pre>
{% endraw %}
