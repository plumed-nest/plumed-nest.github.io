**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.order.dat   
Download: [zipped raw stdout](plumed.order.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.order.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[fv-az1979-234:63567] *** Process received signal ***
[fv-az1979-234:63567] Signal: Aborted (6)
[fv-az1979-234:63567] Signal code:  (-6)
[fv-az1979-234:63567] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f71b7a45330]
[fv-az1979-234:63567] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f71b7a9eb2c]
[fv-az1979-234:63567] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f71b7a4527e]
[fv-az1979-234:63567] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f71b7a288ff]
[fv-az1979-234:63567] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f71b7ea5ff5]
[fv-az1979-234:63567] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f71b7ebb0da]
[fv-az1979-234:63567] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f71b7ea5a55]
[fv-az1979-234:63567] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f71b7ea5a6f]
[fv-az1979-234:63567] [ 8] plumed_master(+0x146dd)[0x55a9eed076dd]
[fv-az1979-234:63567] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f71b7a2a1ca]
[fv-az1979-234:63567] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f71b7a2a28b]
[fv-az1979-234:63567] [11] plumed_master(+0x15365)[0x55a9eed08365]
[fv-az1979-234:63567] *** End of error message ***
</pre>
{% endraw %}
