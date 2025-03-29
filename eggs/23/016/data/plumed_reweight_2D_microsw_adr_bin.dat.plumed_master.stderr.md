**Project ID:** [plumID:23.016]({{ '/' | absolute_url }}eggs/23/016/)  
Stderr for source:  plumed_reweight_2D_microsw_adr_bin.dat   
Download: [zipped raw stdout](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_reweight_2D_microsw_adr_bin.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action DUMPGRID with label @90 : keyword ARG is compulsory for this action
[fv-az1279-218:63639] *** Process received signal ***
[fv-az1279-218:63639] Signal: Aborted (6)
[fv-az1279-218:63639] Signal code:  (-6)
[fv-az1279-218:63639] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6ba4645330]
[fv-az1279-218:63639] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6ba469eb2c]
[fv-az1279-218:63639] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6ba464527e]
[fv-az1279-218:63639] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6ba46288ff]
[fv-az1279-218:63639] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6ba4aa5ff5]
[fv-az1279-218:63639] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6ba4abb0da]
[fv-az1279-218:63639] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6ba4aa5a55]
[fv-az1279-218:63639] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6ba4aa5a6f]
[fv-az1279-218:63639] [ 8] plumed_master(+0x146dd)[0x557c31a836dd]
[fv-az1279-218:63639] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6ba462a1ca]
[fv-az1279-218:63639] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6ba462a28b]
[fv-az1279-218:63639] [11] plumed_master(+0x15365)[0x557c31a84365]
[fv-az1279-218:63639] *** End of error message ***
</pre>
{% endraw %}
