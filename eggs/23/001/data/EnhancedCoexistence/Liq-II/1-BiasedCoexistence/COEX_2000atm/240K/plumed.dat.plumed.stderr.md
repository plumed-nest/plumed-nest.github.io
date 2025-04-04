**Project ID:** [plumID:23.001]({{ '/' | absolute_url }}eggs/23/001/)  
Stderr for source:  EnhancedCoexistence/Liq-II/1-BiasedCoexistence/COEX_2000atm/240K/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::ExceptionError'
what():
(core/Action.cpp:375) void PLMD::Action::error(const std::string&) const
ERROR in input to action ENVIRONMENTSIMILARITY with label @s10 : missing input file ice.pdb
[fv-az1624-565:06333] *** Process received signal ***
[fv-az1624-565:06333] Signal: Aborted (6)
[fv-az1624-565:06333] Signal code:  (-6)
[fv-az1624-565:06333] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd4c8845330]
[fv-az1624-565:06333] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd4c889eb2c]
[fv-az1624-565:06333] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd4c884527e]
[fv-az1624-565:06333] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd4c88288ff]
[fv-az1624-565:06333] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd4c8ca5ff5]
[fv-az1624-565:06333] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd4c8cbb0da]
[fv-az1624-565:06333] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd4c8ca5a55]
[fv-az1624-565:06333] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd4c8ca5a6f]
[fv-az1624-565:06333] [ 8] plumed(+0x146dd)[0x5558c28e26dd]
[fv-az1624-565:06333] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd4c882a1ca]
[fv-az1624-565:06333] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd4c882a28b]
[fv-az1624-565:06333] [11] plumed(+0x15365)[0x5558c28e3365]
[fv-az1624-565:06333] *** End of error message ***
</pre>
{% endraw %}
