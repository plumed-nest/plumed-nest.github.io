**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @173 : keyword ARG is compulsory for this action
[fv-az1781-845:61125] *** Process received signal ***
[fv-az1781-845:61125] Signal: Aborted (6)
[fv-az1781-845:61125] Signal code:  (-6)
[fv-az1781-845:61125] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff2d2645330]
[fv-az1781-845:61125] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff2d269eb2c]
[fv-az1781-845:61125] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff2d264527e]
[fv-az1781-845:61125] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff2d26288ff]
[fv-az1781-845:61125] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff2d2aa5ff5]
[fv-az1781-845:61125] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff2d2abb0da]
[fv-az1781-845:61125] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff2d2aa5a55]
[fv-az1781-845:61125] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff2d2aa5a6f]
[fv-az1781-845:61125] [ 8] plumed_master(+0x146dd)[0x561e69d786dd]
[fv-az1781-845:61125] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff2d262a1ca]
[fv-az1781-845:61125] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff2d262a28b]
[fv-az1781-845:61125] [11] plumed_master(+0x15365)[0x561e69d79365]
[fv-az1781-845:61125] *** End of error message ***
</pre>
{% endraw %}
