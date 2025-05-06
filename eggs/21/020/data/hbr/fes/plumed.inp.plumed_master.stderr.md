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
[fv-az2209-645:64839] *** Process received signal ***
[fv-az2209-645:64839] Signal: Aborted (6)
[fv-az2209-645:64839] Signal code:  (-6)
[fv-az2209-645:64839] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1f9e245330]
[fv-az2209-645:64839] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1f9e29eb2c]
[fv-az2209-645:64839] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1f9e24527e]
[fv-az2209-645:64839] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1f9e2288ff]
[fv-az2209-645:64839] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1f9e6a5ff5]
[fv-az2209-645:64839] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1f9e6bb0da]
[fv-az2209-645:64839] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1f9e6a5a55]
[fv-az2209-645:64839] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1f9e6a5a6f]
[fv-az2209-645:64839] [ 8] plumed_master(+0x146dd)[0x5563a7f7c6dd]
[fv-az2209-645:64839] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1f9e22a1ca]
[fv-az2209-645:64839] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1f9e22a28b]
[fv-az2209-645:64839] [11] plumed_master(+0x15365)[0x5563a7f7d365]
[fv-az2209-645:64839] *** End of error message ***
</pre>
{% endraw %}
