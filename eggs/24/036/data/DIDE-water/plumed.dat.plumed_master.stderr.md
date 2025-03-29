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
[fv-az1374-136:61192] *** Process received signal ***
[fv-az1374-136:61192] Signal: Aborted (6)
[fv-az1374-136:61192] Signal code:  (-6)
[fv-az1374-136:61192] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f194a245330]
[fv-az1374-136:61192] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f194a29eb2c]
[fv-az1374-136:61192] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f194a24527e]
[fv-az1374-136:61192] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f194a2288ff]
[fv-az1374-136:61192] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f194a6a5ff5]
[fv-az1374-136:61192] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f194a6bb0da]
[fv-az1374-136:61192] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f194a6a5a55]
[fv-az1374-136:61192] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f194a6a5a6f]
[fv-az1374-136:61192] [ 8] plumed_master(+0x146dd)[0x56533d2ba6dd]
[fv-az1374-136:61192] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f194a22a1ca]
[fv-az1374-136:61192] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f194a22a28b]
[fv-az1374-136:61192] [11] plumed_master(+0x15365)[0x56533d2bb365]
[fv-az1374-136:61192] *** End of error message ***
</pre>
{% endraw %}
