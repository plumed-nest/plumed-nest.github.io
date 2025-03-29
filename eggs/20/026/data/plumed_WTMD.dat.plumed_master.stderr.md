**Project ID:** [plumID:20.026]({{ '/' | absolute_url }}eggs/20/026/)  
Stderr for source:  plumed_WTMD.dat   
Download: [zipped raw stdout](plumed_WTMD.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_WTMD.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @79 : keyword ARG is compulsory for this action
[fv-az1374-136:67351] *** Process received signal ***
[fv-az1374-136:67351] Signal: Aborted (6)
[fv-az1374-136:67351] Signal code:  (-6)
[fv-az1374-136:67351] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f10e2645330]
[fv-az1374-136:67351] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f10e269eb2c]
[fv-az1374-136:67351] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f10e264527e]
[fv-az1374-136:67351] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f10e26288ff]
[fv-az1374-136:67351] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f10e2aa5ff5]
[fv-az1374-136:67351] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f10e2abb0da]
[fv-az1374-136:67351] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f10e2aa5a55]
[fv-az1374-136:67351] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f10e2aa5a6f]
[fv-az1374-136:67351] [ 8] plumed_master(+0x146dd)[0x5568997a86dd]
[fv-az1374-136:67351] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f10e262a1ca]
[fv-az1374-136:67351] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f10e262a28b]
[fv-az1374-136:67351] [11] plumed_master(+0x15365)[0x5568997a9365]
[fv-az1374-136:67351] *** End of error message ***
</pre>
{% endraw %}
