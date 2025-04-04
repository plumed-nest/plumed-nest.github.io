**Project ID:** [plumID:24.036]({{ '/' | absolute_url }}eggs/24/036/)  
Stderr for source:  DIDE-water/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @47 : keyword ARG is compulsory for this action
[fv-az1360-658:05493] *** Process received signal ***
[fv-az1360-658:05493] Signal: Aborted (6)
[fv-az1360-658:05493] Signal code:  (-6)
[fv-az1360-658:05493] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1873e45330]
[fv-az1360-658:05493] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1873e9eb2c]
[fv-az1360-658:05493] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1873e4527e]
[fv-az1360-658:05493] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1873e288ff]
[fv-az1360-658:05493] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f18742a5ff5]
[fv-az1360-658:05493] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f18742bb0da]
[fv-az1360-658:05493] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f18742a5a55]
[fv-az1360-658:05493] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f18742a5a6f]
[fv-az1360-658:05493] [ 8] plumed_master(+0x146dd)[0x56058b9436dd]
[fv-az1360-658:05493] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1873e2a1ca]
[fv-az1360-658:05493] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1873e2a28b]
[fv-az1360-658:05493] [11] plumed_master(+0x15365)[0x56058b944365]
[fv-az1360-658:05493] *** End of error message ***
</pre>
{% endraw %}
