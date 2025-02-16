**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_2D_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @90 : keyword ARG is compulsory for this action
[fv-az1781-845:61085] *** Process received signal ***
[fv-az1781-845:61085] Signal: Aborted (6)
[fv-az1781-845:61085] Signal code:  (-6)
[fv-az1781-845:61085] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f83e2a45330]
[fv-az1781-845:61085] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f83e2a9eb2c]
[fv-az1781-845:61085] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f83e2a4527e]
[fv-az1781-845:61085] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f83e2a288ff]
[fv-az1781-845:61085] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f83e2ea5ff5]
[fv-az1781-845:61085] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f83e2ebb0da]
[fv-az1781-845:61085] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f83e2ea5a55]
[fv-az1781-845:61085] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f83e2ea5a6f]
[fv-az1781-845:61085] [ 8] plumed_master(+0x146dd)[0x561753e6b6dd]
[fv-az1781-845:61085] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f83e2a2a1ca]
[fv-az1781-845:61085] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f83e2a2a28b]
[fv-az1781-845:61085] [11] plumed_master(+0x15365)[0x561753e6c365]
[fv-az1781-845:61085] *** End of error message ***
</pre>
{% endraw %}
