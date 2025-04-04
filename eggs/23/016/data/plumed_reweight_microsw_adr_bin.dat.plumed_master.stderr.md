**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @173 : keyword ARG is compulsory for this action
[fv-az1719-476:07716] *** Process received signal ***
[fv-az1719-476:07716] Signal: Aborted (6)
[fv-az1719-476:07716] Signal code:  (-6)
[fv-az1719-476:07716] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7eff19c45330]
[fv-az1719-476:07716] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7eff19c9eb2c]
[fv-az1719-476:07716] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7eff19c4527e]
[fv-az1719-476:07716] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7eff19c288ff]
[fv-az1719-476:07716] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7eff1a0a5ff5]
[fv-az1719-476:07716] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7eff1a0bb0da]
[fv-az1719-476:07716] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7eff1a0a5a55]
[fv-az1719-476:07716] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7eff1a0a5a6f]
[fv-az1719-476:07716] [ 8] plumed_master(+0x146dd)[0x55acf6cf46dd]
[fv-az1719-476:07716] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7eff19c2a1ca]
[fv-az1719-476:07716] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7eff19c2a28b]
[fv-az1719-476:07716] [11] plumed_master(+0x15365)[0x55acf6cf5365]
[fv-az1719-476:07716] *** End of error message ***
</pre>
{% endraw %}
