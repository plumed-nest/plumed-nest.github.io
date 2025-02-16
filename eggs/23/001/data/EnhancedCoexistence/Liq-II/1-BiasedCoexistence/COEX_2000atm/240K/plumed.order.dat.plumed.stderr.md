**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.order.dat   
Download: [zipped raw stdout](plumed.order.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.order.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:377) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s9 : missing input file ice.pdb
[fv-az1979-234:63551] *** Process received signal ***
[fv-az1979-234:63551] Signal: Aborted (6)
[fv-az1979-234:63551] Signal code:  (-6)
[fv-az1979-234:63551] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fac19e45330]
[fv-az1979-234:63551] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fac19e9eb2c]
[fv-az1979-234:63551] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fac19e4527e]
[fv-az1979-234:63551] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fac19e288ff]
[fv-az1979-234:63551] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fac1a2a5ff5]
[fv-az1979-234:63551] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fac1a2bb0da]
[fv-az1979-234:63551] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fac1a2a5a55]
[fv-az1979-234:63551] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fac1a2a5a6f]
[fv-az1979-234:63551] [ 8] plumed(+0x146dd)[0x5587483ac6dd]
[fv-az1979-234:63551] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fac19e2a1ca]
[fv-az1979-234:63551] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fac19e2a28b]
[fv-az1979-234:63551] [11] plumed(+0x15365)[0x5587483ad365]
[fv-az1979-234:63551] *** End of error message ***
</pre>
{% endraw %}
