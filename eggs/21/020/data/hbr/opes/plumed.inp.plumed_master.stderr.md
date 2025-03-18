**Project ID:** [plumID:21.020]({{ '/' | absolute_url }}eggs/21/020/)  
Stderr for source:  hbr/opes/plumed.inp   
Download: [zipped raw stdout](plumed.inp.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.inp.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @49 : keyword ARG is compulsory for this action
[fv-az1267-279:67402] *** Process received signal ***
[fv-az1267-279:67402] Signal: Aborted (6)
[fv-az1267-279:67402] Signal code:  (-6)
[fv-az1267-279:67402] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3d97445330]
[fv-az1267-279:67402] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3d9749eb2c]
[fv-az1267-279:67402] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3d9744527e]
[fv-az1267-279:67402] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3d974288ff]
[fv-az1267-279:67402] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3d978a5ff5]
[fv-az1267-279:67402] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3d978bb0da]
[fv-az1267-279:67402] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3d978a5a55]
[fv-az1267-279:67402] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3d978a5a6f]
[fv-az1267-279:67402] [ 8] plumed_master(+0x146dd)[0x55cf4fc276dd]
[fv-az1267-279:67402] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3d9742a1ca]
[fv-az1267-279:67402] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3d9742a28b]
[fv-az1267-279:67402] [11] plumed_master(+0x15365)[0x55cf4fc28365]
[fv-az1267-279:67402] *** End of error message ***
</pre>
{% endraw %}
