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
[fv-az1267-279:62256] *** Process received signal ***
[fv-az1267-279:62256] Signal: Aborted (6)
[fv-az1267-279:62256] Signal code:  (-6)
[fv-az1267-279:62256] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8037245330]
[fv-az1267-279:62256] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f803729eb2c]
[fv-az1267-279:62256] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f803724527e]
[fv-az1267-279:62256] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f80372288ff]
[fv-az1267-279:62256] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f80376a5ff5]
[fv-az1267-279:62256] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f80376bb0da]
[fv-az1267-279:62256] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f80376a5a55]
[fv-az1267-279:62256] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f80376a5a6f]
[fv-az1267-279:62256] [ 8] plumed_master(+0x146dd)[0x557688c016dd]
[fv-az1267-279:62256] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f803722a1ca]
[fv-az1267-279:62256] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f803722a28b]
[fv-az1267-279:62256] [11] plumed_master(+0x15365)[0x557688c02365]
[fv-az1267-279:62256] *** End of error message ***
</pre>
{% endraw %}
