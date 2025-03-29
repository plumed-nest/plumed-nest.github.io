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
[fv-az1279-218:63678] *** Process received signal ***
[fv-az1279-218:63678] Signal: Aborted (6)
[fv-az1279-218:63678] Signal code:  (-6)
[fv-az1279-218:63678] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc7ea445330]
[fv-az1279-218:63678] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc7ea49eb2c]
[fv-az1279-218:63678] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc7ea44527e]
[fv-az1279-218:63678] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc7ea4288ff]
[fv-az1279-218:63678] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc7ea8a5ff5]
[fv-az1279-218:63678] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc7ea8bb0da]
[fv-az1279-218:63678] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc7ea8a5a55]
[fv-az1279-218:63678] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc7ea8a5a6f]
[fv-az1279-218:63678] [ 8] plumed_master(+0x146dd)[0x561f7abd76dd]
[fv-az1279-218:63678] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc7ea42a1ca]
[fv-az1279-218:63678] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc7ea42a28b]
[fv-az1279-218:63678] [11] plumed_master(+0x15365)[0x561f7abd8365]
[fv-az1279-218:63678] *** End of error message ***
</pre>
{% endraw %}
